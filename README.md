🖥 Collaborative Code Editor

A real-time collaborative code editor with multi-language execution, live cursors, and user presence tracking.
Built with React, Node.js, MongoDB, and Socket.io.

<img width="1902" height="720" alt="Screenshot 2025-08-14 111736" src="https://github.com/user-attachments/assets/3227f732-83a0-4a80-bbf0-4e2560327e43" />





🚀 Features:

-Real-time collaboration – Multiple users can edit the same code simultaneously

-Multi-language support – Run JavaScript, Python, C++, Java, and more

-Live cursors – See where everyone is editing in real-time

-User presence – Shows who’s currently in the room

-Persistent rooms – Your code is saved automatically in MongoDB

-Join via URL – Create or jump into existing rooms instantly

-Clean interface – Simple, responsive design that just works

🛠 Built With 
Frontend:
-React
-Socket.io Client
-Lucide Icons

Backend:
-Node.js + Express
-Socket.io for real-time communication
-MongoDB + Mongoose for data persistence

⚙ How It Works

Each room has its own unique URL where users can join and start coding together.
The editor syncs changes instantly and displays each participant’s cursor position.

Code execution is handled server-side in isolated environments, and rooms persist their code in MongoDB so you can pick up right where you left off.

💡 Why This Project is Useful

This project solves a common problem for developers, students, and interviewers — the need to collaborate on code in real time without complex setup.

Instead of screen sharing or constantly sending files back and forth, collaborators can:

-See changes instantly

-Run code in multiple languages

-Track who’s active in the session

It’s ideal for:

-Pair programming without needing to be in the same location

-Technical interviews focused on problem-solving, not setup

-Live coding sessions for teaching or workshops

-Hackathons where speed and teamwork matter

📦 Try it out yourself!

Clone this repo

git clone https://github.com/yourusername/collaborative-code-editor.git


Install dependencies in both frontend and backend folders

"npm install"


Set up your .env file (check .env.example for required variables)

Make sure MongoDB is running

"mongod"


Start the server

'npm start"
