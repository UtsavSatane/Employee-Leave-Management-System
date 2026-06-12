# 🗂️ Employee Leave Management System (ELMS)

A full-stack web application built with the **MERN Stack** that streamlines the process of managing employee leave requests within an organization.

---

## 🚀 Live Demo

> 🔧 Coming Soon — deployment in progress

---

## 📸 Screenshots

> _Add screenshots of your dashboard, leave request form, and admin panel here_

---

## ✨ Features

### 👤 Employee
- Apply for leave with type, dates, and reason
- View personal leave balance and history
- Track the status of submitted requests (Pending / Approved / Rejected)

### 🛠️ Admin
- View all employee leave requests on a centralized dashboard
- Approve or reject leave requests with a single click
- Monitor leave analytics and usage across the organization

### 🔐 General
- Role-based access control (Admin / Employee)
- Secure authentication
- Interactive dashboard with analytics

---

## 🛠️ Tech Stack

| Layer      | Technology            |
|------------|-----------------------|
| Frontend   | React.js              |
| Backend    | Node.js, Express.js   |
| Database   | MongoDB, Mongoose     |
| Auth       | JWT / Session-based   |
| Styling    | CSS / Tailwind / MUI  |

---

## 📁 Project Structure

```
elms/
├── client/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
├── server/          # Express backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
└── README.md
```

---

## ⚙️ Setup & Installation

### Prerequisites
- Node.js (v16+)
- MongoDB (local or Atlas)

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/elms.git
cd elms
```

### 2. Setup the Backend
```bash
cd server
npm install
```

Create a `.env` file inside the `server/` folder:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

Start the backend:
```bash
npm start
```

### 3. Setup the Frontend
```bash
cd client
npm install
npm start
```

The app will run at `http://localhost:3000`

---

## 🔑 Demo Credentials

| Role     | Email               | Password   |
|----------|---------------------|------------|
| Admin    | admin@demo.com      | demo123    |
| Employee | employee@demo.com   | demo123    |

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with ❤️ by [Utsav](https://github.com/YOUR_USERNAME)
