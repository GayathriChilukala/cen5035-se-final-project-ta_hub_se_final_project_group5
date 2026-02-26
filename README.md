
# 🎓 TA Hub — Teaching Assistant Management Platform
 
### A Full-Stack Web Application for University TA Coordination

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![EJS](https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge&logo=ejs&logoColor=black)](https://ejs.co/)
[![Course](https://img.shields.io/badge/CEN5035-Software%20Engineering-blue?style=for-the-badge)](https://www.ufl.edu/)

**University of Florida · CEN5035 Software Engineering · Group 5**

[📹 Demo Video](https://youtu.be/d07az80pcLs) · [📂 Full Source Code](https://drive.google.com/file/d/1wrp66dh3AAnrQviezUJWutNzTJotyO8D/view?usp=sharing) · [📄 Setup Guide](https://drive.google.com/file/d/1aT05w8aNR7uBiX4uxU3Ssh-7P1zYaSMN/view?usp=sharing)

</div>

---

## 📌 Project Overview

**TA Hub** is a full-stack web application designed to streamline the management of Teaching Assistants (TAs) at the university level. The platform centralizes TA assignments, availability scheduling, and communication between instructors and TAs — replacing fragmented email threads and spreadsheets with a unified, role-aware digital hub.

Built as the **final project for CEN5035 (Software Engineering)** at the University of Florida, TA Hub was developed following professional software engineering practices including Agile sprints, requirements gathering, system design, implementation, and testing.

> **The Problem:** Managing TAs across multiple courses involves complex scheduling, role assignments, and communication — currently handled through disconnected tools that are error-prone and time-consuming.
>
> **The Solution:** A centralized web platform where administrators, instructors, and TAs each have role-specific dashboards to manage assignments, office hours, and course responsibilities efficiently.

---

## ✨ Key Features

**For Administrators**
- Create and manage TA profiles and course assignments
- Oversee all active TA-course pairings across departments
- Configure system-wide settings and user roles

**For Instructors**
- View TAs assigned to their courses
- Post and manage TA office hour schedules
- Coordinate grading and support responsibilities

**For Teaching Assistants**
- View assigned courses and responsibilities
- Manage and publish personal availability / office hours
- Access course-specific resources and communication

**Platform-Wide**
- Secure role-based authentication and authorization
- Responsive UI built with EJS templating
- Session management for persistent, secure logins
- Clean dashboard views tailored to each user role

---

## 🏗️ System Architecture

```
TA Hub
├── Frontend
│   ├── EJS Templates (server-side rendered views)
│   ├── CSS (styling and responsive layout)
│   └── Vanilla JavaScript (client-side interactions)
│
├── Backend
│   ├── Node.js runtime
│   ├── Express.js web framework
│   ├── RESTful routing (GET, POST, PUT, DELETE)
│   └── Session-based authentication & authorization
│
└── Data Layer
    ├── Structured data models for Users, Courses, Assignments
    └── Persistent storage (database / file-based)
```

---

## 📁 Repository Structure

```
cen5035-se-final-project/
├── TA_HUB/                          # Main application source
│   ├── routes/                      # Express route handlers
│   ├── views/                       # EJS templates (UI pages)
│   ├── public/                      # Static assets (CSS, JS, images)
│   ├── models/                      # Data models / schema definitions
│   ├── controllers/                 # Business logic layer
│   └── app.js / server.js           # Application entry point
├── Launching an application steps.pdf  # Detailed local setup guide
├── youtubeVideoLink.txt             # Demo video reference
└── README.md                        # This file
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Runtime** | Node.js |
| **Framework** | Express.js |
| **Templating** | EJS (Embedded JavaScript) |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Auth** | Session-based authentication |
| **Dev Tooling** | npm, nodemon |
| **Version Control** | Git & GitHub (via GitHub Classroom) |
| **Methodology** | Agile / Scrum with sprint-based delivery |

---

## 🚀 Getting Started

### Prerequisites

Ensure the following are installed on your machine:
- [Node.js](https://nodejs.org/) (v14 or higher)
- npm (bundled with Node.js)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/GayathriChilukala/cen5035-se-final-project-ta_hub_se_final_project_group5.git
cd cen5035-se-final-project-ta_hub_se_final_project_group5/TA_HUB

# 2. Install dependencies
npm install

# 3. Start the application
npm start
# or with auto-reload:
npx nodemon app.js

# 4. Open in your browser
# Navigate to: http://localhost:3000
```

> 📄 For detailed step-by-step setup instructions, refer to **[Launching an application steps.pdf](./Launching%20an%20application%20steps.pdf)** included in this repository.

---

## 📹 Demo

Watch the full application walkthrough on YouTube:
👉 **[https://youtu.be/d07az80pcLs](https://youtu.be/d07az80pcLs)**

The demo covers:
- User registration and role-based login
- Admin dashboard: TA assignment management
- Instructor view: TA schedules and course coordination
- TA view: availability management and course responsibilities

---

## 🔄 Software Engineering Process

This project was built using formal software engineering practices as part of CEN5035:

**Requirements Engineering** — User stories defined for Admin, Instructor, and TA roles with clear acceptance criteria

**System Design** — Architecture diagrams, ER diagrams, and UI wireframes created before implementation

**Agile Development** — Work divided into sprints with iterative feature delivery and peer code reviews

**Testing** — Functional testing across all user roles and edge cases; manual QA on all core flows

**Documentation** — Maintained throughout development including setup guide and demo video

---

## 🎯 Skills Demonstrated

This project showcases competencies central to **Full-Stack Software Engineering** and **Agile Team Development** roles:

- Full-stack JavaScript development (Node.js + Express + EJS)
- RESTful API design and implementation
- Role-based access control (RBAC) with session authentication
- Server-side rendering with dynamic templating (EJS)
- Collaborative development on GitHub with branching and version control
- Agile/Scrum methodology with sprint planning and delivery
- Software engineering lifecycle: requirements → design → implementation → testing
- Technical documentation and end-user setup guides

---

## 👥 Team

**Group 5 — CEN5035 Software Engineering, University of Florida**

| Member | GitHub |
|---|---|
| Gayathri Chilukala | [@GayathriChilukala](https://github.com/GayathriChilukala) |
| *(Add teammates here)* | |

---

## 📚 Course Context

| Detail | Info |
|---|---|
| **Course** | CEN5035 — Software Engineering |
| **University** | University of Florida |
| **Project Type** | Team Final Project |
| **Platform** | GitHub Classroom |
| **Deliverables** | Working app · Demo video · Setup documentation |

---

<div align="center">

*Built with ❤️ by Group 5 — University of Florida, CEN5035 Software Engineering*

</div>
