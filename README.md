
vim-dokuwiki 
============

A VIM syntax file for DokuWiki



Installation
------------

It is recommended to manage your plugins with Vundle or Bundle plugins.

If you want to install vim-dokuwiki manually, just do following two steps:

1) copy 'syntax/dokuwiki.vim' in your '~/.vim/syntax/'
2) enable by issuing ':set ft=dokuwiki'



Usage
-----

vim-dokuwiki comes with mappings to make your life easier.

### mappings for headings

`<Leader><Leader>h1`: insert level 1 heading (insert mode)

`<Leader><Leader>h2`: insert level 2 heading (insert mode)

`<Leader><Leader>h3`: insert level 3 heading (insert mode)

`<Leader><Leader>h4`: insert level 4 heading (insert mode)

`<Leader><Leader>h5`: insert level 5 heading (insert mode)


### mappings for lists

`<Leader><Leader>ul`: insert unordered list (insert & normal & visual mode)

`<Leader><Leader>ol`: insert ordered list (insert & normal & visual mode)


### mappings for blocks

`<Leader><Leader>cb`: insert code block (insert mode)

`<Leader><Leader>fb`: insert file block (insert mode)

`<Leader><Leader>hb`: insert html block (insert mode)

`<Leader><Leader>pb`: insert php block (insert mode)

`<Leader><Leader>nb`: insert nowiki block (insert mode)



