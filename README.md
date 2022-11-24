# Computer-Networks
TIK TOK GAME
In this project, a multiplayer tic tac toe game has been implemented using socket programming,
the concept of threading and the pygame module provided by Python. A server creates the game
in a local area network, and the players in the LAN can connect to the server by using the IP
address of the server. When a new connection arrives ,a new thread is created. To avoid race
conditions taking place between threads, the concept of mutex has been implemented. The
pygame module makes a physical representation of the game, and provides a board for the two
players to play on.
