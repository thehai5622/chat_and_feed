# Project
This is demo socket on console brower

```bash
let socket = new WebSocket("ws://localhost:8080/websocket")
```
```bash
socket.onmessage = (event) => {console.log("Received from the server: ", event.data)}
```