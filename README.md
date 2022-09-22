# Vim Roadmap

## This roadmap will...

- gives you the direction of learning Vim. 
- lets you know what you have learned and what to learn.

## This roadmap will not...

- teach you how each command works (learn this with `:help {command}`).

## Remember these when learning Vim

- don't use mouse and arrow keys
- if you continuously press a key more than 3 times, there must be a better way to do this

## Moving

Using `k` `j` `h` `l` instead of arrow keys.

Using `w` `W` `b` `B` `e` `E` `0` `$` `^` `%`instead of pressing `h` `l` repeatedly.

Using `{count}k` `{count}j` instead of pressing `k` `j` repeatedly (remember to `set rnu`).

Using `CTRL-D` `CTRL-U` `gg` `G` to move multiple lines.

Using `f{char}` `F{char}` `t{char}` `T{char}` `;` `,` instead of pressing `w` `W` `b` `B` `e` `E` repeatedly.

## Quiting

Using `:wq` to save file and quit Vim, `:q!` to quit Vim.

Using `ZZ` instead of `:wq`, `ZQ` instead of `:q!`.

Using `:!{command}` `CTRL-Z` `fg` to execute external command instead of quitting Vim.

## Inserting

Using `i` `I` `a` `A` `o` `O` to enter insert mode.

Using `i_CTRL-P` `i_CTRL-N` `i_CTRL-L` `i_CTRL-A` `i_CTRL-@` instead of retyping words repeatedly (`i_{keys}` means pressing the keys in insert mode).

Using `CTRL-V` and `I` `A` to insert multiple line once.

## Undoing & Redoing

Using `u` `CTRL-R` to undo and redo.

Using `U` to undo all latest changes on one line.

## Editing

Operators: `d` `c` `y` `=` `>` `<`

Text Objects: `w` `iw` `aw` ...

### Examples

`cw` change to the end of a word

`ci(` change inner `()` block

`dap` delete a paragraph

(Use `:help motion.txt` to learn more.)

## Searching

Using `/` `?` `n` `N` to search words.

Using `*` `#` to search the word under the cursor.

## General

Using `.` instead of retyping command repeatedly.
