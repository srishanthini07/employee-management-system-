Employee Management System

Project Overview

A web-based Employee Management System to add, view, edit, delete, and search employee records.

Technologies Used

- Frontend: React.js, Vite, CSS
- Backend: Node.js, Express.js
- Database: MySQL
- API: REST API
- Deployment: Vercel (Frontend)

Features

- View all employees
- Add new employees
- Edit employee details
- Delete employee records
- Search employees by name
- Email validation

Setup Instructions

1. Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_LINK
cd employee-management

2. Install Frontend Dependencies

npm install

3. Install Backend Dependencies

cd Backend
npm install

4. Configure Environment Variables

Create a ".env" file inside the Backend folder:

DB_HOST=localhost
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_NAME=employee_management
PORT=5000

5. Start Backend

node server.js

6. Start Frontend

Open another terminal in the project root:

npm run dev

Open the local URL shown in the terminal.

Database

Create a MySQL database named "employee_management" and configure the required employees table.

Project Status

Employee Management System – Full Stack Web Application
