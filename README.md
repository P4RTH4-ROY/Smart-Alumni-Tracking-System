# 🎓 Smart Alumni Tracking System (SATS)

A full-stack MERN application designed to help universities and colleges track their alumni efficiently. Users can register, update, and manage alumni records including department, batch, contact info, current position, and LinkedIn profile.

## 🔧 Features

- ✅ Register alumni with key details
- ✏️ Edit or update alumni information
- 🗑️ Delete alumni records
- 📋 View all registered alumni in a responsive table
- 💬 Inline success/error messages
- ⚙️ Built using React, Node.js, Express, MongoDB

---

## 📸 UI Overview

- Logo and branded header
![image](https://github.com/user-attachments/assets/49df58f7-0ec1-438e-8afc-eecdd77c2504)
- Clean and sober form layout
- Success message shown next to submit button
![image](https://github.com/user-attachments/assets/b6e58fb4-c6d2-446e-9990-bec0fb42ad65)


- Alumni list shown in a table with Edit/Delete options

---

## 🚀 Technologies Used

| Frontend       | Backend        | Database     | Others            |
|----------------|----------------|--------------|-------------------|
| React (Vite)   | Node.js        | MongoDB Atlas| Axios, Express.js |
| CSS3           | Express.js     | Mongoose     | Nodemon, CORS     |

---

## 📂 Folder Structure

```

SATS/
├── client/            # React frontend (Vite)
│   └── src/
│       └── App.jsx
│       └── App.css
│       └── logo.png
├── server/            # Backend with Express
│   └── models/        # Mongoose schemas
│   └── routes/        # API routes
│   └── server.js      # Server entry point
└── README.md

````

---

## 📦 Installation

### 1. Clone the repository

```bash
https://github.com/P4RTH4-ROY/Smart-Alumni-Tracking-System.git
````

### 2. Setup Backend

```bash
cd server
npm install
node server.js
```

> Make sure to update the MongoDB connection string in `server.js`.

### 3. Setup Frontend

```bash
cd ../client
npm install
npm run dev
```

## 📃 API Endpoints

| Method | Endpoint          | Description          |
| ------ | ----------------- | -------------------- |
| GET    | `/api/alumni`     | Get all alumni       |
| POST   | `/api/alumni`     | Add new alumni       |
| PUT    | `/api/alumni/:id` | Update alumni info   |
| DELETE | `/api/alumni/:id` | Delete alumni record |

---

## ✅ TODO / Improvements

* [ ] Add authentication for admin access
* [ ] Export alumni list to CSV
* [ ] Filter/search alumni by department or batch
* [ ] Mobile responsiveness enhancement

---

## 💡 Author

**Partha Roy**
📧 Gmail: proy48878@gmail.com
🌐 GitHub: https://github.com/P4RTH4-ROY

