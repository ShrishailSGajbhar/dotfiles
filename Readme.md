# Dotfiles for my current Ubuntu 22.04 Desktop

* `bin` folder contains two custom shell scripts namely `dn` and `dg` present in `/usr/bin/` folder.
  * `dn`: New developer note
  * `dg`: Group developer notes by tag

* `nvim`: contains files for my LazyVim setup. Location: `~/.config/` folder.
* `.tmux.conf`: Tmux config file
* `.zshrc`: zshrc file

## Few custom commands and keymaps to remember

* Zshrc Alias commands
  * odn -> Open the developer note folder
  * rdn -> Review the developer notes

* Lazyvim Keymaps
  * <leader>tn -> New developer note from template
  * <leader>tf -> Format title of the developer note
  * <leader>ok -> Keep the file and move
  * <leader>odd-> Delete the file

## Few useful LazyVim default commands

* `gcc`: command to toggle the comment
* `z=`: To get the correct word suggestion for an incorrect word. Note: the word must be under the vim cursor.
