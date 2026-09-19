# Recipe-Repo
This repository is intended to be used to explain the devs the structure of a fullstack codebase

# Recipe Repo

Recipe Repo is a full-stack web application that is intended to be used to explain the devs the structure of a fullstack codebase. This is a codebase where chefs can create, edit, store, and share recipes with others.

## Technologies

### Frontend

- Next.js
- React
- TypeScript
- HTML
- CSS

### Backend

- Node.js
- Express
- TypeScript
- MongoDB

## Prerequisites

Make sure you have installed:

- Git
- Node.js
- npm
- VS Code
- WSL with Ubuntu if you use Windows

## Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd Recipe-Repo
code .
```

Replace `<repository-url>` with the repository’s SSH URL.

### 2. Install the frontend dependencies

```bash
cd frontend
npm install
```

### 3. Install the backend dependencies

Open a second terminal and run:

```bash
cd backend
npm install
```

## Environment Variables

Create a `.env` file inside the `backend` folder:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

Ask the project lead for the MongoDB connection string.

## Run the Application

### Start the backend

Inside the `backend` folder, run:

```bash
npm run dev
```

### Start the frontend

Inside the `frontend` folder, run:

```bash
npm run dev
```

Open the URL displayed in the frontend terminal. It will usually be:

```text
http://localhost:3000
```

## Stop the Application

Press `Ctrl + C` in each terminal.
