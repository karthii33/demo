# Full-Stack Contact App

A modern, minimal, corporate-style full-stack application built with React, Node.js, Express, and MongoDB.

## Tech Stack
- **Frontend**: React (Vite), Tailwind CSS v4, React Router DOM, Axios, React Toastify, Lucide React (Icons).
- **Backend**: Node.js, Express, Mongoose, CORS, Dotenv.
- **Database**: MongoDB

## Prerequisites
- Node.js installed
- MongoDB running locally (or you can update `backend/.env` with your MongoDB Atlas URI)

## Setup Instructions

### 1. Backend Setup
1. Open a terminal and navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the backend development server:
   ```bash
   npm run dev
   ```
   *(The server will run on `http://localhost:5000` by default)*

### 2. Frontend Setup
1. Open a new terminal and navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the Vite development server:
   ```bash
   npm run dev
   ```
   *(The app will be available at `http://localhost:5173` or similar, check your terminal output)*

## Features Included

### Contact Form (`/`)
- Modern, clean corporate UI
- Full form validation (required fields, proper email format validation)
- Loading state spinner on submit
- Toast notifications (success/error messages)
- Axios POST request to backend
- Clears form fields after successful submission

### Admin Dashboard (`/dashboard`)
- Beautiful, responsive table layout displaying submissions
- Fetches and displays all contacts via GET request
- Loading state while fetching data
- Export to CSV functionality
- Search/filter functionality by name, email, or subject
- Delete functionality for individual contacts (with confirmation dialog)
