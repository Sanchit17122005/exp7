# Real-Time Chat App - Socket.io

A real-time chat application built with Node.js, Express, and Socket.io.

## Setup

1. Install dependencies:
   npm install

2. Start the server:
   node index.js

Server runs on http://localhost:5001

## Features

- Real-time messaging using Socket.io
- Multiple users can join the chat
- Shows when a user joins or leaves
- Typing indicator
- Displays online users list

## How It Works

- User joins with a username
- Messages are broadcast to all connected users in real time
- System notifies everyone when a user joins or leaves
- Typing indicator shows when someone is typing

## Socket Events

| Event       | Description                        |
|-------------|------------------------------------|
| join        | User joins the chat with a username |
| sendMessage | User sends a message               |
| typing      | User is typing                     |
| disconnect  | User leaves the chat               |

## Tech Stack

- Node.js
- Express
- Socket.io
- CORS
