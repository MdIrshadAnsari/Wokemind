WokeMind is a full-stack web application that allows users to register, log in, create notes, edit notes, and delete notes.

It helps users make plans, store notes online, and access or change them anytime from anywhere.

Features :-

User Authentication :-
* Register a new account
* Login with email & password
* Logout securely
* JWT-based authentication
* Protected routes

Notes CRUD Operations :- 
* Create notes
* View all notes
* Edit notes (optional – if implemented)
* Delete notes
* Notes history section in dashboard

User Profile :-
* View user name & email
* Logout
* Clean and simple UI

Tech Stack :-

Frontend :- 
* React (Vite)
* Tailwind CSS
* Axios
* React Router

Backend :-
* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT
* bcrypt for password hashing

Installation & Setup :-
git clone https://github.com/your-username/wokemind.git
cd Wokemind

Backend Setup :-
* Install dependencies
cd backend 
npm install
* Add .env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
* Start server
npm run start


Frontend Setup :-
* Install dependencies
cd frontend 
npm install
* Start server
npm run dev