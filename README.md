# Finance App!

This is a full-stack finance management application developed as part of my **Database Management Systems (DBMS)** project. It simplifies financial tracking and reporting while showcasing integration between frontend and backend technologies.

## Features
- **Client (Frontend)**: A user-friendly interface for managing finances.
- **Server (Backend)**: Handles data storage, retrieval, and business logic.
- **Database Integration**: Efficiently manages financial data with a robust database backend.

## Tech Stack
### Frontend
- Framework: Vite with TypeScript
- Libraries: [Details from `client/package.json`]

### Backend
- Node.js with TypeScript
- Database: [Specify the database used, e.g., MySQL, PostgreSQL, MongoDB]

## Setup Instructions

### Prerequisites
- Node.js (v16 or above recommended)
- Yarn or npm
- Database server (e.g., MySQL)

### Steps
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd finance-app-main
2. Install dependencies:
   - Frontend:
     ```bash
     cd client
     yarn install
   - Backend:
     ```bash
     cd ../server
     yarn install
3. Configure the database:
   - Update the database connection settings in server/src/config (or similar) to match your database.
4. Run the application:
   - Start the backend server:
     ```bash
     cd server
     yarn start
   - Start the frontend:
     ```bash
     cd ../client
     yarn dev
5. Access the application: Open your browser and navigate to http://localhost:3000 (or the specified port).
