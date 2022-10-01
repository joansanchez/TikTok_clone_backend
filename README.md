# Web Sockets
WebSocket is basically an application protocol (with reference to the ISO/OSI network stack), 
message-oriented, which makes use of TCP as transport layer.

The idea behind the WebSocket protocol consists of reusing the established TCP connection 
between a Client and Server. After the HTTP handshake the Client and Server start speaking 
WebSocket protocol by exchanging WebSocket envelopes.


## About this repo
This projects aims as a learning platform for me to practice with WebSockets, replicating 
some of the main functionalities of TikTok

In this project I will use STOMP messaging with Spring to create an interactive web application. 
STOMP is a subprotocol operating on top of the lower-level WebSocket.

## Useful links
[Using WebSocket to build an interactive web application](https://spring.io/guides/gs/messaging-stomp-websocket/)

