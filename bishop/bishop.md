The Shortsighted Bishop (7 Points)
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

- You will be given the size of the board. Since the chess board is a square you will be given only one number. i.e. if you are given the number 4, it means the board is 4 x 4, etc.
- You will be given the X coordinate where the bishop is placed in the board.
- You will be given the Y coordinate where the bishop is placed in the board.



Output
-
Your Output should be formatted as follows:

- You will output a single number that represents the number of squares being attacked

Example
-

**Example 1**

**Input:**

Size of board: 8

X: 1

Y: 1

**Output:** "The shortsighted bishop attacks 7 squares"

![bishop1](https://raw.githubusercontent.com/ponchog/phpcodingchallenge2/master/bishop/board_8x8_1.png)

-

**Example 2**

**Input:**

Size of board: 8

X: 4

Y: 4

**Output:** "The shortsighted bishop attacks 13 squares"

![bishop2](https://raw.githubusercontent.com/ponchog/phpcodingchallenge2/master/bishop/board_8x8_2.png)

-
**Example 3**

**Input:**

Size of board: 4

X: 2

Y: 2

**Output:** "The shortsighted bishop attacks 5 squares"

![bishop3](https://raw.githubusercontent.com/ponchog/phpcodingchallenge2/master/bishop/board_4x4_1.png)

-
