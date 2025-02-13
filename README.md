## vimbnunny8 is a fork of markbahnman/vim-pico8-color
I didn't like the grey... and then I adjusted a lot of colours for fun.
I did run this through the color test thing so it should be all visible.
It should be compatible in the same way the original markbahnman/vim-pico8-color.
I believe I have left the original colors alone so sprite mapping still is the same.


## the old description is below, modified to help a bit

Vim color scheme inspired by the [PICO-8](https://www.lexaloffle.com/pico-8.php) fantasy console.



 ![Vim screenshot](screenshot-vim.png) 
(Font in the pic is Bolded Cousine Nerd Font Mono)
![PICO-8 screenshot](screenshot-pico8.png) 

## Installation

Requires a terminal with true color support (or GVim/MacVim).

Using [vim-plug](https://github.com/junegunn/vim-plug):

```vim
Plug 'BOTButtcheeks/vimbnunny8'
Plug 'ssteinbach/vim-pico8-syntax' " optional
```
I honestly haven't gotten a pico-8 syntax to work, as you can see with the errors in the pictures, but that should be unrelated to coloring

put the below stuff after the call plug#end(), I don't think it works above it
```vim
set termguicolors
colorscheme bnunny8.vim
```

## Related projects

This is a fork of [BordenJardine's](https://github.com/BordenJardine) color scheme [pico8-vim-colorscheme](https://github.com/BordenJardine/pico8-vim-colorscheme), but I have redone almost everything.

This color scheme works well with with:

- [ssteinbach/vim-pico8-syntax](https://github.com/ssteinbach/vim-pico8-syntax) - Syntax highlighting for PICO-8's `.p8` files
- [juanitogan/p8-programming-fonts](https://github.com/juanitogan/p8-programming-fonts) - Fonts modified for PICO-8 programming

Thanks to [Roman Zolotarev](https://www.romanzolotarev.com/) for his [PICO-8 Color Palette](https://www.romanzolotarev.com/pico-8-color-palette/), which was a useful reference when making this.

## License

[MIT](LICENSE)
