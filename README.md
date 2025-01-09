# To-Do List Application
> Backend Link: https://github.com/060701-Jaglan/todo-backend

This repository provides the full-stack implementation of a To-Do List application. The backend is built using **Node.js, Express, and MongoDB**, while the frontend is built with **React.js**. Together, they offer a complete solution to manage to-do tasks.

---

## Features

- **Backend**: RESTful API for managing to-do items.
- **Frontend**: User-friendly interface to interact with the API.
- **CRUD Operations**: Create, read, update, and delete to-do items.
- **MongoDB**: Used for persistent storage.

## Backend Setup

The backend handles the API and database operations for the To-Do List application. Follow these steps to set it up:

Set Up Environment Variables: Create a `config.env` file in the data directory of the backend project

Start the Backend Server

`npm install && npm run start`

---

## Frontend Setup

The frontend provides the user interface for interacting with the To-Do List application. Follow these steps to set it up:

Set Up Environment Variables

Create a `.env` file in the root directory of the frontend project

Start the Frontend Development Server

⁠`npm install && npm run start`

## API Endpoints (Backend)

| Method | Endpoint          | Description              |
|--------|-------------------|--------------------------|
| GET    | `/myTasks`      | Get all to-do items      |
| POST   | `/new`      | Add a new to-do item     |
| PUT    | `/:id`  | Update a to-do item      |

There are also authenication endpoints (which are done as an additional aspect)
---

URLS:
- https://react-todo-app-nine-sage.vercel.app/login
- https://node-todo-backend-kf9s.onrender.com/api/v1/
