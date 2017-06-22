# vim-kolor

Colorful Vim color scheme with 256 color terminal support.

Designed for optimal visibility and comfort.

![](https://lh5.googleusercontent.com/-z7CGCLXhTNQ/UM-4XPy52fI/AAAAAAAAAHo/iCFTSqaoapA/s852/kolor-screenshot.jpg)

## Installation

You can install it via Vundle or Pathogen, alternatively, just copy `kolor.vim` to `~/.vim/colors` (on Windows `<your-vim-dir>\vimfiles\colors`). Or for global accessibility, `/usr/share/vim/vimfiles/colors`.

Then add the line `colorscheme kolor` in your _vimrc_ file, and restart Vim.

For Arch Linux users, there is also a [PKGBUILD](https://aur.archlinux.org/packages/vim-kolor/) available in the AUR, created by [graysky](https://github.com/graysky2).

## Options

Options must be set before the line `colorscheme kolor`.

```
" Enable italic. Default: 1
let g:kolor_italic=1

" Enable bold. Default: 1
let g:kolor_bold=1

" Enable underline. Default: 0
let g:kolor_underlined=0

" Gray 'MatchParen' color. Default: 0
let g:kolor_alternative_matchparen=0

" White foreground 'MatchParen' color that might work better with some terminals. Default: 0
let g:kolor_inverted_matchparen=0
```

## Donations

This color scheme is dedicated to the the Ugandan children (How about donating to them? See Vim's website).

## Self-promotion

If you like _vim-kolor_ don't forget to rate it! (Vimscript [#4339](http://www.vim.org/scripts/script.php?script_id=4339)).
