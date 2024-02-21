# plover-vim-tutor

- Help files + tutor for learning plover-vim
- for proof of speed, see speedrun video [here](https://www.youtube.com/watch?v=8-oDPhmpN9g)

# Installation

## vim-plug

```vim
Plug 'Josiah-tan/plover-vim-tutor'
```

## layout:

for general information:
```vim
:help plover-vim-tutor
```

for plover-vim-tutor exercises:

```vim
:help plover-vim-tutorial
```

for cheatsheet:

```vim
:help plover-vim-cheatsheet
```


# Developers

to contribute and test your own version feel free to clone this repository and try the following below!

```vim
if isdirectory(expand("~/plover-vim-tutor/"))
	Plug '~/plover-vim-tutor/'
else
	Plug 'Josiah-tan/plover-vim-tutor'
endif
```

feel free to chuck pull requests for grammatical errors, numbering issues etc.
