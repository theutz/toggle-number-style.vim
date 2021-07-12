# toggle-number-style.vim

Switch between absolute and relative number styles

## Usage

This is a very simple plugin that simply allows you to switch between relative
and non-relative number mode in your VIM gutter.

## Mappings

This plugin exposes a single `<Plug>` mapping that can be remapped to any key
you like.

Example:

```
  let mapleader="\<Space>"
  nmap <Leader>tn <Plug>(toggle-number-style)
```
