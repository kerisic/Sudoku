# Sudoku #

This is a Sudoku solver as introduced in the first chapter of The Ruby Programming Language by David Flanagan and Yukihiro Matsumoto. It is a good short to medium-length program that demonstrates a number of features of Ruby.

As it is thoroughly commented, this has been uploaded for reference and ease of following along on screen as opposed to the book.

To run and solve Sudoku puzzles, use code:

```
require 'sudoku'
puts Sudoku.solve(Sudoku::Puzzle.new(ARGF.readlines))
```
