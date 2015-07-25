#Material for Vim
This theme is inspired by [Material Theme](https://github.com/equinusocio/material-theme) by [equinusocio](https://github.com/equinusocio) and works on terminal Vim.

![python](https://www.github.com/jackiehluo/vim-material/raw/master/screenshot.png)

##Installation

1. Move `material.vim` to your `.vim/colors` directory or install with [Pathogen](https://github.com/tpope/vim-pathogen) by cloning this repo to your `~/.vim/bundle` directory.

2. Import `material.terminal` in your Terminal preferences to add the color scheme.

3. Add the following to your `.vimrc`:

    ```vimL
    syntax enable
    set background=dark
    colorscheme material
    ```

If you can't import the Terminal theme, you can manually change the ANSI colors in your Terminal preferences to these color codes:

| Color               | Hex Code |
|---------------------|----------|
| Background          | #19242B  |
| Text                | #C4C7D1  |
| Black (00)          | #263238  |
| Bright Black (08)   | #373B41  |
| Red (01)            | #F25570  |
| Bright Red (09)     | #F3765D  |
| Green (02)          | #84B884  |
| Bright Green (0A)   | #C2E985  |
| Yellow (03)         | #FAD430  |
| Bright Yellow (0B)  | #FFCC63  |
| Blue (04)           | #92B6ED  |
| Bright Blue (0C)    | #80B0FA  |
| Magenta (05)        | #81678F  |
| Bright Magenta (0D) | #C88FEC  |
| Cyan (06)           | #33474F  |
| Bright Cyan (0E)    | #5F8291  |
| White (07)          | #707880  |
| Bright White (0F)   | #C4C7D1  |