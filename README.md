# Full-Stack Social Media Application (MERN)

A fully responsive, end-to-end **social media application** built from scratch using the **MERN stack**.
This project implements real-world social features, modern UI/UX practices, robust backend architecture, and complete authentication flow.

---

## Features

### **User Authentication**

* User registration with validation
* Profile image upload during signup
* Login authentication powered by JWT
* Persistent sessions using Redux Persist

### **Home & Feed**

* Personalized home feed after login
* Display of all user posts in chronological order
* Fully responsive UI layout (mobile, tablet, desktop)

### **Posts**

* Create text or image posts
* Edit and delete own posts
* Like/Dislike functionality
* Post comment viewing

### **User Profiles**

* View your own profile with:

  * Location
  * Occupation
  * Profile views & impressions
* Visit other users’ profiles
* Display all posts created by the selected user
* Add/Remove friends

### **UI/UX**

* Clean, modern, minimalistic design
* **Light/Dark mode** toggle
* Smooth navigation using React Router

### **Backend Integration**

All frontend features are connected to:

* Custom-built Node.js + Express API
* MongoDB database storing users, posts, friend lists, likes, comments, and more
* Secure authentication and image upload handling

---

## Tech Stack

### **Frontend**

* **React**
* **React Router** – Routing & navigation
* **Formik + Yup** – Form handling & validation
* **Redux Toolkit** – Global state management
* **Redux Persist** – Local storage persistence
* **React Dropzone** – Image uploads
* Fully responsive layout using modern CSS

### **Backend**

* **Node.js** – Runtime
* **Express.js** – Backend framework
* **Mongoose** – MongoDB object modeling
* **MongoDB** – NoSQL database
* **JWT (JSON Web Token)** – Secure authentication
* **Multer** – Handling profile/post image uploads

---

## Setup Instructions

### 1. Backend Setup

```bash
cd server
npm install
```

Create a `.env` file:

```
MONGO_URL=<your-mongodb-uri>
JWT_SECRET=<your-secret>
PORT=3001
```

Start the server:

```bash
npm start
```

### 2. Frontend Setup

```bash
cd client
npm install
npm start
```

---

## Future Improvements

* Real-time updates using WebSockets
* Push notifications
* Comment threading
* Story/reels feature
* Chat system

---

## Acknowledgements

Inspired by modern social platforms and built as a learning project to understand full-stack development, authentication flows, backend API design, and responsive UI architecture.


