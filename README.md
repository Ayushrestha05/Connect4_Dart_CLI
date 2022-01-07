# Connect 4 Dart
Connect 4 Dart is a simple console application built using only Dart. This program has only one player and one AI.
This repository consists of two versions of this program.

- AI Built using Mini-Max Algorithm only
- AI built using Mini-Max Algorithm and optimized using Alpha-Beta Pruning

Each program consists of a Time counter that provides the user how much time was taken by an AI to decide a move in various depths.
## Using the Program
To run this program, firstly clone this repository and go to the folder where you have cloned the repository.
Go inside the repo folder and then into the `bin` folder
Go to your Terminal or Command Prompt and type:

`dart .\connect4.dart` for Connect 4 with Mini-Max algorithm only
<br/>
or,
<br/>
`dart .\connect4_w_AlphaBetaPruning.dart` for Connect 4 with Mini-Max Algorithm and optimized using Alpha-Beta Pruning

Once the program runs inside the Terminal or Command Prompt, the user can insert values from 0-6 to choose the column in which the user wishes to drop their piece. In this program, Player Pieces are denoted by `1` and AI Pieces are denoted by `2`.

The goal of this game is to connect 4 of your pieces either horizontally, vertically or diagonally.
## References

- [Building Connect 4 in Python by Keith Galli](https://www.youtube.com/watch?v=UYgyRArKDEs&list=PLFCB5Dp81iNV_inzM-R9AKkZZlePCZdtV)
- [How Board Games AI work? by Keith Galli](https://www.youtube.com/watch?v=y7AKtWGOPAE)
- [Algorithms Explained – minimax and alpha-beta pruning by Sebastian Lague](https://www.youtube.com/watch?v=l-hh51ncgDI)
- [Connect 4 by Numberphile](https://www.youtube.com/watch?v=yDWPi1pZ0Po)
