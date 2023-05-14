# Tictac
# Tic tac toe game which was played by us in childhood
# Some of the Python concepts used in this program are:

Object-oriented programming (OOP) - The program uses classes to create objects that represent the game board and the game pieces (X and O).

Multithreading - The program uses threads to handle incoming messages from the other player without interrupting the main game loop.

Socket programming - The program uses sockets to establish a network connection between the two players.

Pygame library - The program uses the Pygame library to create a graphical user interface (GUI) for the game and to handle input events.

File handling - The program uses files to store images used in the game.

Conditional statements - The program uses conditional statements such as if-else statements to determine the game state and the winner.

Loops - The program uses loops such as for loops and while loops to iterate over lists and handle game events.

Functions - The program uses functions to encapsulate specific tasks such as checking for a win condition and updating the game state.

This is a Python script for a Tic Tac Toe game with a client-server architecture, where two players can play the game by sending their moves to the server. The server then sends the moves to the other player, and the game progresses until a player wins or the game is drawn.

The script uses the Pygame library to create a graphical user interface and provides a "test" class to determine the position of the mouse click and send the move to the server. The "clss" class runs in a separate thread to receive the moves from the server.

The main loop of the program checks for events, such as mouse clicks or quitting the game, and updates the game board accordingly. The "win" function checks if any player has won the game by checking if any row, column, or diagonal has the same symbol.

Overall, this is a basic implementation of a Tic Tac Toe game with a client-server architecture using the Pygame library. However, the code could be improved in terms of code structure, error handling, and performance.
