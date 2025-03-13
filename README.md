# Employee Records Management System

This is a MERN (MongoDB, Express, React, Node.js) stack application for managing employee records. It allows you to add, update, delete, and view employee information.

## Features
- Add new employee records
- Update existing employee records
- Delete employee records
- View a list of all employees

## Prerequisites
Make sure you have the following installed on your machine:
- Node.js
- npm (Node Package Manager)
- MongoDB Atlas account

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sanjograiofficial/mern-stack

  note: make sure to change the url of all the fetch requests on client directory on 'Record.jsx' and 'RecordList.jsx' to your server's localhost.

1. Install the dependencies for both the client and server:
  ```bash
  cd client
  npm install
  cd ../server
  npm install
  ```
3. Create a MongoDB Atlas account and set up a new cluster. Get your MongoDB connection string.

4. Create a config.env file in the server directory and add the following content:
  ```bash
  ATLAS_URI=mongodb+srv://<username>:<password>@<cluster>.<projectId>.mongodb.net/employees?retryWrites=true&w=majority
  PORT=5050
  ```
5. Start the development server:
  ```bash
  cd server
  node --env-file=config.env server
  cd ../client
  npm run dev
  ```
Contributing
Feel free to contribute by opening a pull request. For major changes, please open an issue first to discuss what you would like to change.

License
This project is licensed under the MIT License.


I hope this helps! If you need any more details or have any questions, just let me know.
