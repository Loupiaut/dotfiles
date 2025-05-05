# My dotfiles

This directory contains the dotfiles for my system
From https://www.youtube.com/watch?v=y6XCebnB9gs&t=112s

## Requirements

Ensure you have the following installed on your system

### Git

```
apt install git
```

### Stow

```
apt install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/Loupiaut/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
