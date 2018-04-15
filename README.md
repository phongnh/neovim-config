Neovim and terminal configuration
------

This is my Neovim editor setup, with zsh and tmux configurations.
Feel free to fork it
and submit a pull request if you found any bug.

**Warning**: Install script removes all previous configuration (zshrc, oh-my-zsh, nvim, tmux)

Installation
-----------

    $ git clone https://github.com/kristijanhusak/neovim-config.git ~/neovim-config
    $ cd ~/neovim-config
    $ chmod +x ./install.sh
    $ ./install.sh
    $ nvim
    $ :UpdateRemotePlugins

Plugins
----------------

* [junegunn/vim-plug](https://github.com/junegunn/vim-plug)
* [w0rp/ale](https://github.com/w0rp/ale)
* [nelstrom/vim-visual-star-search](https://github.com/nelstrom/vim-visual-star-search)
* [Raimondi/delimitMate](https://github.com/Raimondi/delimitMate)
* [mattn/emmet-vim](https://github.com/mattn/emmet-vim)
* [manasthakur/vim-commentor](https://github.com/manasthakur/vim-commentor)
* [tpope/vim-surround](https://github.com/tpope/vim-surround)
* [tpope/vim-repeat](https://github.com/tpope/vim-repeat)
* [tpope/vim-fugitive](https://github.com/tpope/vim-fugitive)
* [airblade/vim-gitgutter](https://github.com/airblade/vim-gitgutter)
* [scrooloose/nerdtree](https://github.com/scrooloose/nerdtree)
* [Xuyuanp/nerdtree-git-plugin](https://github.com/Xuyuanp/nerdtree-git-plugin)
* [gregsexton/MatchTag](https://github.com/gregsexton/MatchTag)
* [sheerun/vim-polyglot](https://github.com/sheerun/vim-polyglot)
* [phpactor/phpactor](https://github.com/phpactor/phpactor)
* [Shougo/deoplete.nvim](https://github.com/Shougo/deoplete.nvim)
* [Shougo/neosnippet](https://github.com/Shougo/neosnippet)
* [kristijanhusak/deoplete-phpactor](https://github.com/kristijanhusak/deoplete-phpactor)
* [dyng/ctrlsf.vim](https://github.com/dyng/ctrlsf.vim)
* [vimwiki/vimwiki](https://github.com/vimwiki/vimwiki)
* [junegunn/fzf](https://github.com/junegunn/fzf)
* [junegunn/fzf.vim](https://github.com/junegunn/fzf.vim)
* [ludovicchabant/vim-gutentags](https://github.com/ludovicchabant/vim-gutentags)
* [kristijanhusak/vim-js-file-import](https://github.com/kristijanhusak/vim-js-file-import)
* [FooSoft/vim-argwrap](https://github.com/FooSoft/vim-argwrap)
* [morhetz/gruvbox](https://github.com/morhetz/gruvbox)

Font used:
* current - [Iosevka](https://github.com/be5invis/Iosevka)
* previous (and on screenshots) - [Inconsolata for powerline](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/Inconsolata/complete/Inconsolata%20for%20Powerline%20Nerd%20Font%20Complete.otf)

License
-------

This project is licensed under MIT License (see LICENSE file for details). But
each plugin has its own license, so check each one to see what you can do.
