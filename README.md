dotfiles
========

Simple .dotfiles configuration with [homeshick](https://github.com/andsens/homeshick/) as manager.

For Vim: [http://vim.spf13.com/](http://vim.spf13.com/) used as main configuration.

TODO: install/update scripts for tools (+ bootstrap script to new machines, tested in clean VM).

Install:

```bash
## install homeshick
git clone git://github.com/andsens/homeshick.git $HOME/.homesick/repos/homeshick

## add homeshick to shell
printf '"\nsource “$HOME/.homesick/repos/homeshick/homeshick.sh"' >> $HOME/.bashrc
## or for zsh:
# printf '"\nsource “$HOME/.homesick/repos/homeshick/homeshick.sh"' >> $HOME/.zshrc

## add homeshick shell completion
printf '\nsource "$HOME/.homesick/repos/homeshick/completions/homeshick-completion.bash"' >> $HOME/.bashrc
## or for zsh:
# printf '\nsource "$HOME/.homesick/repos/homeshick/completions/homeshick-completion.bash"' >> $HOME/.zshrc
## TODO: make completion works with zsh
```
