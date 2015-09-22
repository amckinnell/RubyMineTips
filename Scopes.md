**Rationale**

A complex project has many files that you do not need to see in your day-to-day work. Define a scope that shows only those files that you use everyday.

On my current project I have excluded these files from the project folder: `.gitignore`, `.rake_tasks`, `.rubocop.yml`, `.ruby-version`, `config.ru`, `Gemfile`, `Gemfile.lock`, and `Rakefile`.

On my current project I have chosen to exclude the `app/mailers` directory as we're not using this Rails feature.

Note: you can always see all directories and files in the root folder by choosing the _Project_ scope.

**Mechanism**

_Preferences > Scopes_

Add a local scope and start excluding or including files. Note: you can also define exclusions and inclusions based on directories (by clicking the _Include Recursively_ or _Exclude Recursively_ button).

