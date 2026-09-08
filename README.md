## 🏛️ AcadNexus Pro — University Academic Management System

> **A centralized, secure, and role-based university academic management platform connecting administrators, departments, faculty, and students through one unified digital ecosystem for managing academic operations, learning resources, assessments, submissions, communication, and student performance.**

---

### 🚀 Project Overview

- **AcadNexus Pro** is a full-stack University Academic Management System designed to centralize and simplify academic operations within a university environment. The platform provides a unified digital ecosystem where administrators, departments, faculty members, and students can manage and access academic information according to their respective roles and responsibilities.

- The system brings together essential academic activities such as department and academic structure management, faculty and student management, subjects, assignments, practical/lab activities, quizzes, learning materials, announcements, polls, submissions, academic records, and performance analytics.

- By combining **role-based access control, centralized academic data, targeted content delivery, secure authentication, and interactive dashboards**, AcadNexus Pro reduces fragmented academic workflows and provides a more organized, transparent, and efficient way to manage university-level academic activities.


### 👥 User Roles

- 🛡️ **Super Admin** — Institution-level management
- 🏢 **Department Admin** — Department-level management
- 👨‍🏫 **Faculty** — Teaching and academic activities
- 🎓 **Student** — Academic learning and submissions

---
## 🛠️ Technology Stack

### 🎨 Frontend

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,ts,vite,tailwind&perline=4" alt="Frontend Technologies"/>
</p>

<p align="center">
  <b>React</b> • <b>TypeScript</b> • <b>Vite</b> • <b>Tailwind CSS</b>
</p>

---

### ☁️ Backend & Database

<p align="center">
  <img src="https://skillicons.dev/icons?i=supabase" width="48" alt="Supabase"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://skillicons.dev/icons?i=postgres" width="48" alt="PostgreSQL"/>
</p>

<p align="center">
  <b>Supabase</b>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <b>PostgreSQL</b>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <b>REST API</b>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <b>Row Level Security</b>
</p>

---

### 🧩 Frameworks & Libraries

<p align="center">
  <img src="https://cdn.simpleicons.org/reactrouter/CA4245" width="45" alt="React Router"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/lucide/F56565" width="45" alt="Lucide React"/>
</p>

<p align="center">
  <b>React Router</b>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <b>Recharts</b>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <b>Lucide React</b>
</p>

---

### 🧰 Development & Version Control

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github&perline=2" alt="Development Technologies"/>
</p>

<p align="center">
  <b>Git</b> • <b>GitHub</b>
</p>

---

## 🚀 Live Website

> **https://acadnexus-rc.vercel.app/**

---


## 🧩 Core Components

- 🔐 Authentication & Authorization
- 🛡️ Super Admin Management
- 🏢 Department Management
- 👨‍🏫 Faculty Management
- 🎓 Student Management
- 📚 Subject Management
- 📝 Assignment Management
- 🧪 Laboratory & Practical Tasks
- 📤 Digital Submissions
- 📊 Polls & Surveys
- 📢 Announcements
- 🎥 Learning Materials & Videos
- 📈 Academic Analytics

---


## 🏗️ System Architecture

```text
                 ┌───────────────────────┐
                 │        USERS          │
                 │                       │
                 │   Super Admin         │
                 │   Department Admin    │
                 │   Faculty             │
                 │   Student             │
                 └───────────┬───────────┘
                             │
                             ▼
                 ┌───────────────────────┐
                 │    REACT FRONTEND     │
                 │                       │
                 │  TypeScript + Vite    │
                 │  Tailwind CSS         │
                 └───────────┬───────────┘
                             │
                             ▼
                 ┌───────────────────────┐
                 │       SUPABASE        │
                 │                       │
                 │  Authentication       │
                 │  Backend Services     │
                 │  REST API             │
                 │  Database Access      │
                 └───────────┬───────────┘
                             │
                             ▼
                 ┌───────────────────────┐
                 │      POSTGRESQL       │
                 │                       │
                 │  Profiles             │
                 │  Departments          │
                 │  Academic Years       │
                 │  Semesters            │
                 │  Sections             │
                 │  Subjects             │
                 │  Assignments          │
                 │  Submissions          │
                 │  Polls                │
                 │  Announcements        │
                 │  Resources            │
                 └───────────────────────┘
```

---

## 🔄 Application Workflow

```text
                 User Opens AcadNexus Pro
                           │
                           ▼
                    🔐 Authentication
                           │
                           ▼
                     🛡️ Identify Role
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
     Super Admin     Department Admin   Faculty / Student
          │                │                │
          ▼                ▼                ▼
     Institution       Department        Academic
     Management        Management         Workspace
          │                │                │
          └────────────────┼────────────────┘
                           ▼
                  📚 Academic Activities
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
     📝 Assignments    🧪 Lab Tasks     🎥 Resources
          │                │                │
          ▼                ▼                ▼
     📤 Submissions   📤 Submissions    📖 Learning
                                          Materials
          │                │                │
          └────────────────┼────────────────┘
                           ▼
                    📊 Academic Data
                           │
                           ▼
                       📈 Analytics
```

---



---

## 🔐 Security

- 🔐 Supabase Authentication
- 🛡️ Role-Based Access Control
- 🔒 PostgreSQL Row Level Security
- 🎯 Academic-context-based access
- 🔑 Least-privilege permissions
- 🛡️ Protected application routes
- 🌐 Secure environment variables

---

## 📊 Academic Analytics

AcadNexus Pro provides role-based academic insights including:

- 👥 User activity
- 📝 Assignment activity
- 📤 Submission information
- 📊 Poll participation
- 📢 Announcement activity
- 🎥 Resource activity
- 📈 Academic trends
- 📋 Activity summaries

---

## 📂 Project Structure

```text
AcadNexus-Pro/
│
├── public/
│   └── images/
│
├── src/
│   ├── components/
│   ├── contexts/
│   │   └── AuthContext.tsx
│   ├── pages/
│   │   ├── auth/
│   │   ├── admin/
│   │   ├── department/
│   │   ├── faculty/
│   │   └── student/
│   ├── services/
│   │   └── supabase/
│   ├── types/
│   ├── lib/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
│
├── supabase/
│   └── migrations/
│
├── .env.example
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

---

## ⚙️ Installation

```bash
git clone https://github.com/YOUR_USERNAME/AcadNexus-Pro.git
cd AcadNexus-Pro
npm install
```

Create `.env`:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

Run the application:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

---

## 🎯 Project Focus

```text
University
     │
     ▼
Academic Management
     │
     ├── Administration
     ├── Faculty
     ├── Students
     ├── Subjects
     ├── Assignments
     ├── Practical Tasks
     ├── Submissions
     ├── Announcements
     ├── Learning Resources
     ├── Polls
     └── Analytics
```

> **AcadNexus Pro — Centralize Academics. Simplify Management. Empower Learning.**

---

<p align="center">

**Built with ❤️ using React • TypeScript • Vite • Tailwind CSS • Supabase • PostgreSQL**

**© 2026 Chadarasipalli Ramcharan — AcadNexus Pro**

</p>
