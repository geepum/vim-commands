# VIM commands

## insert mode

- `o`		: insert below
- `i`		: before cursor
- `a`		: after cursor

## moving around
- `gg` 		: beginning of document
- `G` 		: end of document
- `0`		: beginning of the line
- `^`		: beginning of code in the line
- `$`		: end of the line
- `w`		: next word
- `b`		: previous word
- `ctrl+f`	: next page
- `ctrl+b`	: previous page
- `CTRL + d`		: go forward half display at a time
- `CTRL + u`		: go backward half display at a time
- `number + G`	: move to line number

## copy, cut and paste
- `dw`		: cut from cursor to end of word
- `d$` or `D`	: cut from cursor to end of line
- `diw`		: cut the whole word
- `dd`		: cut the whole line
- `3dd`		: cut 3 lines
- `yy`		: copy line
- `y$`		: copy from cursor to end of line
- `3yy`		: copy 3 lines
- `p`		: paste
- `gp`		: paste after the cursor
- `gP`		: paste before the cursor

## select
- `ggVG`	: select all

## replace all
- `:%s/oldWorld/newWorld/g`

## Others

- `:set mouse=a`	: enable mouse
- `?bin`		: find word bin => `N` to forward find `n` to backward find
- `H`			: high of display
- `M`			: mid of display
- `L`			: low of display
- `x`			: delete
- `X`			: backspace
- `u`			: undo
- `CTRL + r`		: redo
- `set nu`		: set numbers on left
- `set nonu`		: remove set numbers
- `v`			: select character
- `V`			: select line
