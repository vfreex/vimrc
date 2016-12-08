# Vimrc for Programmers

This is my vimrc inspired from the basic version of
[Amix's The Ultimate vimrc][1] but using [Vundle][2] as plugin manager.

## Features

- Default color schema & key mappings are not modified.
- The `vimrc` file is stored in `~/.vim`, leaving your own `~/.vimrc` intact.
- The following plugins are included by default:
  + [Vundle][2] - Vundle is short for Vim bundle and is a Vim plugin manager.
  + [YouCompleteMe][3] - YouCompleteMe is a fast, as-you-type, fuzzy-search code completion engine for Vim.
  + [YCM-Generator][4] - A script which generates a list of compiler flags from a project with an arbitrary build system.
  + [cscope-maps][5] - Just old good cscope maps for vim.
  + [NERDTree][6] - The NERD tree allows you to explore your filesystem and to open files and directories.
  + [lightline.vim][7] - A light and configurable statusline/tabline for Vim.
  + [ctrlp.vim][8] - Full path fuzzy file, buffer, mru, tag, ... finder for Vim.

## Usage

- Clone from GitHub:

``` sh
$ git clone --recursive https://github.com/vfreex/vimrc ~/.vim
```

- Enable it by sourcing `~/.vim/vimrc`:

```sh
$ vim ~/.vimrc
source ~/.vim/vimrc
```

- Edit `~/.vim/vimrc` for the list of plugins to install. Please read the document of [Vundle][2]
carefully before making any change to the file.

``` sh
$ vim ~/.vim/vimrc
```
- Install plugins

``` sh
$ vim
:VundleInstall
```
- Install YouCompleteMe

YouCompleteMe requires additional steps to install. Please follow [this guide][9].

[1]: https://github.com/amix/vimrc
[2]: https://github.com/VundleVim/Vundle.vim
[3]: https://github.com/Valloric/YouCompleteMe
[4]: https://github.com/rdnetto/YCM-Generator
[5]: https://github.com/joe-skb7/cscope-maps
[6]: https://github.com/scrooloose/nerdtree
[7]: https://github.com/itchyny/lightline.vim
[8]: https://github.com/ctrlpvim/ctrlp.vim
[9]: https://github.com/Valloric/YouCompleteMe#installation
