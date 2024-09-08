# Socket.IO Chat Application with Nicknames and Rooms

## Project Overview
This is a real-time chat application built using Node.js, Express, and Socket.IO. It allows multiple users to communicate in specific rooms, and each user can set a nickname that is displayed alongside their messages.

## Features
1. **Nicknames**: Users can set their own nicknames.
2. **Rooms**: Users can join different chat rooms, and their messages are only broadcast to other users in the same room.
3. **Real-time messaging**: Messages are instantly broadcast to everyone in the same room.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/chat-app.git
    cd chat-app
    ```

2. Install the necessary dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    node index.js
    ```

4. Open the application in your browser by navigating to:
    ```
    http://localhost:3000
    ```

## Usage

1. Enter your **nickname** and the **room name** you want to join.
2. Type a message in the input field and press **Send**.
3. Your message will be broadcast to all users in the same room, displayed as `[Nickname] says: [Message]`.

## Dependencies

- [Express](https://expressjs.com/) - Web framework for Node.js.
- [Socket.IO](https://socket.io/) - Library for real-time web applications.
