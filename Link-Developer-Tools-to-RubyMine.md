**Rationale**

Tweak your developer tools so that links open in RubyMine. In our example we show the configuration for opening links in Better Errors and Rails Footnotes in RubyMine.

**Mechanism**

Use iTerm2 to enable Command+Click to open filename in Rubymine

_Preferences > Profiles > Advanced_

Semantic History

| Setting        | Value                              |
| -------------- | ---------------------------------- |
| Run command... | /usr/local/bin/mine --line \2 "\1" |
| Open URL...    | x-mine://open?file=\1&line=\2      |