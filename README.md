Collaborative Code Editor
Real-time collaborative code editor with multi-language execution, live cursors, and user presence. Built with React, Node.js, MongoDB, and Socket.io.
Features

Real-time collaboration - Multiple users can edit the same code simultaneously
Multi-language support - Run JavaScript, Python, C++, Java, and more
Live cursors - See where everyone is editing in real-time
User presence - Shows who's currently in the room
Persistent rooms - Your code gets saved automatically
Join via URL - Create or jump into existing rooms easily
Clean interface - Simple, responsive design that just works

Built with
Frontend:

React
Socket.io client
Lucide icons

Backend:

Node.js + Express
Socket.io for real-time changes
MongoDB with Mongoose

Getting started

Clone this repo
npm install in both frontend and backend folders
Set up your .env file (check .env.example)
Make sure MongoDB is running
npm start to fire it up

How it works
Each room gets its own URL where people can join and start coding together. The editor syncs changes instantly and shows everyone's cursor position. Code execution happens server-side in isolated environments.
Rooms persist their code in MongoDB so you can always come back to where you left off.
