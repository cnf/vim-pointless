# Pointless Color Scheme for ViM

Hey, what's in a name...

## Status

It isn't complete yet, but it should be functional.

## 256!

This is a color scheme that requires 256 colors.

In your terminal, type:

    $ tput colors

If the output is not 256, your terminal is not configured for 256 colors.

in vim enter command mode, and set:

    :set t_Co

If the output is not 256, vim is not configured for 256 colors.

## Installation

### Pathogen

The preferred method of installation is [Pathogen][vim-pathogen].

[vim-pathogen]:https://github.com/tpope/vim-pathogen 

### Legacy

Alternatively, copy ```pointless.vim``` to ```~/.vim/colors/```

## Screenshot

### C
![C](https://github.com/cnf/vim-pointless/raw/master/screenshots/pointless-c.png)

### Python
![Python](https://github.com/cnf/vim-pointless/raw/master/screenshots/pointless-python.png)

### Ruby
![Ruby](https://github.com/cnf/vim-pointless/raw/master/screenshots/pointless-ruby.png)
