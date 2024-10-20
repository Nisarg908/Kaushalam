# Todo List Application (MERN Stack)

A full-stack Todo List application built with the MERN stack (MongoDB, Express, React, Node.js). This application allows users to add, edit, delete, and display todo tasks with a deadline and status.

## Features

- Add new tasks with a deadline and status.
- Display the list of tasks.
- Edit existing tasks.
- Delete tasks.

## Project Structure

```bash
Todo-List/
│
├── backend/
│   ├── model/
│   │   └── todoList.js    # Mongoose schema for the Todo list
│   └── server.js          # Backend API and server logic
│
└── frontend/
    ├── public/
    ├── src/
    │   ├── App.js         # React app entry point
    │   └── Todo.js        # Main React component for the Todo List
    └── package.json       # Frontend dependencies
```

## Installation

### Step 1: Clone the repository

```bash
git clone <repository-url>
cd Todo-List
```

### Step 2: Set up the backend

1. Navigate to the `backend` folder:

    ```bash
    cd backend
    ```

2. Install the required dependencies:

    ```bash
    npm install
    ```

3. Set up MongoDB by replacing the MongoDB connection URL in `server.js` with your MongoDB URL.

4. Start the backend server:

    ```bash
    npm start
    ```

   The backend server will run on `http://localhost:3001`.

### Step 3: Set up the frontend

1. Navigate to the `frontend` folder:

    ```bash
    cd ../frontend
    ```

2. Install the required dependencies:

    ```bash
    npm install
    ```

3. Start the frontend server:

    ```bash
    npm start
    ```

   The frontend server will run on `http://localhost:3000`.

### Step 4: Open the app

1. Once both the backend and frontend servers are running, open your browser and visit:

    - Frontend: [http://localhost:3000/](http://localhost:3000/)
    - Backend (API): [http://localhost:3001/](http://localhost:3001/)

## Backend API Endpoints

- **`GET /getTodoList`**: Fetches all tasks from the database.
- **`POST /addTodoList`**: Adds a new task to the database.
- **`POST /updateTodoList/:id`**: Updates an existing task based on the provided ID.
- **`DELETE /deleteTodoList/:id`**: Deletes a specific task based on the provided ID.

## Frontend

- `App.js`: Routes to the Todo component.
- `Todo.js`: Handles displaying, adding, editing, and deleting tasks from the Todo list.

## Conclusion

This project is a great starting point for learning full-stack development with the MERN stack. Follow the above instructions to download, run, and modify the application for your learning or projects.

Enjoy coding!