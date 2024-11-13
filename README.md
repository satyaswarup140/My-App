# Todo Web App

This is a full-stack Todo web application that allows users to manage daily tasks, including creating, updating, and deleting tasks. The application includes user authentication, profile management, and task status updates.

## Project Structure

/todo-web-app ├── /client (ReactJS frontend) │ ├── /public │ ├── /src │ │ ├── /components │ │ ├── /context │ ├── App.js │ ├── index.js ├── /server (Node.js backend) │ ├── /controllers │ ├── /models │ ├── /routes │ ├── /middleware │ ├── /config │ ├── server.js ├── .env ├── package.json └── README.md


## Installation

### 1. Clone the Repository
    ```bash
    git clone <repository-url>
    cd todo-web-app

    2. Set Up Backend (Server)
       cd server
       npm install
    3. Set Up Frontend 
       cd ../client
       npm install

### Environment Variables
. Create a .env file in the root directory with the following variables:
  MONGO_URI=<your_mongo_db_connection_string>
  JWT_SECRET=<your_jwt_secret>
  PORT=5000

### Run the Application
. Start the backend server:
  cd server
  node server.js

. Start the frontend:
  npm start 

### Features
. User Authentication (Sign up, login)
. Task Management (CRUD operations)
. Profile Management

### Technologies Used
. Frontend: ReactJS
. Backend: Node.js, Express
. Database: MongoDB
. Authentication: JWT

### Deployment
This section has moved here: my-7wdzdizby-satyaswarup140s-projects.vercel.app
