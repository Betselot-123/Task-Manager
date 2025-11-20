# Task Manager App - Technology Documentation

## Project Overview
A full-stack web application for managing tasks with real-time database operations.

## Technology Stack

### Frontend
- **HTML5** - Page structure and semantics
- **CSS3** - Styling with modern features (gradients, animations, flexbox)
- **JavaScript (ES6+)** - Client-side logic and API communication
- **Fetch API** - For HTTP requests to backend

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **SQLite3** - Database for data persistence
- **RESTful API** - Standard API architecture

### Development Tools
- **npm** - Package management
- **Git** - Version control

## Project Structure
task-manager/
├── server.js # Express backend server
├── package.json # Dependencies and scripts
├── DOCUMENTATION.md # This file
└── public/ # Frontend files
├── index.html # Main page
├── style.css # Styling
└── script.js # Frontend logic

## API Endpoints
- `GET /api/tasks` - Fetch all tasks
- `POST /api/tasks` - Create new task  
- `PUT /api/tasks/:id` - Update task status
- `DELETE /api/tasks/:id` - Delete task

## Setup Instructions
1. Clone repository
2. Run `npm install`
3. Run `npm start`
4. Visit `http://localhost:3000`