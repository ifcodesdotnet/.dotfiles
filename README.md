Everything in Linux is a file. This repository contains all of the files I use on a daily basis when running Debian. 

## Installation
To use my configuratons and scripts clone my .dotfiles repository and run the bootstrap script:
```sh
git clone https://github.com/ifcodesdotnet/.dotfiles.git ~/.dotfiles
~/.dotfiles/scripts/bootstrap/bootstrap
```
## Bootstrapping System
The bootstrap script heavily relies on `jq` to parse a [json configuration file](https://raw.githubusercontent.com/ifcodesdotnet/.dotfiles/master/scripts/bootstrap/bootstrap.json) that specifies the following parameters:
 - apt packages to install
 - folders and files to symlink using stow
 - scripts to execute to install additional software

## Useful scripts
 - [Bootstrap System](https://raw.githubusercontent.com/ifcodesdotnet/.dotfiles/master/scripts/bootstrap/bootstrap)
 - [Install Visual Studio Code](https://raw.githubusercontent.com/ifcodesdotnet/.dotfiles/master/scripts/install-software/install-vscode)
 - [Install Vimix Icons](https://raw.githubusercontent.com/ifcodesdotnet/.dotfiles/master/scripts/install-icons/install-vimix-icon)
 - [Install Vimix Theme](https://raw.githubusercontent.com/ifcodesdotnet/.dotfiles/master/scripts/install-themes/install-vimix-theme)
