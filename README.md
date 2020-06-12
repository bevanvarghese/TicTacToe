# Tic Tac Toe
A GUI-enabled online multiplayer rendition of the popular two-player game, Tic Tac Toe. Designed as an assignment for COMP2396: Object Oriented Programming & Java. Uses concepts such as OOP, multi-threading and sockets. 

### Running the game
#### To run from an IDE
- Compile the files TicTacToeServer.java and TicTacToeClient.java
- Run TicTacToeServer.java on the host machine
- Run TicTacToeClient.java on Player 1's machine
- Run TicTacToeClient.java on Player 2's machine

#### To run from the terminal 
- From the terminal, navigate to the directory containing  TicTacToeServer.java
- Enter the following commands to set up the server
```
javac TicTacToeServer.java
java TicTacToeServer
```
- For Player 1, navigate to the directory containing TicTacToeClient.java
- Enter the following commands to set up the game for Player 1:
```
javac TicTacToeClient.java
java TicTacToeClient
```
- Repeat the last two steps to set up the game for Player 2

### Assumptions
- If both players have disconnected, the server will be restarted before starting a new game
- In no case will a third player attempt to join the game

