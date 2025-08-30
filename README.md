<div align="center">
  <h1>📊 Subscription Tracker API</h1>
  <p>A production-ready API to manage user subscriptions, reminders, and notifications.</p>
</div>

---

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)  
2. ⚙️ [Tech Stack](#tech-stack)  
3. 🔋 [Features](#features)  
4. 🤸 [Quick Start](#quick-start)  
5. 🕸️ [Snippets](#snippets)  
6. 🚀 [Future Improvements](#future-improvements)  
7. 👤 [Author](#author)

---

## 🤖 Introduction

This is a **Subscription Management System API** built with **Node.js, Express, and MongoDB**.  
It handles subscription tracking, authentication, email reminders, and structured API architecture for scalability.

---

## ⚙️ Tech Stack

- **Node.js** – Server runtime  
- **Express.js** – Backend framework  
- **MongoDB + Mongoose** – Database & ORM  
- **JWT** – Authentication  
- **Nodemailer** – Email notifications  

---

## 🔋 Features

- **User Authentication (JWT)** – Secure login & signup  
- **Subscription Management** – Create, update, delete, and track subscriptions  
- **Email Reminders** – Automated email notifications for renewals  
- **Error Handling** – Global error middleware  
- **Logging** – Debugging & monitoring  
- **Environment Config** – `.env` file support  

---

## 🤸 Quick Start

### Prerequisites
- [Git](https://git-scm.com/)  
- [Node.js](https://nodejs.org/)  
- [npm](https://www.npmjs.com/)  
- [MongoDB](https://www.mongodb.com/)

### Installation

```bash
# Clone the repository
git clone https://github.com/rafay0704/subscription-tracker-upstach-nodemailer.git
cd subscription-tracker-upstach-nodemailer



Set Up Environment Variables

Create a .env.local file in the root:

PORT=5500
NODE_ENV=development
DB_URI=mongodb://localhost:27017/subscription-tracker

JWT_SECRET=your-secret-key
JWT_EXPIRES_IN=1d

EMAIL_PASSWORD=your-email-password


# Install dependencies
npm install


Run the Project
npm run dev


Server runs at:
👉 http://localhost:5500


🚀 Future Improvements

Add role-based access (Admin, User)

Payment gateway integration

Analytics dashboard for subscriptions

Multi-language support

👤 Author

Abdul Rafay
