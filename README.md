# Real-Time-Chat-App

Creating a real-time chatting app in a single Python file without using HTML or external packages like Flask or Django for serving the app is challenging, but you can utilize Python's built-in socket module for creating a simple server-client architecture. However, please note that without using external packages, the solution will be quite basic and may not have the features or security measures found in more robust solutions.

To run this code:

Copy the code into a Python file (e.g., chat_server.py). Run the Python file using python chat_server.py. This code sets up a simple server that listens for connections on port 9999. When a client connects, it starts a new thread to handle that client's messages. Messages received from one client are broadcasted to all other connected clients.

To connect to the server, clients will need to use a simple Python script or a telnet client to connect to the server's IP address and port.

Please note that this code lacks many features typically found in a real-time chat application, such as user authentication, message formatting, error handling, and security measures. Additionally, running this server in a production environment without proper security measures could pose risks.
