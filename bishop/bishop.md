The Shortsighted Bishop (6 Points)
=

The challenge
-
This is the story of a shortsighted Bishop, this poor bishop just couldn’t see beyond his nose! The problem is that he doesn’t know how many squares he is attacking from his current position. And for a bishop, well, that’s pretty bad. So he needs you to help him find out how many squares he is attacking from his current position.

Specifications
-
- Your solution should work for any chess board size.
- A chess board is always a square.
- Bishops can only move diagonally.
- The bishop can be placed on any square of the board (black or white).
- Find the number of squares the bishop is attacking without including his own square.


Input
-

- You will be given the size of the board. Since the chess board is a square you will be given only one number. i.e. if the board size is 4, it means the board is 4 x 4, if the board size is 8, it means the board is actually 8 x 8, etc.
- You will be given the X coordinate where the bishop is placed in the board.
- You will be given the Y coordinate where the bishop is placed in the board.

Output
-
You will output a single number that represents the number of squares being attacked.

"The shortsighted bishop attacks N squares"

Example
-

**Example 1**

**Input:**

Size of board: 8

X: 1

Y: 1

**Output:** "The shortsighted bishop attacks 7 squares"

![Alt text](https://github.com/ponchog/phpcodingchallenge2/blob/master/bishop/board_8x8_2.png)

-

**Example 2**

**Input:**

Size of board: 8

X: 4

Y: 4

**Output:** "The shortsighted bishop attacks 13 squares"

-
**Example 3**

**Input:**

Size of board: 4

X: 2

Y: 2

**Output:** "The shortsighted bishop attacks 5 squares"

-
