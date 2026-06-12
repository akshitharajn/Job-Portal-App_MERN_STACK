#  Job Portal Application using MERN Stack

A full-stack **Job Portal Application** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. This platform allows job seekers to search and apply for jobs while enabling employers to post job opportunities and manage applications efficiently.

The application is designed with secure authentication, scalable architecture, responsive UI, and smooth user interaction.

---

##  Features

### User Authentication

* Secure registration and login using **JWT (JSON Web Tokens)**
* Password encryption using **Bcrypt**

###  Job Listings

* Browse and search multiple job opportunities
* Dynamic data fetched from MongoDB

###  Application Management

* Job seekers can manage submitted applications
* Employers can review and manage candidate applications

###  Image Upload

* Integrated with **Cloudinary** for image storage and management

###  Responsive Design

* Optimized experience across desktop, tablet, and mobile devices

---

#  System Architecture

```text
                   ┌─────────────────┐
                   │      User       │
                   └────────┬────────┘
                            │
                            ▼
                ┌────────────────────┐
                │ React Frontend UI  │
                │ (React + Bootstrap)│
                └────────┬───────────┘
                         │ API Calls
                         ▼
               ┌──────────────────────┐
               │ Node.js + Express API│
               └────────┬─────────────┘
                        │
        ┌───────────────┴───────────────┐
        ▼                               ▼

┌───────────────────┐          ┌────────────────┐
│ MongoDB Atlas     │          │ Cloudinary     │
│ Database Storage  │          │ Image Storage  │
└───────────────────┘          └────────────────┘
```

---

#  Workflow

### 1. User Registration/Login

Users create an account and authenticate securely.

### 2. Browse Available Jobs

Job seekers explore posted opportunities.

### 3. Apply for Jobs

Users submit applications directly.

### 4. Employer Management

Employers create listings and review applications.

### 5. Data Processing

Backend handles requests and stores data in MongoDB.

### 6. Response Delivery

Frontend updates dynamically and displays results.

---

#  Technologies Used

## Frontend

* React.js
* React Router
* Bootstrap
* HTML5
* CSS3
* JavaScript

## Backend

* Node.js
* Express.js

## Database

* MongoDB Atlas

## Authentication

* JWT (JSON Web Tokens)
* Bcrypt

## Cloud Storage

* Cloudinary

## Deployment

* Vercel (Frontend)
* Render (Backend)

---

#  Getting Started

## Prerequisites

Ensure the following are installed:

* Node.js (**v22.2.0+**)
* MongoDB Atlas account
* Cloudinary account

---

## Installation

### Clone Repository

```bash
git clone https://github.com/exclusiveabhi/react-job-portal.git
```

### Install Dependencies

```bash
cd react-job-portal

cd backend
npm install

cd ../frontend
npm install
```

---

## Environment Variables

Create:

```text
backend/config/config.env
```

Add:

```env
PORT=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
CLOUDINARY_CLOUD_NAME=
FRONTEND_URL=
DB_URL=
JWT_SECRET_KEY=
JWT_EXPIRE=
COOKIE_EXPIRE=
```

---

## Run Backend

```bash
cd backend
node server.js
```

## Run Frontend

```bash
cd frontend
npm run dev
```

Open:

```text
http://localhost:5173
```

---

#  Contributing

Contributions are welcome.

1. Fork Repository

2. Create Branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit Changes

```bash
git commit -m "Add AmazingFeature"
```

4. Push Changes

```bash
git push origin feature/AmazingFeature
```

5. Open Pull Request

---

##  Support

If you found this project helpful, give the repository a **star**.
