# dotfiles
A bunch of config files

In order to use bash custom settings you need to include the entry point file to your ~/.bashrc: 
. /path/to/dotfiles/bashrc

To load changes execute: 
source /path/to/dotfiles/bashrc

In order to use ssh config file its better to move ~/.ssh/config file content to /path/to/dotfiles/ssh/config and create a symbolic link: 
ln -s /path/to/dotfiles/ssh/config ~/.ssh/config
