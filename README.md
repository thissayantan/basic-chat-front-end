# Chat App Frontend

This README details the frontend setup for a real-time chat application using HTML, CSS, and JavaScript with Socket.IO.

## Overview

This frontend application is designed to work in conjunction with a backend chat server, allowing users to join chat rooms, send and receive messages in real-time, and view active users and rooms. It uses Socket.IO for seamless real-time communication.

## Features

- Real-time messaging.
- User can join and leave chat rooms.
- Displays messages dynamically in the chat window.
- Shows active users in the current room.
- Lists all active chat rooms.
- Indicates when a user is typing a message.

## Setup

### Prerequisites

- A compatible backend server running Socket.IO.
- Basic knowledge of HTML, CSS, and JavaScript.

### Files Included

- `index.html`: The main HTML file.
- `style.css`: Styling for the application.
- `app.js`: JavaScript file handling the client-side logic.

## Usage

1. Open `index.html` in a web browser.
2. Enter a name and a room to join.
3. Start chatting by typing messages and sending them.
4. Real-time updates will appear in the chat window.

## Key Components

- **Socket.IO Client**: Establishes a connection with the backend server.
- **Event Listeners**: Handles chat messages, joining rooms, and displaying user and room lists.
- **UI Interactions**: Updates the chat display and shows user activities like typing.

## Event Handling

- `message`: For sending and receiving messages.
- `enterRoom`: For a user entering a chat room.
- `activity`: To show when a user is typing.
- `userList`: To display the list of users in a room.
- `roomList`: To display a list of active rooms.

## HTML Structure

- Forms for joining a room and sending messages.
- A display area for chat messages.
- Sections to show active users and chat rooms.

## CSS

`style.css` includes basic styles to organize the layout and appearance of the chat application.

## JavaScript

`app.js` contains the logic for connecting to the Socket.IO server, handling events, and updating the UI in response to server messages.

## Conclusion

This frontend setup, when connected to a suitable backend, provides a fully functional real-time chat application. It's a great starting point for anyone looking to learn real-time web communication.