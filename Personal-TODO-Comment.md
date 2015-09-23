**Rationale**

While working on a particular feature it can be useful to leave TODO comments for yourself in the source code.

RubyMine has features that will help you by allowing you to see all of your personal TODOs and warning you when you are about to commit a personal TODO to your source code repository.

I prefer to add my initials and a creation date to each personal TODO. The initials allow the rest of the team to track me down. The creation date lets me know if an unresolved TODO is fresh or ancient.

I use personal TODO comments to keep track my notes and comments during a programming episode or for a feature branch. Rarely do I intend for personal TODO comments to live for a long time in the codebase.

**Mechanism**

_Preferences > Editor > TODO_

Patterns

| Configuration   | Value            |
| :-------------- | :--------------- |
| Icon:           | _your choice_    |
| Case Sensitive: | Yes              | 
| Pattern:        | \bARM\b.*        |

Filters

| Configuration   | Value            |
| :-------------- | :--------------- |
| Name:           | Alistair's TODOs |  
| Pattern:        | \bARM\b.*        |
