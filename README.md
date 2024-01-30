Overview
This project is a web application featuring user authentication functionalities using React, Node.js, and MySQL. Users can securely sign up, store credentials in a MySQL database, and subsequently log in using their registered email and password.

Technologies Used
Frontend: React
Backend: Node.js, Express
Database: MySQL
Communication: Axios


Installation
To run this project locally, follow these steps:

Clone the repository to your local machine:

But in the frontend folder, I didn't add the node modules. 
Please check the necessary modules and dependencies before you start and use the command 'npm install' to install the modules inside your frontend folder.
I mentioned it below once again. Please refer to 'npm install' to understand it clearly.

git clone <repository-url>

Navigate to the project directory:

cd <project-directory>

Install dependencies for both frontend and backend:

cd frontend
npm install
cd ../backend
npm install

Create a MySQL database and configure the connection details in the backend code.

Usage
To start the development server, follow these steps:

Start the backend server:

cd backend
npm start
Start the frontend server:
cd frontend
npm start

The application will be running on http://localhost:3000 by default.

Features
User signup and login
Data validation and security measures
Robust authentication system
