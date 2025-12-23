
**Simple C HTTP Server**

This project is a basic **HTTP server written in C**. It listens on a specified port and serves an HTML file (`index.html`) to connected clients using TCP sockets.

### Features

* Uses socket programming in C
* Listens on port **8080**
* Sends an HTML file to the client
* Handles basic HTTP requests

### Files

* `server.c` – Main server source code
* `index.html` – HTML file served to the client

### How to Compile

```bash
gcc server.c -o server
```

### How to Run

```bash
./server
```

### How to Access

Open a browser and go to:

```
http://localhost:8080
```

### Notes

* Make sure `index.html` is in the same directory as `server.c`
* This is a simple single-client server meant for learning purposes

