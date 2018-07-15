## Source: https://www.youtube.com/watch?v=Nim4_f5QUxA&t=717s

## Understanding the Argument/Noun/Verb relationship
- Editing commands generally follow the structure of:
  - [register][num/range]<verb><noun|(i|a)<text object>>
- Example #1:
  - 

## Pen to the page
- i -  Enter insert mode at cursor
- I - Enter insert mode at first non-blank character
- s - Delete character under cursor and enter insert mode
- S - Delete line and begin insert at beginning of same line
- a - Enter insert mode _after_ cursor
- A - Enter insert mode at the end of the line
- o - Enter insert mode on the next line
- O - Enter insert mode on the above line
- C - Delete from cursor to end of line and begin insert

## Basic Motion
- w - Forward to the beginning of next word
- W - Forward to the beginning of the next WORD
- b - Backward to the next beginning of a word
- B - Backward to the next beginning of a WORD
- e - Forward to the next end of word
- E - Forward to the next end of WORD
- 0 - Move to the zeroth character of the line
- $ - Move you to the last character of the line
- GG - Go to the end of the file
- gg - Go the the first line of the file

 
## Slightly less basic: fFtT
## All follow [(n)um]<verb><n()un> syntax
for
- [n]f<o> - Forward until (nth) (o) (Inclusive)
- [n]F<o> - Backward until (nth) (o) (Inclusive)
- [n]t<o> - Forward until (nth) (o) (Exclusive)
- [n]T<o> - Backward until (nth) (o) (Exclusive)

  abcdefg, abcdefg, abcdefg

## Searching 
- / - Forward
- ? - Backword
- * - Word under cursor - forward (bounded)
- g* - Word under cursor - forward (unbounded)
- # - Word under cursor - backward (bounded)
- g# - Word under cursor - backward (unbounded)
- n - Next result, forward
- N - Next result, backward

(Note here to explain what bounded/unbounded mean)

## Copy/Paste

- y - Yank. Example: yw (yank word)
- p - paste after cursor
- P - paste before cursor
- v - Visual selection

## Undoing your changes
- u - undo stuff
- Ctrl-r - redo stuff

## vim: set syn=mkd :
