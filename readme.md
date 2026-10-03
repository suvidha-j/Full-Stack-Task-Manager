# Student Task Manager

## 1. Product Idea

Student Task Manager is a simple full-stack web application that helps students create, manage, update, and delete their daily tasks.

### Main Features
- Add a new task
- View all tasks
- Update task status
- Delete a task
- Mark tasks as completed
- Store task information in a database

---

## 2. Technology Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Version Control
- Git
- GitHub

---

## 3. System Architecture

The application follows a simple three-layer architecture:

User
↓
Frontend
↓
REST API / Backend
↓
Database

### Architecture Flow

1. User interacts with the frontend.
2. Frontend sends HTTP requests to the backend API.
3. Backend processes the request.
4. Backend reads or updates data in the database.
5. Backend sends a response to the frontend.
6. Frontend displays the result to the user.

---

## 4. Data Model

### Task

| Field | Type | Description |
|---|---|---|
| id | String | Unique task ID |
| title | String | Task title |
| description | String | Task details |
| status | String | Pending or Completed |
| priority | String | Low, Medium or High |
| dueDate | Date | Task deadline |
| createdAt | Date | Task creation date |

---

## 5. API Routes

### GET /api/tasks
Fetch all tasks.

### GET /api/tasks/:id
Fetch a single task by ID.

### POST /api/tasks
Create a new task.

### PUT /api/tasks/:id
Update an existing task.

### DELETE /api/tasks/:id
Delete a task.

---

## 6. Frontend Screens

### 1. Home / Dashboard
Displays all tasks and their status.

### 2. Add Task Screen
Allows the user to create a new task.

### 3. Task Details Screen
Displays complete information about a selected task.

### 4. Edit Task Screen
Allows the user to update task information.

### 5. About Screen
Provides basic information about the application.

---

## 7. Project Structure

```text
Full-Stack-Task-Manager/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── models/
│   └── controllers/
│
└── README.md