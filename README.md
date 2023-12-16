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
1. "initializeBoard()" - Initialize the board:
   • Fills the playing field with empty cells.
   • Places ships on the board according to given rules.
2. "printBoard()" - Display the board on the screen:
   • Displays the current state of the playing field.
3. "isValidMove (int row, int col)" - Checking the validity of a move:
   • Checks that the entered coordinates are within the board and the cell is free.
4. "isGameOver()" - Checking the end of the game:
   • Checks if all ships are sunk, returning "true" if the board does not contain any ships.
5. "playGame (const string& playerName)" - Main game loop:
   • Initializes the board and variables.
   • Invites the player to make moves, displaying the state of the board after each move.
   • Ends the game and congratulates the player after all ships have been sunk.
   

GENERAL COURSE OF THE GAME:
1. Entering the player name:
   • The player enters his name.
2. Initialization and start of the game:
   • The board and variables are initialized.
   • The player makes moves until he sinks all the ships.
3. End of the game:
   • After completing the game, congratulations and the number of shots taken are displayed.
