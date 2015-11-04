# Todo.vim

Simple plugin to help manage my Todos.

## Usage

...need to write this out. heres how i'm using it [currently](https://github.com/robhurring/dotvim/blob/master/vimrc)

```viml
autocmd FileType markdown nmap <buffer> <localleader>i <Plug>(todo-new)
autocmd FileType markdown nmap <buffer> <localleader>I <Plug>(todo-new-below)
autocmd FileType markdown imap <buffer> <localleader>i <Plug>(todo-new)
autocmd FileType markdown imap <buffer> <localleader>I <Plug>(todo-new-below)

autocmd FileType markdown nmap <buffer> <localleader>x <Plug>(todo-mark-as-done)
autocmd FileType markdown nmap <buffer> <localleader>X <Plug>(todo-mark-as-undone)
autocmd FileType markdown vmap <buffer> <localleader>x <Plug>(todo-mark-as-done)
autocmd FileType markdown vmap <buffer> <localleader>X <Plug>(todo-mark-as-undone)
```
