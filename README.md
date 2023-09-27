# dev-setup

note:
- mac user only
- make sure [homebrew](https://brew.sh/) already installed on our machine

| Command                                 | Functionality                                                                         |
| --------------------------------------- | ------------------------------------------------------------------------------------- |
| brew install nvm                        | install nvm using homebrew                                                            |
| source $(brew —prefix nvm)/nvm.sh       | to make nvm available every time when we open a new terminal                          |
| nvm ls-remote                           | show a list of available nodejs versions (add --lts flag to check nodejs lts version) |
| nvm ls                                  | show all nodejs version that already installed                                        |
| nvm install [version]                   | install specific nodejs version                                                       |
| nvm use [version]                       | switch to specific nodejs version                                                     |
| nvm alias default [version]             | make specific nodejs version as default                                               |
| nvm uninstall [version]                 | remove spesific nodejs version                                                        |
| npm install -g pnpm                     | install pnpm using npm                                                                |
| [nvm](https://github.com/nvm-sh/nvm) -v | check current nvm version                                                             |
| [node](https://nodejs.org/en) -v        | check current nodejs version                                                          |
| [pnpm](https://pnpm.io/installation) -v | check current pnpm version                                                            |
