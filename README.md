### Team Members:
Kyle Foisy -   101215573

Peter Mccomb - 101243509

Yuvraj Bains - 101235916

Daniel Afanassiev - 101146679
## PURPOSE OF PROJECT:
This project's goal is to make a simpler version of the traditional board game Scrabble. Players can arrange tiles on a 15x15 board, create words, and receive points depending on the value of the tiles they use in this text-based gaming interface. The score calculation and word placement validation are done in accordance with the fundamental Scrabble rules in this implementation.

## Date: Dec 6, 2024

## HOW TO START THIS PROJECT:
Download the project ZIP file or clone the repository using Git: git clone https://github.com/Team-14---SYSC-3310---Scrabble.git

## USER INSTRUCTIONS:
You will be asked to enter the number of players when the game has finished running. By entering tile positions and words, each player will alternately place tiles on the board. By indicating their beginning position and direction (horizontal or vertical), players can write words on the board. The software will determine the score and determine whether the word is valid based on Scrabble rules. Gameplay Rules: Words have to be positioned next to tiles that already exist. It is necessary to position the initial word in the middle of the board. After every turn, players will draw fresh tiles until the tile bag is empty. Winning the Game: The game continues until all tiles have been placed or no valid moves are left. The player with the highest score at the end of the game wins.

When using the undo feature to switch between turns, the game will always switch to the beginning of the last human player's turn.

When saving or loading a game, the game will always be saved to or loaded from the same file the jar file is in.

The undo/redo feature only considers the currently opened window. Undo/Redo states are not saved in a save file.

Loading a board requires loading a JSON file that must be in the same directory as the JAR file. See example file included for formatting. Note that the starting square must always be on the 8th row and 8 column. 

If prompted for a file name, do not include the file extension.

#### Changes since Deliverable 3
##### What's done:
- Added Undo/Redo functionality
- Added Save/Load functionality
- Added functionality to load a custom board
- Bug fixes regarding blank tiles

##### What's missing:

##### Known issues:
-The board loader does not verify file formating correctness.

### other TODOs:

