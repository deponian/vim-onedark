### Description

This is faster version of [onedark.vim](https://github.com/joshdick/onedark.vim). I've replaced all complicated checks and function calls with simple list of `execute highlight group-name colors`. Original onedark is sourced about 40 ms on my old laptop. This version needs only 7 ms. Of course, I had to sacrifice something. My version doesn't have 16 color terminals support, italics is always on and you can't override colors settings from your `vimrc`.

### Configuraion

There is only one option. Use it if you don't want transparent background.
```viml
let g:onedark_transparent = 0
```

### Acknowledgements
Thanks to authors of original [onedark.vim](https://github.com/joshdick/onedark.vim) theme.
