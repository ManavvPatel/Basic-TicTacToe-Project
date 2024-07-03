# Basic-TicTacToe-Project
A simple game of TicTacToe created to understand the basics of first year course work of Bachelors in CS 

Code Structure
The game is implemented using an object-oriented programming (OOP) structure, consisting of two main classes: Board and Player. Each class is designed to encapsulate specific behaviours and attributes.

Board Class
The Board class represents the game board and includes the following methods:
  •	Constructor: Initializes the board using an array of characters.
  •	display_board: Prints the current state of the board.
  •	set_move: Sets the player's move on the board.
  •	is_position_available: Checks if a given position on the board is available.
  •	check_winner: Checks if there is a winner.
  •	is_full: Checks if the board is full.

Player Class
The Player class represents a player in the game and includes the following methods:
  •	Constructor: Initializes a player with a player number, symbol, and board.
  •	make_move: Makes a move after verifying the position's availability using the is_position_available method from the Board class.
  •	move_validity: Checks if the input position is valid.
  •	get_player_number: Retrieves the player's number.
  •	get_symbol: Retrieves the player's symbol.

Main Method
After defining the Board and Player classes, the main method sets up the game:
  1.	Board Creation: Initializes a new board.
  2.	Player Setup: Creates two players with their respective symbols.
  3.	Game Loop: Uses a while loop to continuously run the game until a player wins or the board is full. The variable game_running is set to true                  to control the loop. When a player wins or the board is full, game_running is set to false, ending the game and displaying the                      result.
