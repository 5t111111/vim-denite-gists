# vim-denite-gists

`vim-denite-gists` is a source for [denite.nvim](https://github.com/Shougo/denite.nvim).

This plugin can open gist page with Denite interface.

![vim-denite-gists-screenshot](https://cloud.githubusercontent.com/assets/1496543/23336842/1fbe0a0a-fc1f-11e6-9d32-10ad6c4797c6.gif)

## depends

This plugin depends on:

* [denite.nvim](https://github.com/Shougo/denite.nvim)
* [vim-denite-kind-open-browser](https://github.com/pocari/vim-denite-kind-open-browser)
* [open-browser.vim](https://github.com/tyru/open-browser)

## install

For [dein.vim](https://github.com/Shougo/dein.vim)

   ```vim
   call dein#add('Shougo/denite.nvim')
   call dein#add('tyru/open-browser.vim')
   call dein#add('pocari/vim-denite-kind-open-browser')
   call dein#add('pocari/vim-denite-gists')
   ```

## usage

`:Denite gists`
or
`:Denite gists:[github user name]`

Default Action is `open` with `open-browser.vim`.

You can choose multiple candidates, and you can open them by multiple browser tab.

## github user detection

1. argument on startup

    Denite gists:pocari

2. from your .gitconfig
   
    if following section exists in your gitconfig, it is used.
    
    e.g) ~/.gitconfig
    ```
    [github]
    	user = pocari
    ```

3. no argument and no github section in gitconfig
    
    A prompt for entering the user name is displayed at startup.

