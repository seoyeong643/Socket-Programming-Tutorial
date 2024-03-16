# Socket-Programming-Tutorial
Python Socket Programming Tutorial Youtube - [Watch Tutorial](https://youtu.be/3QiPPX-KeSc?si=kHJmQ4Ta3xqF-9T6)

This project demonstrates a simple client-server interaction using Python's socket programming. The server listens for incoming connections from clients, receives messages, and sends back a confirmation. The client connects to the server, sends messages, and receives acknowledgments.

## Project Structure

- `server.py`: Contains the server-side code.
- `client.py`: Contains the client-side code.

---

### Running the Server

1. Open a terminal and navigate to the project directory.

2. Run the server script.

    ```bash
    python server.py
    ```

3. The server will start listening for connections. It will display information about incoming connections and received messages.

### Running the Client

1. Open another terminal and navigate to the project directory (if not already there).

2. Run the client script.

    ```bash
    python client.py
    ```

3. The client will connect to the server and send messages. It will display the acknowledgment received from the server.

4. You can send multiple messages. To disconnect from the server, send the `!DISCONNECT` message.
