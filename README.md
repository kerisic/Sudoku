#Sudoku#

This is a Sudoku solver as introduced in the first chapter of The Ruby Programming Language by David Flanagan and Yukihiro Matsumoto.

To run and solve Sudoku puzzles, use code:

```
require 'sudoku'
puts Sudoku.solve(Sudoku::Puzzle.new(ARGF.readlines))
```
