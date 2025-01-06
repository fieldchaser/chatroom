# WebSocket Chatroom

A simple real-time chatroom application built using **Golang**, **Gorilla WebSocket**, and a modern front-end interface. This project allows users to connect to the server, exchange messages in real time, and see a list of connected users.

---

## Features

- **Real-time Messaging**: Chat with other users in real time.
- **User Management**: View the list of active users.
- **Modern UI**: A visually appealing chat interface with gradient backgrounds.
- **WebSocket-Based**: Powered by WebSocket for fast and persistent communication.

---

## Technologies Used

### Backend
- **Golang**: Core language for the server.
- **Gorilla WebSocket**: For WebSocket handling.
- **Gorilla Mux**: For routing.

### Frontend
- **HTML/CSS/JavaScript**: The chat interface is implemented in plain HTML and JavaScript.
- **Responsive Design**: Optimized for desktop and mobile devices.

---

## Project Structure

```plaintext
.
├── server.go       # Main entry point for the backend server
├── hub.go          # WebSocket hub to manage connections and broadcast messages
├── data.go         # Data model for chat messages and user info
├── connection.go   # WebSocket connection management
├── static/
│   ├── index.html  # Frontend chat interface
│   ├── styles.css  # (Optional) External CSS if separated
├── README.md       # Documentation
