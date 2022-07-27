# CLIENT-SERVER-COMMUNICATION-USING-UDP

Aim: To implement a client server communication using UDP.
Algorithm

SERVER

• Include appropriate header files.
• Create a UDP Socket.
• Fill in the socket address structure (with server information)
• Specify the port where the service will be defined to be used by client.
• Bind the address and port using bind() system call.
• Server executes listen() system call to indicate its willingness to receive connections.
• Send a message to client using sendto() system call.

CLIENT

• Include appropriate header files
• Create a UDP Socket.
• Fill in the socket address structure (with server information)
• Specify the port of the Server, where it is providing service• Receive the message from the server using recvfrom () system call.
• Write the result thus obtained on the standard output.
