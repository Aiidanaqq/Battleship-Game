RULES OF THE GAME:
1. Purpose of the game: Sink all ships on the playing field.
2. Playing field: The field is a 7x7 square. The ships are placed randomly and occupy several cells.
3. Ships:
   • There are three ships of different lengths: length 3, length 2 (two ships of this length) and four ships of 1 tile length.
   • Ships cannot touch each other, even at corners.
4. Player move:
   • The player enters coordinates (row, column) to shoot at an empty square.
   • If a shot hits a ship, "Hit!" is displayed. Otherwise "Miss!"
   • If the shot is repeated into the cell where the previous shot was, the message "Sunk! Continue.." is displayed, and the player can continue the game.
5. End of the game:
   • The game ends when all ships are sunk.
   • After completing the game, congratulations and the number of shots taken are displayed
   

METHODS USED:
#### Game Setup:
1. Compile and run the provided C++ code using a C++ compiler.
2. The game will prompt you to enter your name. Type your name and press Enter.
3. The game board will be initialized with ships placed randomly. The board is a 6x6 grid.

#### Game Rules:
1. **Objective:** Sink all the ships on the board.
2. **Ships:** There are a total of 7 ships on the board:
   - One ship of length 3.
   - Two ships of length 2.
   - Four ships of length 1.
3. **Gameplay:**
   - You will be prompted to enter your guess in the format (row, col) where both row and col are integers.
   - Rows and columns are numbered from 0 to 5.
   - After each guess, the board will be displayed showing hits ('X'), misses ('*'), and empty spaces ('.').
   - The game will inform you if your guess is a hit or a miss.
4. **Hit:**
   - If your guess hits a ship, the board will display "Hit!" and mark the hit with 'X'.
   - The number of ship hits will be tracked.
   - If you sink all ships, the game will end, and you will be declared the winner.
5. **Miss:**
   - If your guess misses a ship, the board will display "Miss!" and mark the miss with '*'.
   - Total shots taken will be tracked.
6. **Invalid Moves:**
   - If you enter an invalid move (e.g., a move outside the board or a move already guessed), you will be prompted to enter a new guess.
7. **Game Over:**
   - The game ends when all ships are sunk.
   - The final board will be displayed.
   - Your total shots taken will be shown.
   - You will be congratulated for sinking all the ships.

#### Interaction:
- **Guess Input:**
  - Enter your guess in the format (row, col) when prompted.
  - Example: To guess at row 2, column 3, enter "2 3" and press Enter.

- **Invalid Move Handling:**
  - If your input is invalid, you will be prompted to enter a new guess.

- **Game Replay:**
  - After completing a game, the program will prompt you to play again.
  - Type any input to play again or close the program to exit.

#### Note:
- The game uses a basic console-based interface and might not work well in all environments.
- The delay after each move is for visual effect and can be adjusted by modifying the `this_thread::sleep_for` duration in the code.


GENERAL COURSE OF THE GAME:
1. Entering the player name:
   • The player enters his name.
2. Initialization and start of the game:
   • The board and variables are initialized.
   • The player makes moves until he sinks all the ships.
3. End of the game:
   • After completing the game, congratulations and the number of shots taken are displayed.
