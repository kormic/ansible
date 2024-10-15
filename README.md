# Boostrap a new machine for development

1. Clone this repo
2. Install ansible with your package manager of choice
3. Go inside the cloned repo and run `ansible-playbook bootstrap.yaml -K` and provide your password
4. Close your terminal and launch alacritty terminal
5. Open neovim (skip the errors)
6. Run `PackerSync` in neovim to install all the plugins
7. Exit neovim and open it again so Mason can install any plugin / language server
8. Log out and log in again for zsh
9. Start coding :)
