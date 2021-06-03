
# compile 

To compile `server.c`

```
gcc server.c -o server
```

To compile `client.c`

```
gcc client.c -o client
```

# command

To run server 
 - Port : TCP 10011

```
$ ./server
<output>
Server Received: aaaa
```

To run client

```
$ ./client 127.0.0.1 10011  
<output>
Please enter the message: aaaa

Sending to SERVER: aaaa
 
Received FROM SERVER: 
aaaa Please enter the message: 
```

# Reference 
https://www.thegeekstuff.com/2011/12/c-socket-programming/

  
