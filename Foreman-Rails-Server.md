**Rationale**

If you use a Foreman configuration to launch Rails server you can configure RubyMine to do the same. 

**Mechanism**

Use the Run > Edit Configurations and add a new configuration based on the Gem Command default.

| Configuration    | Value                           |
| :--------------- | :------------------------------ |
| Name:            | Foreman                         |
| Gem name:        | foreman                         |
| Executable name: | foreman                         |
| Arguments:       | start --procfile=./Procfile.all |

Reference: https://www.jetbrains.com/ruby/help/run-debug-configuration-gem-command.html