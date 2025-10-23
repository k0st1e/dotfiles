# My dotfiles

This directory has all the dotfiles for my penguin laptop. 

## Requirements

Ensure the following!

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow
```

## Installation

Get the dotfiles repo in the $HOME directory with git.

```
$ git clone git@github.com/k0st1e/dotfiles.git
$ cd dotfiles
```

Then use GNU Stow in order to create the symlinks.

```
$ stow .
```
