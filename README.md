#Material for Vim
This theme is inspired by [Material Theme for Sublime Text 3](https://github.com/equinusocio/material-theme) by [equinusocio](https://github.com/equinusocio) and works on terminal Vim.

![vim-material](https://www.github.com/jackiehluo/vim-material/raw/master/screenshot.png)

##Installation

1. Move `material.vim` to your `.vim/colors` directory or install with [Pathogen](https://github.com/tpope/vim-pathogen) by cloning this repo to your `~/.vim/bundle` directory.

2. Install [Fira Code](https://github.com/tonsky/FiraCode), and import `material.terminal` in your Terminal preferences to add the color scheme. If you can't, you can manually change the ANSI colors in your Terminal preferences to these color codes:

    | Color               | Hex Code |
    |---------------------|----------|
    | Background          | #19242B  |
    | Text                | #C4C7D1  |
    | Black (00)          | #263238  |
    | Bright Black (08)   | #373B41  |
    | Red (01)            | #EC5F67  |
    | Bright Red (09)     | #FF516A  |
    | Green (02)          | #C3E88D  |
    | Bright Green (0A)   | #C2E985  |
    | Yellow (03)         | #FAD430  |
    | Bright Yellow (0B)  | #FFCC63  |
    | Blue (04)           | #92B6ED  |
    | Bright Blue (0C)    | #80B0FA  |
    | Magenta (05)        | #81678F  |
    | Bright Magenta (0D) | #C88FEC  |
    | Cyan (06)           | #ACD5DA  |
    | Bright Cyan (0E)    | #7DCBC4  |
    | White (07)          | #707880  |
    | Bright White (0F)   | #CDD3DE  |

3. Add the following to your `.vimrc`:

    ```vimL
    syntax enable
    set background=dark
    colorscheme material
    ```
