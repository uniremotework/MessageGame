# MessageGame
Having a Player object:
1. a Player object has a state "ready" or "not ready"
2. a Player object can send and receive messages

The use case for this task is as bellow:
1. create 2 players
2. wait until both players are "ready"
3. one of the players should send a message to second player
4. when a player receives a message should send back a new message that contains the previous message concatenated with the message counter that this player sent (additional info: terminate the program after the "initiator" received 10 messages. the counter should be per player)
5. finalize the program (gracefully) after one of the players sent 10 messages (stop condition)
6. document for every class the responsibilities it has
7. additional challenge: have every player in a separate JAVA process (additional info: separate processes means 2 java processes, concurrent processes (threads) are still in the same VM. What you use for communication is your choice)

Please deliver a maven project with the source code so the jar can be built.
Please provide a shell script to start the program.
Everything what is not clearly specified is to be decided by developer.
