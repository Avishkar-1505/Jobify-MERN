
# Jobify

Jobify is a job application management tool built using the MERN (MongoDB, Express.js, React, Node.js) stack. It allows users to track their job applications, manage contacts, and keep notes on their job search process. This README file provides an overview of the project, installation steps, and usage instructions.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)

## Features
- **User Authentication**: Sign up, log in, and log out with JWT authentication.
- **Job Tracking**: Add, edit, delete, and view job applications.
- **Contact Management**: Keep track of contacts related to job applications.
- **Notes**: Add notes for each job application.
- **Responsive Design**: Fully responsive for both desktop and mobile devices.

## Tech Stack
- **Frontend**: React.js, Redux
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)

## Installation
### Prerequisites
Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine.
- MongoDB installed and running.

### Clone The Repository
`git clone https://github.com/Avishkar-1505/Jobify-MERN.git` 

`cd Jobify-MERN`
### Setup
1. Install dependencies
`npm install`

2. Create a .env file add the following environment variables:
`MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret`

3. Start the server:
`npm start`

## Usage

1. Open your browser and go to http://localhost:3000.
2. Sign up for a new account or log in if you already have one.
3. Start adding, editing, and managing your job applications, contacts, and notes.
