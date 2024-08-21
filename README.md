
# Tic-Tac-Toe Game in Java

This is a simple console-based Tic-Tac-Toe game implemented in Java. The game allows two players to take turns and compete against each other in a 3x3 grid. The first player to align three of their symbols (either 'X' or 'O') horizontally, vertically, or diagonally wins the game.

### Features:
- **Two-player mode**: Players X and O take turns to play.
- **Input validation**: Prevents players from making invalid moves by choosing occupied cells.
- **Win detection**: Checks for winning conditions after each move, including rows, columns, and diagonals.
- **User-friendly interface**: Simple text-based board display for ease of play.

### How to Run:
1. Clone the repository.
2. Compile and run the `Tik_Tack` class.
3. Players will be prompted to enter their moves by specifying the row and column numbers.

### Example Gameplay:

**Example 1: Basic Moves**
```
Player X enter: 1 1

   |   |  
---+---+---
   | X |  
---+---+---
   |   |  

Player O enter: 0 0

 O |   |  
---+---+---
   | X |  
---+---+---
   |   |  

Player X enter: 2 2

 O |   |  
---+---+---
   | X |  
---+---+---
   |   | X

Player O enter: 0 1

 O | O |  
---+---+---
   | X |  
---+---+---
   |   | X
```

**Example 2: Winning Scenario (Horizontal)**
```
Player X enter: 0 0

 X |   |  
---+---+---
   |   |  
---+---+---
   |   |  

Player O enter: 1 1

 X |   |  
---+---+---
   | O |  
---+---+---
   |   |  

Player X enter: 0 1

 X | X |  
---+---+---
   | O |  
---+---+---
   |   |  

Player O enter: 2 2

 X | X |  
---+---+---
   | O |  
---+---+---
   |   | O

Player X enter: 0 2

 X | X | X 
---+---+---
   | O |  
---+---+---
   |   | O

Player X has won!
```

**Example 3: Winning Scenario (Diagonal)**
```
Player X enter: 0 0

 X |   |  
---+---+---
   |   |  
---+---+---
   |   |  

Player O enter: 0 1

 X | O |  
---+---+---
   |   |  
---+---+---
   |   |  

Player X enter: 1 1

 X | O |  
---+---+---
   | X |  
---+---+---
   |   |  

Player O enter: 2 1

 X | O |  
---+---+---
   | X |  
---+---+---
   | O |  

Player X enter: 2 2

 X | O |  
---+---+---
   | X |  
---+---+---
   | O | X

Player X has won!
```

### Additional Notes:
- The game continues until a player wins or the board is full.
- After each move, the board is updated and displayed to provide a visual representation of the game state.
- This implementation is an excellent starting point for anyone looking to learn basic game development in Java.

Enjoy the game!
