
# SocioBuddy - FullStack Social Media App

Build an COMPLETE Fullstack Responsive MERN App with Auth, Likes, Dark Mode | React, MongoDB, MUI

Key Features:
- Users can register, login, and logout securely using JSON Web Tokens (JWT).
- The app also comes with a login page that ensures authenticated access to protected routes.
- Users can post content and interact with it by liking and disliking posts, with the number of likes displayed.
- The mobile-first design ensures a seamless user experience on various devices.
- The app is powered by MongoDB for data storage and Express.js for the backend API, enabling efficient data management and retrieval.

What you need to run this code

    Node
    NPM
    MongoDB

Run Locally

Clone the project

  git clone https://github.com/Khushwant-Manglani

Go to client folder

    npm install

Go to server folder

    npm install

create .env file in server folder and write below content in it

MONGO_URL = 'change this to your mongodb url'
JWT_SECRET = 'secretkey'
PORT = 3001

change .env file in client folder and write below content in it

REACT_APP_SERVER_URL = 'http://localhost:3001'

Start the server

    Go to client folder

  npm start

    Go to server folder

  node index.js

Tech Stack

Client: React, Redux, JWT

Server: Node, Express

Database: MongoDb