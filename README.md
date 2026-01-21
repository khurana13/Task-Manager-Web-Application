## Task Manager Web Application

A simple task manager built using Node.js, Express, and EJS that stores tasks as text files on the server.

This is a simple task manager web application built using Node.js, Express, and EJS. The application allows users to create tasks, view task details, and rename task files. All tasks are stored as text files on the server using Node’s file system module.

This project was created to practice backend development concepts and server-side rendering.

---

## Features

- Create new tasks with title and description  
- View task content on a separate page  
- Rename existing task files  
- Clean and minimal user interface  
- No database used (file-based storage)

---

## Technologies Used

- Node.js  
- Express.js  
- EJS (Embedded JavaScript Templates)  
- File System (fs module)  
- Tailwind CSS (via CDN)

---

## Project Structure

task-manager/
│
├── files/ # Stores task text files
├── views/ # EJS templates
│ ├── index.ejs
│ ├── show.ejs
│ └── edit.ejs
│
├── public/ # Static files (optional)
├── index.js # Main server file
├── package.json
├── README.md
└── .gitignore

yaml
Copy code

---

## How to Run the Project

1. Clone the repository  

2. Install dependencies  
   ```bash
   npm install
Start the server

bash
Copy code
npm start
Open your browser and visit

arduino
Copy code
http://localhost:3000
Learning Outcome
Understanding Express routing

Working with EJS templates

Handling files using Node.js

Passing data from backend to frontend

Structuring a basic Node.js project

Author
Sneha Khurana
B.Tech Student | Learning Full Stack DevelopmentDevelopment
