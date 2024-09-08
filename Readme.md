# QUICKTALK - A Real-Time Chat Application

QUICKTALK is a real-time chat application built using Socket.io for WebSocket communication, Express.js for the backend, and plain HTML/CSS for the frontend. This app allows users to exchange messages instantly, see how many clients are connected, and receive typing feedback.

![page1](/image.png)

## Features

- **Real-time Messaging**: Messages are delivered instantly to connected clients.
- **User Feedback**: See when other users are typing in real-time.
- **Client Counter**: Displays the total number of clients connected to the server.
- **Own Message Highlight**: Your messages are aligned to the right side of the chat box for better user experience.
- **Message Timestamps**: Messages show when they were sent using relative time (e.g., "a few seconds ago").
- **Notification Sound**: A sound is played every time a new message is received.

## Tech Stack

- **Backend**: 
  - Node.js
  - Express.js
  - Socket.io

- **Frontend**: 
  - HTML
  - CSS
  - Font Awesome icons
  - Moment.js (for date formatting)

- **Real-time Communication**: Socket.io

## How to Run Locally


## Usage
- Enter your username (defaults to anonymous).
- Start typing your message in the input box and hit "Send" or press "Enter".
- You will hear a notification sound when other users send a message.
- The total number of clients connected is shown at the bottom of the screen.


## File Structure
.
├── public
│   ├── index.html         # Frontend HTML file
│   ├── style.css          # Styles for the chat interface
│   └── main.js            # Frontend JavaScript logic
├── server.js              # Node.js server and Socket.io logic
├── package.json           # Project metadata and dependencies
└── README.md              # Project documentation


## Future Enhancements
- Add authentication and user login functionality.
- Implement chat rooms or private messaging between users.
- Store chat history using a database like MongoDB.
- Add file sharing capability (images, videos, etc.).

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/ichat.git
   cd ichat
