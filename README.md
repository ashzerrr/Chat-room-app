This project implements a simple chat room application where multiple clients can connect to a server, choose unique usernames, and exchange messages in real-time. Communication follows a predefined protocol:

The server requests a username and ensures it’s unique.
Once accepted, the client can send messages broadcasted to all connected clients.
Clients receive messages prefixed with "MESSAGE" from the server.
The application uses sockets, threads, and Java Swing GUI components (for clients) or console logs (for servers) to manage chat sessions
