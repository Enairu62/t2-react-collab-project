# PERN Stack Project

This project is a full-stack application built with the PERN (PostgreSQL, Express, React, Node.js) stack.

## Project Structure

- `frontend/`: Contains the React application.
- `backend/`: Contains the Node.js and Express server.

## Getting Started

### Prerequisites

- Node.js
- PostgreSQL

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Enairu62/t2-react-collab-project.git
   cd t2-react-collab-project
   ```

2. **Install backend dependencies:**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies:**
   ```bash
   cd ../frontend
   npm install
   ```

### Configuration

1. **Set up the database:**
   - Make sure you have PostgreSQL installed and running.
   - Create a new database.
   - Open `backend/db.js` and update the configuration with your database credentials:
     ```javascript
     const pool = new Pool({
       user: 'your_username',
       password: 'your_password',
       host: 'localhost',
       port: 5432,
       database: 'your_database'
     });
     ```

### Running the Application

1. **Start the backend server:**
   ```bash
   cd backend
   npm start
   ```
   The server will be running on `http://localhost:5000`.

2. **Start the frontend development server:**
   ```bash
   cd frontend
   npm start
   ```
   The React app will be running on `http://localhost:3000`.
