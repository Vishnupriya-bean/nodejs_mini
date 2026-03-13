# Node.js Todo App with SQLite

A simple todo application built with Node.js, Express, and SQLite.

## Features

- Add new todos
- Mark todos as completed
- Delete todos
- Persistent storage with SQLite

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

Start the server:
```bash
npm start
```

Open your browser and navigate to `http://localhost:3000`

## API Endpoints

- `GET /api/todos` - Get all todos
- `POST /api/todos` - Create a new todo (body: `{ "title": "Todo title" }`)
- `PUT /api/todos/:id` - Update a todo (body: `{ "title": "New title", "completed": true }`)
- `DELETE /api/todos/:id` - Delete a todo

## Technologies Used

- Node.js
- Express.js
- SQLite3
- Vanilla JavaScript (Frontend)