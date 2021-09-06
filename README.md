# Client-Server-application
Simple implemention of concurrent day-time client-server application
- code will run on linux or mac
- Windows user can use https://replit.com/~ website

# ALGORITHM

- server()
	- Create UDP socket
  - Bind socket to address
  - Wait for datagram from client
  - Process and reply to client request
  - Repeat while server is active

- client()
  - Create UDP socket
  - Send request to server
  - Wait for datagram from server
  - Process and reply from server
  - Close socket and exit


# Screenshots
server.c output

![Image of server](https://github.com/AbhishekKumarSingh00/Client-Server-application/blob/main/server-output.jpg)

client.c output

![Image of client](https://github.com/AbhishekKumarSingh00/Client-Server-application/blob/main/client-output.jpg)
