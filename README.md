# Network Programming

Projects of the Network Programming course @ CS NCTU 2019 fall.

## 1. npshell
Implement a Shell with special piping mechanisms. [[spec]](https://people.cs.nctu.edu.tw/~cysun0226/np-spec/NP_Project1_Spec.pdf)

## 2. chat room
Design a chat-like system server. [[spec]](https://people.cs.nctu.edu.tw/~cysun0226/np-spec/NP_Project2_Spec.pdf)

* Concurrent connection-oriented: allows clients to connect & execute shells
* Chat-like system: Message sending (between users or broadcast), piping content between users, etc.
    * Single-process concurrent
    * Multi-process (fifo + shared memory)

## 3. http & cgi
Implement a simplified HTTP server and console cgi programs. [[spec]](https://people.cs.nctu.edu.tw/~cysun0226/np-spec/NP_Project3_Spec.zip)

## 4. socks4
Implement the SOCKS4 protocol. [[spec]](https://people.cs.nctu.edu.tw/~cysun0226/np-spec/NP_Project4_Spec.pdf)

* SOCKS4 Server Connect Mode
* SOCKS4 Server Bind Mode
* CGI Proxy
* Firewall
