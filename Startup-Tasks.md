**Rationale**

I want to run a [Zeus Server](https://github.com/burke/zeus) to speed up my development. I'd love it if I could get RubyMine to start a Zeus Server for me.

**Mechanism**

RubyMine supports [Startup Tasks](https://www.jetbrains.com/ruby/help/startup-tasks.html) for exactly this purpose.

Navigate to: _Preferences > Tools > Startup Tasks_

Click the `+` on the bottom left corner

Select `Start Zeus Server: <env>`

Note: you may want to disable the _Activate tool window_ setting (so that _Run_ window does not open on startup).
