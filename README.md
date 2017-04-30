# vim-acme
syntax-highlighting for the acme 6502-family assembler

## Install

### [vim-plug](https://github.com/junegunn/vim-plug) users

Put
```vim
Plug 'leissa/vim-acme'
```
into your plugged-section in your ```~/.vimrc``` and run
```vim
:PlugInstall
```

### Other Users

```bash
git clone git@github.com:leissa/vim-acme.git
ln -s vim-acme/ftdetect/acme.vim ~/.vim/ftdetect/.
ln -s vim-acme/syntax/acme.vim ~/.vim/syntax/.
```
