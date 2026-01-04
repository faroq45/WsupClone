💬 Wclone – Real-Time Chat Application

Wclone is a real-time chat application built with Node.js, Express, Socket.IO, and MongoDB.
It supports user authentication, persistent messaging, and live communication using WebSockets.

This project demonstrates backend fundamentals, real-time systems, authentication, and database integration.

🚀 Features

🔐 User authentication (login & signup)

💬 Real-time messaging with Socket.IO

🗄️ Persistent chat messages using MongoDB

👥 User presence handling (connect / disconnect)

🧠 Session-based authentication

🎨 Server-rendered UI with EJS

⚙️ Clean project structure (routes, models, controllers)

🛠️ Tech Stack

Backend: Node.js, Express

Real-time: Socket.IO

Database: MongoDB (Mongoose)

Authentication: Express Sessions

Templating: EJS

Version Control: Git & GitHub

📁 Project Structure
chat-app/
├── server.js
├── package.json
├── package-lock.json
├── routes/
├── controllers/
├── models/
├── sockets/
├── views/
├── public/
├── .gitignore
└── README.md

⚙️ Prerequisites

Make sure you have the following installed:

Node.js (v16+ recommended)

MongoDB Community Server (running locally on port 27017)

Git

📦 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/faroq45/Wclone.git
cd Wclone/chat-app

2️⃣ Install Dependencies
npm install

3️⃣ Environment Variables

Create a .env file in the project root:

PORT=9100
MONGO_URI=mongodb://127.0.0.1:27017/chatapp
SESSION_SECRET=your_secret_key


⚠️ Do not commit .env to GitHub

4️⃣ Start MongoDB

Make sure MongoDB is running:

net start MongoDB


(Use Administrator PowerShell on Windows)

5️⃣ Run the Application
node server.js


Open your browser and go to:

http://localhost:9100

🧪 Usage

Register a new user

Log in

Start chatting in real time

Messages are stored in MongoDB and persist across refreshes

🧹 Known Warnings (Non-Breaking)

Duplicate MongoDB index warning (safe, can be optimized)

Deprecated Mongoose options (can be removed safely)

These do not affect functionality.

🔒 Security Notes

Passwords are hashed using bcrypt

Sessions are secured using cookies

Sensitive data is stored in environment variables

📌 Future Improvements

Multiple chat rooms

Typing indicators

Online user list

MongoDB Atlas support

Improved UI / mobile responsiveness

JWT authentication

👨‍💻 Author

Faroq

GitHub: https://github.com/faroq45

📄 License

This project is licensed under the MIT License.
