# Live Chat Bot

This project is a chat application built with HTML, CSS, JavaScript, and Socket.IO. 

- **Join or Create a Room**: Users can enter an existing chat room with a unique code or create a new room.
- **Real-Time Messaging**: Messages are updated in real-time using Socket.IO.
- **Responsive Layout**: The chat interface is designed to be simple and user-friendly.

## Project Structure

- **main.py**: The main server script where the Socket.IO setup and routes are defined.
- **Templates**:
  - `base.html`: Base template for the project structure.
  - `home.html`: Entry page where users can enter their name and a room code.
  - `room.html`: The chat room interface, where messages are sent and displayed in real time.
- **Static**:
  - `style.css`: Contains styles for the chat interface and layouts.

## How to Run

1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
