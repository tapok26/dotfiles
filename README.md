# dotfiles
A bunch of config files

<b><i>bashrc</i></b> just include all of bash config files <br/>
<b><i>bash/aliases</i></b> contains aliases of the most frequently used commands and functions to make it reusable and dynamic <br/>
<b><i>bash/env</i></b> contains variable of environment and custom variables <br/>
<b><i>bash/config</i></b> defines configuration of prompt line <br/>
<b><i>ssh/config</i></b> contains ssh connections aliases and required data to make connection easier <br/>

In order to use bash custom settings you need to include the entry point file to your ~/.bashrc: <br/>
<code>. /path/to/dotfiles/bashrc</code>

To load changes execute: <br/>
<code>source /path/to/dotfiles/bashrc</code> <br/>

In order to use ssh config file its better to move ~/.ssh/config file content to /path/to/dotfiles/ssh/config and create a symbolic link: <br/>
<code>ln -s /path/to/dotfiles/ssh/config ~/.ssh/config</code>
