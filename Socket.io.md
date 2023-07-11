## Web Sockets

- **What is a Web Socket?**
  A Web Socket is a protocol for real-time communication between a client and a server without frequent requests.

- **Web Socket request/response handshake and connection establishment:**
  The connection is established through a handshake process, enabling simultaneous data exchange between the client and server.

- **Web Sockets provide a standardized way to send content without client request:**
  Web Sockets allow the server to send content to a client without waiting for a request, enabling real-time updates.

## Socket.io Tutorial

- **What does `io.on()` do?**
  The event handler `io.on()` listens for events from clients, allowing the server to respond accordingly.

- **Possible proof of life or expected code behavior:**
  Proof of life includes successful connections, event handling, broadcasting messages, and real-time updates.

- **What does `socket.emit()` do?**
  `socket.emit()` is used to send events from the client to the server or to a specific client.

## Socket.io vs Web Sockets

- **Difference between WebSocket and Socket.IO:**
  WebSocket is the communication protocol, while Socket.IO is a library with additional features and abstractions built on top of WebSocket.

- **When to use Socket.IO:**
  Socket.IO is suitable for real-time, bi-directional communication, offering features like automatic reconnection and broadcasting.

- **When to use WebSockets:**
  WebSockets are more appropriate for basic, low-level communication needs without additional abstractions.

## TCP Handshakes Explained

- **Key takeaways from the video:**
  The video explains the process of establishing a reliable connection between devices over a TCP network.

- **Translation for a non-technical friend:**
  Imagine sending letters to a friend. TCP handshakes are like a series of steps to ensure both parties are ready to exchange messages securely.
