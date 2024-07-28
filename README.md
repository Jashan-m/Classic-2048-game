## 2048 Game in Python 
This repository contains a simple implementation of the 2048 game using Python and the Tkinter library for the graphical user interface. The game includes the basic functionalities of 2048, such as creating a new game, moving tiles with keyboard arrow keys, and updating the game board.
### Features
- **Graphical Interface**: The game uses Tkinter to create a graphical interface, displaying a 4x4 grid for the game board.
- **New Game Button**: Start a new game anytime by clicking the "New Game" button.
- **Random Tile Placement**: New tiles (2 or 4) are randomly placed on the grid after each move.
- **Tile Merging**: Combine tiles with the same number to form a tile with double the value.
- **Score Tracking**: Keeps track of the score, which increases when tiles are merged.
### How to Run
1. Ensure you have Python installed on your machine.
2. Install Tkinter if it's not already installed. (Tkinter usually comes pre-installed with Python on most systems.)
3. Clone the repository.
4. Navigate to the directory containing the script.
5. Run the script using Python:
### How to Play
- Use the arrow keys to move the tiles in the respective direction (Up, Down, Left, Right).
- When two tiles with the same number collide, they merge into a single tile with double the value.
- The goal is to create a tile with the number 2048, but you can continue playing to reach higher scores.
### Code Overview
- **Game2048 Class**: Contains the main logic for the game, including initializing the game, handling user input, updating the game board, and managing the score.
- **draw_grid()**: Draws the initial empty grid and updates it with the current tile values.
- **place_new_tile()**: Places a new tile (2 or 4) on a random empty spot on the grid.
- **move()**: Handles the movement of tiles based on user input (arrow keys).
- **shift_tiles()**: Manages the logic for shifting and merging tiles.
- **update_grid()**: Updates the graphical display of the grid.
- **new_game()**: Resets the game to start a new round.
