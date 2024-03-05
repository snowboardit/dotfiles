# dotfiles

My personal dotfiles, configurations, and applications.

## Installation

[**bin/zsh**](./bin/zsh): Installs `zsh` and makes it the default shell.

[**bin/apps**](./bin/apps): Installs applications from `apps.txt` using `apt` and any other applications from other sources.

[**bin/install**](./bin/install): Copies `.*` from the root of the repo into `$HOME`, then runs `source` against the shell config files (e.g. `.zshrc`, `.aliases`).
