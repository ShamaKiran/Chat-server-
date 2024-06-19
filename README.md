# Chat-server-
This project is a secure chat application that allows multiple users to communicate over a network using SSL/TLS encryption. The application features a graphical user interface (GUI) for the client, enabling users to send messages and files securely. It also includes a server that handles multiple client connections, broadcasting messages, and managing file transfers.

Key Features
Secure Communication: Utilizes SSL/TLS for encrypted communication between the client and server, ensuring data privacy and integrity.
GUI Client: Provides a user-friendly interface for connecting to the server, sending messages, and transferring files.
File Transfer: Supports the sending and receiving of files between clients.
Multi-client Handling: The server can manage multiple clients simultaneously, broadcasting messages and handling file transfers.
Technologies and Skills Used
Python: The core programming language used for both the client and server applications.
Tkinter: A Python library for creating the graphical user interface (GUI) of the chat client.
Socket Programming: Utilized for network communication between the client and server.
SSL/TLS: Implemented using Python's ssl library to secure data transmission.
Threading: Used to handle multiple clients concurrently on the server and to manage asynchronous message receiving on the client.
File Handling: Mechanisms for reading, writing, and transmitting files over the network.
