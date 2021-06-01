# dotfiles
Configuration files:

<ul>
  <li>
    <b><i>bashrc</i></b> imports all config files
  </li>
  <li>
    <b><i>bash/aliases</i></b> contains aliases of the most frequently used commands and functions to make it reusable and dynamic
  </li>
  <li>
    <b><i>bash/env</i></b> contains environment and custom variables
  </li>
  <li>
    <b><i>bash/config</i></b> defines prompt line configuration
  </li>
  <li>
    <b><i>ssh/config</i></b> contains ssh connection aliases and data to make connection easier
  </li>
</ul>

In order to use bash custom settings you need to include the entry point file to your <code>~/.bashrc:</code> <br/>

<code>. /path/to/dotfiles/bashrc</code>

To apply changes execute: <br/>

<code>source /path/to/dotfiles/bashrc</code> <br/>

In order to use ssh config file its better to move <code>~/.ssh/config</code> file content to <code>/path/to/dotfiles/ssh/config</code> and create a symbolic link: <br/>

<code>ln -s /path/to/dotfiles/ssh/config ~/.ssh/config</code>
