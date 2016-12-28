# vimfiles

![screenshot](https://raw.githubusercontent.com/marceldiass/vimfiles/master/screenshot.png)

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> My `~/.vim` and `~/.vimrc` configurations.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contribute](#contribute)
- [Plugins list](#plugins_list)
- [Used In](#used_in)
- [License](#license)

## Installation

```sh
bash -c "$(wget -O - https://raw.githubusercontent.com/marceldiass/vimfiles/master/install.sh)"
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
- 'marceldiass/onedark.vim'

## Used in

- [marceldiass/dotfiles](http://github.com/marceldiass/dotfiles)

## License

[MIT © Marcel Dias](https://github.com/marceldiass/vimfiles/blob/master/LICENSE)
