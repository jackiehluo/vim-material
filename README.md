#Material for Vim
This theme is inspired by [Material Theme for Sublime Text 3](https://github.com/equinusocio/material-theme) by [equinusocio](https://github.com/equinusocio) and works on terminal Vim.

![vim-material](https://www.github.com/jackiehluo/vim-material/raw/master/screenshot.png)

##Installation

1. Move `material.vim` to your `.vim/colors` directory or install with Pathogen by cloning this repo to your `~/.vim/bundle` directory.
2. Change the ANSI colors in your Terminal preferences to the color codes in `colors.txt`.
3. Add the following to your `.vimrc`:
    ```
    syntax enable
    set background=dark
    colorscheme material
    ```