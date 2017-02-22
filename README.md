# vim-denite-gists

`vim-denite-gists` is a source for [denite.nvim](https://github.com/Shougo/denite.nvim).

This plugin can open gist page with Denite interface.

## depends

This plugin depends on:

* [denite.nvim](https://github.com/Shougo/denite.nvim)
* [open-browser.vim](https://github.com/tyru/open-browser)

## install

For [dein.vim](https://github.com/Shougo/dein.vim)

   ```
   call dein#add('Shougo/denite-nvim')
   call dein#add('tyru/open-browser.vim')
   call dein#add('pocari/vim-denite-gists')
   ```

## usage

`:Denite gists`
or
`:Denite gists:[github user name]`

