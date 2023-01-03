Setup for VIM editor
--------------------

DEPRECATED in favor https://github.com/franchiotta/my-nvim-setup

Personal configuration to setup vim in your machine.

**Installation steps**

* git clone git@github.com:franchiotta/my-vim-setup.git ~/.vim
* mkdir ~/.vim/bundle
* cd ~/.vim/bundle
* git clone git@github.com:VundleVim/Vundle.vim.git
* ln -s ~/.vim/vimrc ~/.vimrc
* Use vundle to install the plugins

**Recomendations**
As this bundle comes with different packages pre-installed such as command-t, you need to make sure your vim installation is compatible with all those dependencies. Consider to read the documentation for each installed pluging (Vundle is used as pluging manager).


**Vim pre-requisites**
- python3
- ruby

You can compile vim using the following command to be compliant with the needed requisites: 

./configure --prefix=/usr/local --enable-gui=no --without-x --disable-nls --enable-multibyte --with-tlib=ncurses --enable-python3interp --with-python-command=python3.7 --with-python3-config-dir=$(python3-config --configdir) --enable-rubyinterp --with-ruby-command=/usr/bin/ruby --with-features=huge --enable-fail-if-missing

