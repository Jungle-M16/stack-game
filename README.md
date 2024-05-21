# stack-game

# Stack Game

A simple HTML, CSS, and JavaScript-based stack game where players stack blocks that bounce back and forth on an 18x24 grid. The blocks reduce in size according to the amount overshot by the previous block.

## Gameplay

- Press the spacebar or click on the game area to place a block.
- Stack the blocks as high as you can.
- If a block overshoots the previous block, it will reduce in size.
- The game ends if there is no overlap between the current block and the previous block.
- The game is won when the stack reaches the top of the grid.

## Features

- Score system: Earn points based on the overlap of the blocks.
- High score: The highest score is saved and displayed.
- Difficulty levels: Choose between easy, medium, and hard difficulty levels.
- Dynamic block colors: Blocks change hue as you progress.
- Game state messages: Displays messages indicating the current state of the game (e.g., game over, you win).

## Difficulty Levels

- **Easy**: Slower speed and wider blocks.
- **Medium**: Moderate speed and block width.
- **Hard**: Faster speed and narrower blocks.

## Controls

- **Spacebar**: Place a block.
- **Mouse click**: Place a block.

## How to Play

1. Open the `index.html` file in a web browser.
2. Select a difficulty level from the dropdown menu.
3. Click the "Restart Game" button to start.
4. Press the spacebar or click to place blocks as they move back and forth.
5. Stack the blocks as high as you can while trying to maintain overlap with the previous block.

## Code Structure

- **HTML**: Sets up the game structure and UI elements.
- **CSS**: Styles the game and UI elements.
- **JavaScript**: Contains the game logic, including block movement, collision detection, scoring, and difficulty settings.

## Files

- `index.html`: Main HTML file.
- `README.md`: This readme file.
