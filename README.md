# Dev Configurations

### `VSCode/settings.json`
#### Settings File Locations
Depending on your platform, the user settings file is located here:

- Windows `%APPDATA%\Code\User\settings.json`
- Mac `$HOME/Library/Application Support/Code/User/settings.json`
- Linux `$HOME/.config/Code/User/settings.json`
  
  
  
### `VSCode/vscode-extensions.list`
#### VSCode Extensions
On the old machine:
`code --list-extensions > vscode-extensions.list`
On the new machine:
`cat vscode-extensions.list | xargs -L 1 code --install-extension`
