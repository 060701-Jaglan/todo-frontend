# To-Do List Application

This repository provides the full-stack implementation of a To-Do List application. The backend is built using **Node.js, Express, and MongoDB**, while the frontend is built with **React.js**. Together, they offer a complete solution to manage to-do tasks.

---

## Features

- **Backend**: RESTful API for managing to-do items.
- **Frontend**: User-friendly interface to interact with the API.
- **CRUD Operations**: Create, read, update, and delete to-do items.
- **MongoDB**: Used for persistent storage.

---

## Prerequisites

Ensure the following are installed on your system:

1. **Node.js** (v16+ recommended)  
   [Download Node.js](https://nodejs.org/)

2. **npm** (comes with Node.js) or **yarn**  
   [Download Yarn](https://yarnpkg.com/)

3. **MongoDB**  
   Install and start MongoDB on your machine or use a cloud-based MongoDB service like [MongoDB Atlas](https://www.mongodb.com/atlas).

---

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

---

URLS:
- https://todo-frontend-ro3o5k1ut-himanshus-projects-4a38f295.vercel.app
- https://node-todo-backend-kf9s.onrender.com/api/v1/
