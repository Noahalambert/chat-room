# Chat Room

A real-time chat room built with Python and WebSockets.

## Features

- Real-time messaging between multiple users
- Username support
- Simple browser-based client

## Requirements

- Python 3.7+
- websockets library

## Installation

1. Clone this repository:
```bash
   git clone https://github.com/noahalambert/chat-room.git
   cd chat-room
```

2. Install dependencies:
```bash
   pip install websockets
```

## Usage

1. Start the server:
```bash
   python server.py
```

2. Open `client.html` in your browser (double-click the file or drag it into a browser window)

3. Open additional browser tabs to simulate multiple users

4. Enter a username when prompted and start chatting!

## How It Works

- **server.py** - A WebSocket server using Python's `asyncio` and `websockets` libraries. It maintains a set of connected clients and broadcasts messages to all users.

- **client.html** - A simple HTML/JavaScript frontend that connects to the WebSocket server and provides a basic chat interface.

## License

MIT