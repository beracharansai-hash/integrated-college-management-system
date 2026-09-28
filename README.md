<h1 align="center">
    SCHOOL MANAGEMENT SYSTEM
</h1>

<h3 align="center">
Streamline school management, class organization, and add students and faculty.<br>
Seamlessly track attendance, assess performance, and provide feedback. <br>
Access records, view marks, and communicate effortlessly.
</h3>

# About

The School Management System is a web-based application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It aims to streamline school management, class organization, and facilitate communication between students, teachers, and administrators.

## Features

- **User Roles:** The system supports three user roles: Admin, Teacher, and Student. Each role has specific functionalities and access levels.

- **Admin Dashboard:** Administrators can add new students and teachers, create classes and subjects, manage user accounts, and oversee system settings.

- **Attendance Tracking:** Teachers can easily take attendance for their classes, mark students as present or absent, and generate attendance reports.

- **Performance Assessment:** Teachers can assess students' performance by providing marks and feedback. Students can view their marks and track their progress over time.

- **Data Visualization:** Students can visualize their performance data through interactive charts and tables, helping them understand their academic performance at a glance.

- **Communication:** Users can communicate effortlessly through the system. Teachers can send messages to students and vice versa, promoting effective communication and collaboration.

## Technologies Used

- Frontend: React.js, Material UI, Redux
- Backend: Node.js, Express.js
- Database: MongoDB

<br>

# Installation
Open two terminals.

### Backend setup:

```
cd backend
npm install
```

Create a .env file in the backend folder. Add the following:

```
MONGO_URL = mongodb://127.0.0.1/smsproject

SECRET_KEY = 'secret123key'
```

Fill MONGO_URL using the instructions below. SECRET_KEY is any random string.

Start the backend:

```
npm start
```

### Frontend setup:

```
cd frontend
npm install
```

Create a .env file in the frontend folder and add:

```
REACT_APP_BASE_URL=http://localhost:5000
```

If a .env file already exists and the line is commented out, remove the comment.

```
npm start
```

Frontend runs at localhost:3000. Backend runs at localhost:5000.
