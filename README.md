# Dotfiles

From my Ubuntu install

### Programs covered:

 - abcde
 - ranger
 - rubygems
 - tmux
 - vim
 - xdefaults (urxvt256c)
 - zsh

### Other:

 - Misc scripts

## How to use

This repo makes use of [Stow](https://www.gnu.org/software/stow/manual/stow.html) to manage the dotfiles.

 - Clone repo

```
git clone git@github.com:DuncSmith/dotfiles.git ~/dotfiles
cd ~/dotfiles
```

 - Install using stow:

```sh
stow vim
 ```

## Dependancies

Some configurations require additional tools:

 - ctags
 - [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
 - TheSilverSurfer (ag)

