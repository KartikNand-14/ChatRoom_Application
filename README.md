# ChatRoom_Application
This project is a real-time chatroom application consisting of a server and client implementation. The chatroom allows multiple clients to connect, exchange messages, and engage in live conversations. It enables users to join the chatroom, communicate with each other, and gracefully leave the chatroom when they choose to.

# Technical Implementation
The project is implemented in C, utilizing socket programming to handle connections and communication with clients. Multi-threading is used to manage multiple client connections concurrently, enabling seamless message delivery. Both the server and client applications are written in C, and they communicate with each other through sockets.

# Requirements
C Compiler (e.g., GCC)
Standard C Libraries
Unix-Based System (e.g., Linux)

# Usage
# Server:
Compile and run the server executable, providing the desired port number as a command-line argument.
The server will start listening on the specified port for incoming connections from clients.

# Client:
Compile and run the client executable, providing the server's IP address and port number as command-line arguments.
Upon successful connection, the client will be prompted to enter a username to join the chatroom.
Clients can start sending and receiving messages in the chatroom.
To exit the chatroom, simply type "exit" in the message prompt.
