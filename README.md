# Tick Tack Toe

- Hobby project for practising Pascal syntax

## Synopsis

This rendition of Blackjack was a small hobby project to practise programming in Pascal. Initial commit was written on a 1989 Macintosh SE using a dated version of TurboPascal. Done as a challenge due to lack of basic functions; no conversion of String to Integer, Exponent etc. functions were possible, so custom ones were written instead.

## Sample Output
````
<output ommitted>

   1 2 3 
1  _ x _ 
2  _ x _ 
3  _ _ o 
 
   > It's o's turn
   > [1] -> Enter Selection
   > [2] -> New Game
   > [0] -> Quit

  >> [?] ->: 1
  >> Enter column number: 3
  >> Enter row number: 1
   > No winner yet
   > Drawing the game board: 

   1 2 3 
1  _ x o 
2  _ x _ 
3  _ _ o 
 
   > It's x's turn
   > [1] -> Enter Selection
   > [2] -> New Game
   > [0] -> Quit

  >> [?] ->: 1
  >> Enter column number: 2
  >> Enter row number: 3
   > We have a winner: x
   > Drawing the game board: 

   1 2 3 
1  _ x o 
2  _ x _ 
3  _ x o 

=============================================================

   > Starting a new game
````

## Usage

Compile `TickTackToe.pas` using a Pascal compiler. Precompiled source (OS X) in `./bin/`.

## Copyright Notice

Copyright &copy; Alex Cummaudo 2014. All rights reserved.