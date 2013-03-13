Kolor - Vim Theme
=================

Colorful Vim color scheme with 256 color terminal support.

Designed to have high text readability and optimal visibility of every element, and to be eye comfortable as well.

![][screenshot]

## Installation

Just copy `kolor.vim` to `~/.vim/colors` (on Windows `<your-vim-dir>\vimfiles\colors`). Or for global accessibility, `/usr/share/vim/vimfiles/colors`.

Then add the line `colorscheme kolor` in your vimrc file, and restart Vim.

If you use Pathogen or Vundle, the directory structure is compatible.

For Arch Linux users, there is also a [PKGBUILD][pkgbuild] available in the AUR, created by [graysky][graysky2].

## Options

You can put the following lines before `colorscheme kolor` in your vimrc.

    let g:kolor_italic=1                    " Enable italic. Default: 1
    let g:kolor_bold=1                      " Enable bold. Default: 1
    let g:kolor_underlined=0                " Enable underline for 'Underlined'. Default: 0
    let g:kolor_alternative_matchparen=0    " Gray 'MatchParen' color. Default: 0

## Donations

If you want to make a donation, rather, consider to help the Uganda children on Vim's website.

This color scheme is dedicated to them.

## Self-promotion

If you like `kolor.vim` follow the GitHub [repository][repository], and don't forget to vote for it on Vim.org! ([vimscript #4339][script]).

[script]: http://www.vim.org/scripts/script.php?script_id=4339
[repository]: https://github.com/zeis/vim-kolor
[screenshot]: https://lh5.googleusercontent.com/-z7CGCLXhTNQ/UM-4XPy52fI/AAAAAAAAAHo/iCFTSqaoapA/s852/kolor-screenshot.jpg
[pkgbuild]: https://aur.archlinux.org/packages/vim-kolor/
[graysky2]: https://github.com/graysky2

## Support & Development

Feel free to contribute, develop ports or report any problems. I'll be happy to give my support.

