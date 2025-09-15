# 🎓 UniTrack: A Student Management Application

**UniTrack** is a full-stack web application designed to manage university academic operations. Built using modern technologies like **React**, **Next.js**, **Prisma**, and **NextAuth**, it provides a secure, role-based platform for students, instructors, and administrators.

---

## 📌 Table of Contents

- [🔑 Demo Access](#-demo-access)
- [🚀 Features](#-features)
- [🛠️ Tech Stack](#-tech-stack)
- [📊 Analytics Dashboard](#-analytics-dashboard)
- [📄 License](#-license)

---

## 🔑 Demo Access

🔗 **Live Demo:** [https://unitrack-eight.vercel.app](https://unitrack-eight.vercel.app)

For demonstration purposes, you can use the following credentials to test each user role:

| Role         | Email                   | Password   |
|--------------|--------------------------|------------|
| **Student**   | `john.doe@qu.com`        | `john123`  |
| **Instructor**| `jane.doe@qu.com`        | `jane123`  |
| **Admin**     | `admin@qu.com`       | `admin123` |

Each role grants unique access to different features of the platform.

---

## 🚀 Features

### 👩‍🎓 Student Portal
- Secure login using **NextAuth**
- Browse and search available courses by name or category
- Register for courses with **prerequisite** and **seat limit validation**
- View enrolled courses and academic progress
- Track learning path: Completed, In Progress, Pending
- View grades for completed courses
- Recommended course suggestions based on study plan

### 👨‍🏫 Instructor Portal
- View assigned classes and enrolled students
- Submit grades securely for each student
- Monitor academic performance and class progress

### 🧑‍💼 Admin Panel
- Create new courses and schedule class sections
- Assign instructors to specific classes
- Approve or reject new class creation requests
- Generate and view weekly course/class schedules
- View user and registration data

---

## 📊 Analytics Dashboard

Real-time metrics to track academic performance:

- 🎓 Top-performing students of the semester
- 📚 Top 3 most enrolled courses
- ❌ Failure rates per course
- 📈 Course popularity trends
- 🧮 Credit hour distribution
- 🕒 Class registration patterns
- 🔄 Drop/add rates per course
- ⚖️ Gender-based academic stats
- ⏱️ Course fill-time analytics
- 💡 10+ additional interactive charts

---

## 🛠️ Tech Stack

| Frontend        | Backend & DB         | Authentication | Styling       | ORM      |
|----------------|----------------------|----------------|---------------|----------|
| React, Next.js | Next.js API Routes   | NextAuth       | CSS Modules   | Prisma   |
| HTML, JSX      | Server Actions       |                |               | PostGres |

---

## 📄 License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

You are free to:

- ✅ **Use** the code for any purpose.
- 🔍 **Study** how the code works and modify it.
- 🔗 **Share** the original or your modified versions.
- 🛠️ **Adapt** the project and distribute under the same license.

You **must**:

- 🧾 **Disclose source** code if distributing.
- 🪪 **Apply GPL-3.0** license to any derivative works.
- 📝 **State all changes** made from the original.

> ⚠️ This project is provided **as-is**, **without warranty**, and does **not grant any trademark rights**.

For more details, see the [full license text here](https://www.gnu.org/licenses/gpl-3.0.en.html).


