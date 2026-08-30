# Frontend Documentation

# 1. Project Overview

The frontend of the Digital Subsidy and Grant Administration Platform
is a web application developed using React and Vite.

It provides an easy-to-use interface for managing government subsidy
and grant-related activities.

# 2. Technologies Used

- React.js
- Vite
- JavaScript
- HTML5
- CSS3

# 3. Frontend Structure

The frontend contains the following main files and folders:

- `public/` – Contains public/static files.
- `src/` – Contains the main application source code.
- `App.jsx` – Main application component.
- `App.css` – Styling for the application.
- `main.jsx` – Entry point of the React application.
- `index.css` – Global CSS styles.
- `package.json` – Contains project dependencies and scripts.
- `vite.config.js` – Vite configuration file.

# 4. Main Features

The frontend provides interfaces for:

- User registration and login
- Beneficiary subsidy applications
- Application status tracking
- Officer verification
- Administrator approval
- Grant and subsidy management
- Disbursement tracking
- User-friendly dashboards

# 5. User Interface

The application provides different screens and dashboards based on
the user's role.

The interface allows users to submit information, view application
details, track status and perform authorized actions.

# 6. Frontend and Backend Communication

The React frontend communicates with the Spring Boot backend through
REST APIs.

The basic flow is:

Frontend (React)
       ↓
REST API
       ↓
Spring Boot Backend
       ↓
Database

The frontend sends requests to the backend and displays the received
data to the user.

# 7. Installation

To install the frontend dependencies:

```bash
npm install
