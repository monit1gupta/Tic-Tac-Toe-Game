## README.md

**Tic Tac Toe Game in Python**

This is a simple implementation of the classic Tic Tac Toe game in Python.

**Features:**

* Two-player game with 'X' and 'O'
* Displays the current board state
* Checks for win conditions
* Tracks turns and announces the winner

**To play:**

1. Run the `tic_tac_toe.py` script.
2. Follow the on-screen instructions to enter your moves.
3. The game will automatically check for wins and draws.

**Code Structure:**

* **board.py:** Contains the main logic of the game.
* **boardPrinter.py:** Prints the current board state.
* **checkIfWon.py:** Checks for win conditions.

**Dependencies:**

* Python 3
* No additional libraries required

**Usage:**

```
python tic_tac_toe.py
```

**Example Output:**

```
 X   |  O   |  
____|______|____
     |  X   |  
____|______|____
 O   |     |  X
    |      |    

Turn for X
Enter a position: TL

 X   |  O   |  
____|______|____
 X   |  X   |  
____|______|____
 O   |     |  X
    |      |    

Turn for O
Enter a position: MR

 X   |  O   |  
____|______|____
 X   |  X   |  O
____|______|____
 O   |     |  X
    |      |    

O has won!
Thanks for playing :)
```

**Further Improvements:**

* Implement AI to play against the computer.
* Add difficulty levels.
* Enhance the user interface.

**Enjoy playing Tic Tac Toe!**
