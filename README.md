# vimfiles

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> vimfiles is a `~/.vim` and `~/.vimrc` configurations.

This repository is intended to keep my `~/.vim` and `~/.vimrc` files versioned. It configures a few [plugins](#plugins-list) and the result looks like the screenshot below - using iterm.

![screenshot](https://raw.githubusercontent.com/marceldiass/vimfiles/master/screenshot.png)

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Contribute](#contribute)
- [Plugins list](#plugins_list)
- [Used In](#used_in)
- [License](#license)

## Install

```sh
bash -c "$(wget -O - https://raw.githubusercontent.com/marcel-dias/vimfiles/master/install.sh)"
```

The install script download this git repository, create two symbolic links `vim.symlink > ~/.vim` and `vimrc.symlink > ~/.vimrc` and install vim plugins using [Vundle](https://github.com/VundleVim/Vundle.vim)


## Usage

You can add plugins in the `vimrc.symlink` file and run he command below to install them.

```sh
vim +PluginInstall +qall
```

## Contribute

PRs accepted.

## Plugins list

- 'tpope/vim-sensible'
- 'rstacruz/vim-opinion'
- 'vim-scripts/closetag.vim'
- 'scrooloose/nerdtree'
- 'honza/dockerfile.vim'
- 'vim-airline/vim-airline'

## Used in

- [marcel-dias/dotfiles](http://github.com/marcel-dias/dotfiles)

## License

[MIT © Marcel Dias](https://github.com/marcel-dias/vimfiles/blob/master/LICENSE)
