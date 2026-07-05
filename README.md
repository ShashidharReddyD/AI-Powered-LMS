# 🎓 AI-Powered Learning Management System (LMS)

An AI-powered Learning Management System designed to simplify academic management between administrators and students. The system provides separate portals for Admin and Student users, enabling efficient management of attendance, assignments, educational resources, and AI-assisted learning.

---

## 📌 Project Overview

Managing academic activities manually can be time-consuming and inefficient. This project provides a centralized platform where administrators can manage students and academic resources, while students can easily access their learning materials and interact with an AI-powered chatbot.

---

## 🚀 Features

### 👨‍💼 Admin Portal

- Secure Admin Login
- Student Management
- Attendance Management
- Assignment Management
- Educational Video Management
- Timetable Management
- Dashboard Overview

### 👨‍🎓 Student Portal

- Secure Student Login
- View Attendance
- View Assignments
- Submit Assignments
- View Educational Videos
- View Timetable
- AI-powered Academic Chatbot

---

## 🤖 AI Chatbot

The project integrates the Gemini API to provide AI-assisted learning support.

Students can:

- Ask academic questions
- Receive instant AI-generated responses
- Improve learning experience through interactive assistance

---

## 🛠️ Tech Stack

### Frontend

- HTML
- CSS
- JavaScript

### Database

- MySQL

### AI Integration

- Gemini API

---

## 🗂️ Database Modules

The system stores data using MySQL.

### Students

- Student ID
- Name
- Class
- Roll Number
- Email
- Password

### Admin

- Admin ID
- Username
- Password

### Attendance

- Attendance ID
- Student ID
- Date
- Status

### Assignments

- Assignment ID
- Title
- Description
- Class
- Deadline

### Assignment Submissions

- Submission ID
- Student ID
- Assignment ID
- Submission Date
- File Path

### Videos

- Video ID
- Title
- Subject
- Class
- YouTube Link

### Timetable

- Timetable ID
- Class
- Subject
- Teacher
- Day
- Time

---

## 🔄 System Workflow

### Admin

1. Login
2. Manage Students
3. Mark Attendance
4. Upload Assignments
5. Upload Videos
6. Update Timetable

### Student

1. Login
2. View Dashboard
3. Check Attendance
4. View Assignments
5. Submit Assignments
6. Watch Videos
7. Use AI Chatbot

---

## 🔐 Authentication

The application supports two user roles:

- Admin
- Student

After successful authentication, users are redirected to their respective dashboards based on their role.

---

## 📂 File Storage

Assignment files uploaded by students are stored on the server, while the file location is maintained in the MySQL database. This enables administrators to access submitted files efficiently.

---

## 🎥 Video Management

Administrators upload educational YouTube links, which are stored in the database. Students can access videos relevant to their class directly through the portal.

---

## 📊 Attendance Management

Administrators record attendance for each student. Attendance information is stored in the database and displayed to students in real time whenever they log in.

---

## 📚 Assignment Management

Administrators upload assignments with deadlines.

Students can:

- View assignments
- Submit completed work
- Track submission status

---

## 💡 Future Enhancements

- Spring Boot Backend
- JWT Authentication
- Parent Portal
- Notifications
- Student Performance Analytics
- Mobile Application
- Cloud Deployment
- Role-based Authorization
- Email Notifications

---

## 👨‍💻 My Contribution

- Led the project as Team Leader.
- Developed the frontend using HTML, CSS, and JavaScript.
- Implemented Attendance Management.
- Implemented Role-Based Authentication.
- Integrated the Gemini API chatbot.
- Coordinated module integration and testing.

---

## 📷 Screenshots

(Add project screenshots here)

---

## 📄 License

This project was developed for academic purposes.
