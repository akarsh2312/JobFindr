# JobFindr - Full Stack Job Portal

JobFindr is a full-stack job portal application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application allows job seekers to search for jobs, apply for positions, and manage their profiles. It also includes features like job posting for recruiters, resume uploading, and secure user authentication.

## Features

- **Job Seeker:**
  - Search and filter jobs.
  - Apply for jobs.
  - Upload resumes and manage profiles.
  
- **Recruiter:**
  - Post job openings.
  - Manage job applications.
  - View and manage resumes.

- **Authentication:**
  - Secure user authentication using JWT.
  - Role-based access for job seekers and recruiters.

- **Error Tracking:**
  - Integrated Sentry for error monitoring and performance tracking.

## Technologies Used

- **Frontend:** React.js, React Router, Redux
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT, Clerk
- **Error Tracking:** Sentry
- **Hosting:** Vercel (Frontend), AWS (Backend)

## Installation

### Prerequisites

- Node.js (>= 14.x)
- npm (>= 6.x)
- MongoDB (local or MongoDB Atlas)

### Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Maclinz/JobFindr.git

2. Navigate to the project directory:
   ```bash
    cd JobFindr

3. Install backend dependencies:
   ```bash
    cd backend
    npm install

4.Install frontend dependencies:
   ```bash
    cd frontend
    npm install

5.Set up your environment variables:
   ```bash
    Create a .env file in the backend directory.
    Add the necessary MongoDB URI and JWT secret key.

6. Start the backend server:
   ```bash
    cd backend
    npm start
    
7. Start the frontend development server:
   ```bash
    cd frontend
    npm start
    Open the app in your browser at http://localhost:3000.

Deployment
The frontend is deployed on Vercel and can be accessed live at: https://jobfinder-lac.vercel.app/findwork

