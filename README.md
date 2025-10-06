# 📝 TaskApp – MERN Stack To-Do List

A simple and intuitive task management application built with the MERN stack (MongoDB, Express, React, Node.js). This full-stack app allows users to create, read, update, and delete tasks through a clean, component-based frontend and a robust RESTful API.

---

## 📌 Project Overview

**Tech Stack:**
* **Frontend:** React.js, Axios
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (with Mongoose)
* **Core Functionality:** The application implements full CRUD (Create, Read, Update, Delete) operations for managing tasks.

**Developer:** Honoured OneByte

---

## ✨ Features

* **Create Tasks:** Add new tasks with a title and an optional description.
* **View All Tasks:** See a real-time, organized list of all current tasks.
* **Mark as Complete:** Toggle the completion status of any task with a single click.
* **Delete Tasks:** Remove tasks that are no longer needed.
* **RESTful API:** A well-structured backend API to handle all task-related logic and database interactions.
* **Component-Based UI:** A clean and maintainable frontend built with reusable React components.

---

## 🚦 API Endpoints

The backend server provides the following endpoints to manage tasks:

| Method | Route             | Description                               |
| :----- | :---------------- | :---------------------------------------- |
| `GET`  | `/api/tasks`      | Fetches all tasks from the database.      |
| `POST` | `/api/tasks`      | Creates a new task.                       |
| `PUT`  | `/api/tasks/:id`  | Updates an existing task (e.g., marks it as complete). |
| `DELETE`| `/api/tasks/:id` | Deletes a specific task.                  |

---

## 🛠️ Installation & Setup

To run this project locally, you will need to set up both the backend and frontend servers.

### Prerequisites
* Node.js & npm
* MongoDB (local installation or a cloud instance like MongoDB Atlas)
* Git

### Steps

**1. Clone the repository:**
```bash
git clone [https://github.com/Honoured-1-byte/TaskApp.git](https://github.com/Honoured-1-byte/TaskApp.git)
cd TaskApp
