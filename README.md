# vim-kolor

Colorful Vim color scheme with 256 color terminal support.

Designed for high readability and optimal visibility of every element, and to be eye comfortable as well.

![](https://lh5.googleusercontent.com/-z7CGCLXhTNQ/UM-4XPy52fI/AAAAAAAAAHo/iCFTSqaoapA/s852/kolor-screenshot.jpg)

## Installation

You can install it via Vundle or Pathogen, alternatively, just copy `kolor.vim` to `~/.vim/colors` (on Windows `<your-vim-dir>\vimfiles\colors`). Or for global accessibility, `/usr/share/vim/vimfiles/colors`.

Then add the line `colorscheme kolor` in your _vimrc_ file, and restart Vim.

For Arch Linux users, there is also a [PKGBUILD](https://aur.archlinux.org/packages/vim-kolor/) available in the AUR, created by [graysky](https://github.com/graysky2).

## Options

Options must be set before the line `colorscheme kolor`.

```
let g:kolor_italic=1                    " Enable italic. Default: 1
let g:kolor_bold=1                      " Enable bold. Default: 1
let g:kolor_underlined=0                " Enable underline. Default: 0
let g:kolor_alternative_matchparen=0    " Gray 'MatchParen' color. Default: 0
```

## Donations

This color scheme is dedicated to the the Ugandan children (see Vim's website).

How about donating to [them](http://iccf-holland.org/click5.html)?. And, if you donate, please, let me know.

## Self-promotion

If you like _vim-kolor_ don't forget to vote for it! (Vimscript [#4339](http://www.vim.org/scripts/script.php?script_id=4339)).

## Support & Development

Feel free to contribute, develop ports or report any problems. I'll be happy to give my support.
