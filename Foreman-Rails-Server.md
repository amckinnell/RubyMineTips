**Rationale**

If you use a Foreman configuration to launch Rails server you can configure RubyMine to do the same. 

**Mechanism**

Use the _Run > Edit Configurations_ and add a new configuration based on the Gem Command default.

| Configuration    | Value                           |
| :--------------- | :------------------------------ |
| Name:            | Local Server                    |
| Gem name:        | foreman                         |
| Executable name: | foreman                         |
| Arguments:       | start --procfile=./Procfile.all |

Reference: https://www.jetbrains.com/ruby/help/run-debug-configuration-gem-command.html