
# 🎓 Campus Connect Portal

> **RV University**

> *Repository:* [akshathabsc24-bit/Campus-connects](https://github.com/akshathabsc24-bit/Campus-connects)

---

## 📌 Project Overview

**Campus Connect** is an integrated academic management portal designed to connect students, faculty, and administrators onto a single digital platform. The project provides a modern web interface for viewing university highlights, accessing dedicated role portals, managing schedules and notices, and tracking academic attendance.

---

## 🚀 Key Features

### 1. Modern Responsive Landing Page (`client/index.html`)

- **Semantic HTML5 Structure:** Structured with `<header>`, `<nav>`, `<section>`, `<article>`, and `<footer>` elements.
- **Layouts with CSS Grid & Flexbox:**
  - Flexbox-driven navigation header, brand badges, and action buttons.
  - Responsive multi-column CSS Grid for Student, Faculty, and Admin portals.
- **Campus Life Carousel:** Interactive image carousel showcasing campus infrastructure and digital learning.
- **Micro-Interactions:** Hover elevation effects and drop shadows on portal cards and buttons.
- **Mobile Responsiveness:** Adaptive media queries for mobile, tablet, and desktop screens.

### 2. Student Authentication System (`client/login.html`)

- Dedicated RV University branded login and registration portal.
- Tab-switching interface between Student Login and Student Registration.
- Interactive notifications upon successful registration and login.
- Direct redirection to student dashboard features.

### 3. Student Performance & Attendance Portal (`client/attendance.html`)

- **Student Profile Summary:** Displays student academic details and enrollment status.
- **Batch Grade Evaluator:** Automated mark processing and grade calculation.
- **Interactive Attendance Tracker:** Counter functionality for tracking lecture attendance.
- **Announcement Dialogs:** Interactive notification and prompt boxes.

### 4. Interactive Notice & Task Board (`client/experiment3.html`)

- **Real-Time Input Reflection:** Live preview responding instantly to user typing.
- **Dynamic Content Management:** Add announcements and tasks dynamically.
- **Task Actions:** Remove items and toggle completed status.
- **Dark Mode Toggle:** Switch between light and dark themes.

### 5. Study & Task Planner (`client/experiment4.html`)

- **State-Driven Architecture:** User interface updates according to application state.
- **Task Filtering & Priorities:** Filter tasks by All, Pending, and Completed.
- **Priority Tags:** High, Medium, and Low priorities.
- **Local Persistence:** Saves tasks to `localStorage` across browser sessions.

### 6. Backend API Server (`server/`)

- Built with **Node.js** and **Express.js**.
- Modular routing architecture with authentication endpoints.
- MongoDB and Mongoose integration for data persistence.
- CORS-enabled communication between the frontend and backend.

---

## 🛠️ Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript (ES6+), React 19, Vite |
| **Backend** | Node.js, Express.js, CORS, Dotenv |
| **Database & Auth** | MongoDB, Mongoose, JWT, bcryptjs |
| **Version Control** | Git, GitHub |

---

## 📂 Project Structure

```text
Campus-connects/
├── README.md
├── package.json
├── client/
│   ├── index.html
│   ├── login.html
│   ├── attendance.html
│   ├── experiment3.html
│   ├── experiment3.js
│   ├── experiment4.html
│   ├── experiment4.js
│   ├── package.json
│   ├── src/
│   │   ├── style.css
│   │   ├── main.jsx
│   │   ├── App.jsx
│   │   ├── assets/
│   │   └── components/
│   │       ├── AuthModule.jsx
│   │       └── StudentPortal.jsx
│   └── public/
└── server/
    ├── package.json
    └── src/
        ├── app.js
        ├── config/
        │   └── db.js
        ├── models/
        │   └── User.js
        └── routes/
            └── authRoutes.js
```

---

## 💻 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/akshathabsc24-bit/Campus-connects.git
cd Campus-connects
```

### 2. Run the Frontend

You can open the HTML pages directly in your browser or use VS Code Live Server.

Available pages:

- **Home Page:** `client/index.html`
- **Login Portal:** `client/login.html`
- **Notice Board:** `client/experiment3.html`
- **Task Planner:** `client/experiment4.html`

Alternatively, run the development server:

```bash
cd client
npm install
npm run dev
```

### 3. Run the Backend Server

Open a new terminal and run:

```bash
cd server
npm install
node src/app.js
```

The server will start on:

```text
http://localhost:5000
```

---

## 📝 License

This project is licensed under the **ISC License**.