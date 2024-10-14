# Boostrap a new machine for development

Prerequisites: SSH should be set up first

1. Clone this repo
2. Install ansible with your package manager of choice
3. Go inside the cloned repo and run `ansible-playbook bootstrap.yaml -K` and provide your password
4. Close your terminal and launch alacritty terminal
5. Open neovim
6. Source `packer.lua`
7. Run `PackerSync` in neovim to install all the plugins
8. Exit neovim and open it again so Mason can install any plugin / language server
9. Log out and log in again for zsh
10. Start coding :)

TODO:
1. Use ansible vault to store my SSH keys
