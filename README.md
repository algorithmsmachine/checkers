# Checkers

Checkers is a board game that involves two players (one takes the dark pieces, the other takes the light pieces). The
dark player always has the first turn. The players take turns moving pieces forward and diagonally one spot and can "
capture" opponents by jumping over them diagonally. If a player captures another player's piece and lands in a spot
where another capturing move is available, this capturing move must be performed. If a player's piece makes it to the
opposing player's side of the board, this piece is "kinged" and is allowed to move backwards diagonally one spot.

### Design Approach:

Object Oriented. Each of the game pieces is an object and has properties relevant to
its current state in the game. At times, this made creating the program easier and at others it made it more
frusturating. The program was designed to utilize many Piece object methods and functions that either alter the data
model or the visual UI board that appears in the browser. Unfortunately, my approach was scattered and unorganized. I
frequently had to redesign functions and methods in order to keep progressing, only to find that these redesigns
wouldn't work with later features. In the future, I plan to psuedocode and wireframe more effectively.

## Code

The code supports all the features of checkers including kingship and double/triple/quadruple jumping. The Board object
controls the board and therefore the game. The pieces and tiles instances are used in the game for checking whether a
piece can be moved, moving a piece, deleting a piece, checking whether tile is in range, and much more. The script is
fully commented and original.

If you find any bugs, please make a Pull Request or an Issue.
