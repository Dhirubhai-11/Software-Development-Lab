**Project Structure**
ChatApplication/
│
├── ChatClient.java
├── ChatServer.java
└── ClientHandler.java

# Experiment 1  
## Multithread Chat Application (Java)

### Aim  
To develop a multithreaded client–server chat application using Java sockets.

### Description  
This project implements a chat system where multiple clients can connect to a server simultaneously. Each client is handled using a separate thread, allowing real-time communication.

### Files  
- ChatServer.java – Starts the server and accepts clients  
- ClientHandler.java – Handles each client using a separate thread  
- ChatClient.java – GUI-based chat client using Swing  

### How to Run  
1. Compile files:  
   javac *.java  

2. Start server:  
   java ChatServer  

3. Start client:  
   java ChatClient  

### Output  
Multiple clients can join the chat and exchange messages in real time.

### Technologies  
Java, Socket Programming, Multithreading, Swing


