**Rationale**

We want to create Keynote slides that contain highlighted Ruby source code.

We will create an external tool in Rubymine that transforms the current clipboard contents so that the
code in the clipboard can be pasted into a Keynote slide.

There are a few assumptions:

1. The code to be highlighted is Ruby code.
1. The Keynote slide background is black.
1. The appropriate command line tools to perform the highlighting are in place. 
 
**Mechanism**

Download and install the [Source Code Pro](https://github.com/adobe-fonts/source-code-pro) font.

Install the python package Pygments. On OS X use the following command:

````
easy_install Pygments
````

Create an executable script called ```highlight_code.sh``` (in some directory on your path) that contains the following:

````
#!/usr/bin/env bash
pbpaste | pygmentize -l ruby -f rtf -P style=monokai -P fontface="Source Code Pro" -P fontsize=72 | pbcopy
````

Navigate to: _Preferences > Tools > External Tools_ and add a new tool.

Setting     | Value
:------     | :----
Name        | Highlight Code
Description | Transforms the code in the clipboard as RTF suitable for pasting into a Keynote slide
Options     | Uncheck all options
Show in     | Check Main menu
Program     | /Users/alistair/dev/scripts/highlight_code.sh

You can invoke your tool using the Find Action command.
