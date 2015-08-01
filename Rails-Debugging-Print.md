**Rationale**

When debugging a Rails application a useful technique is to insert print statements into the server log. To make the debugging print statement stand out in the log it's useful to display a prompt prior to the debugging output. It can sometimes be necessary to distinguish between multiple debugging print statements. We can make this common operation easier by adding a live template just for this purpose.

**Mechanism**

Navigate to: _RubyMine > Preferences > Editor > Live Templates_

![New Live Template](https://github.com/amckinnell/RubyMineTips/blob/master/images/new-live-template.png)

![Debugging Print Live Template](https://github.com/amckinnell/RubyMineTips/blob/master/images/debugging-print-live-template.png)

Click "Edit variables"

![Debugging Print Edit Template Variables](https://github.com/amckinnell/RubyMineTips/blob/master/images/debugging-print-edit-template-variables.png)

Now, when you are debugging and want to print the value of some variable:

1. copy the variable name
1. put the cursor on the line where you want to know the value of that variable
1. type `pp` and press Enter (or your expand live template key)

![Debugging Print Example](https://github.com/amckinnell/RubyMineTips/blob/master/images/debugging-print-example.png)
