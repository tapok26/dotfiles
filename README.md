# dotfiles
A bunch of config files

bashrc just include all of bash config files
bash/aliases contains aliases of the most frequently used commands and functions to make it reusable and dynamic
bash/env contains variable of environment and custom variables
bash/config defines configuration of prompt line
ssh/config contains ssh connections aliases and required data to make connection easier

In order to use bash custom settings you need to include the entry point file to your ~/.bashrc: 
. /path/to/dotfiles/bashrc

To load changes execute: 
source /path/to/dotfiles/bashrc

In order to use ssh config file its better to move ~/.ssh/config file content to /path/to/dotfiles/ssh/config and create a symbolic link: 
ln -s /path/to/dotfiles/ssh/config ~/.ssh/config
