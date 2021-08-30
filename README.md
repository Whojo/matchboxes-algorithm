Inspired by Brillant's course on "Introduction to Neural Networks"


The matchbox algorithm aims to solve the tic-tac-toe game with a Neural Networks approach.


# Algorithm
## Construction of the graph
### Generation
### Load nodes

## Define edges' weight
### Learning process
### Load nodes and edges

## Play



# Backup for futur usage 

# Representation of boards
+---+---+---+
|   | x | o |
+---+---+---+
| x | x | o |
+---+---+---+
|   |   |   |
+---+---+---+

This board is represented this way:
" xoxxo   "

Each case is represented by one index and its label is then put in the index at this precise index
+---+---+---+
| 1 | 2 | 3 |
+---+---+---+
| 4 | 5 | 6 |
+---+---+---+
| 7 | 8 | 9 |
+---+---+---+


## Improve:
- We do not need to represent every boards. This is due to the fact that most of them are similar at 1 rotation/ symmetrie away. This reprensents a huge difference actually. The current model has 3^9 = 19 693 nodes. And we could reduce it to 304 nodes if we represent it the correct way.

Moreover, the overcost is only made in the construction of the graph. So the changement won't be that much of a pain.

- bitboard representation (is it possible on a three states as here ?)


# Experimentation

Innitial nbr of matches


# TLDR; How to use it ?
