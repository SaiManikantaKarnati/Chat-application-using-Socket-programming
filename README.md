# Chat-application-using-Socket-programming in Python

Algorithm for Server:-
  (i) Create a socket with the socket() system call. 
  (ii) Bind the socket to an address using the bind() system call. For a server socket on the Internet, an address consists of a port number on the host machine. 
  (iii)Listen for connections with the listen() system call. 
  (iv)Accept a connection with the accept() system call. This call typically blocks the connection until a client connects with the server. 
  (v)Send and receive data using the read() and write() system calls. 
  
Algorithm for Client:-
  (i) Create a socket with the socket() system call. 
  (ii) Connect the socket to the address of the server using the connect() system call. 
  (iii) Send and receive data. There are a number of ways to do this, but the simplest way is to use the read() and write() system calls. 
