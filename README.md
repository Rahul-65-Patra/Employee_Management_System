# 🧑‍💼 StaffHub - Employee Management System (MERN Stack)

**StaffHub** is a powerful and intuitive **Employee Management System** built using the MERN stack (MongoDB, Express.js, React, Node.js).  
It streamlines HR processes like attendance, leave, and salary management through a clean interface and role-based access.

---

## ✨ Features

### 🔐 Authentication
- 👤 Users can log in with username and password.
- 🔒 Only super admins can sign up new users with role, email, name, password, position, and date of joining.

### 🧾 Dashboard
- 📊 Displays statistics and relevant insights.
- 🗓️ Shows employees on leave today.
- 👥 Summarizes total employees and their designations.

### 🧑‍💼 Employee Management
- 📝 Employees can view/edit their own profiles.
- 👑 Super admins can view/edit all employee data.

### 🗂️ Department Management
- 🏢 Manage departments.
- 📌 Assign employees to departments.

### 🕒 Attendance Management
- ✅ Track employee attendance records.
- 📅 View daily/monthly attendance summaries.

### 💰 Salary Management
- 💵 Manage employee salary records.
- 🧮 Includes basic, allowances, deductions, and net salary.

### 🛫 Leave Management
- 📥 Employees can apply for leave and check status/history.
- 👨‍💼 Super admin can view, approve, or reject leave requests.

### ⚙️ Profile & Settings
- 👤 Employees can update their profile picture, username, and password.

### 🧩 Utilities
- 🛡️ Private routing and role-based access.
- 🧱 Reusable components for consistency.

---

## 🛠️ Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Javascript](https://img.shields.io/badge/JavaScript-FFFF00?style=for-the-badge&logo=javascript&logoColor=black)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-ffff00?style=for-the-badge&logo=node.js&logoColor=black)
![Express.js](https://img.shields.io/badge/Express.js-ffff00?style=for-the-badge&logo=express&logoColor=black)
![JWT](https://img.shields.io/badge/jwt-ffff00?style=for-the-badge&logo=JWT&logoColor=black)

---

## 🔗 Live Preview

🚧 *Live demo link coming soon...*

---

## 🧑‍💻 How to Clone & Run Locally :---

 1. 📥 **Clone the Repository**
```bash
git clone https://github.com/your-username/Employee_Management_System.git

cd Employee_Management_System
```

2. 📁 **Navigate to the Backend Directory**
```bash
  cd backend
```

3. 🧱 **Install Backend Dependencies**
```bash
  npm install
```

4. ⚙️ **Configure Environment Variables**

   Create a .env file in the backend folder and add:
```bash
  PORT=your_port_number
  MONGO_URI=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret_key
```

5. 🚀 **Start the Backend Server**
```bash
  node server.js
```

6. 🌐 **Navigate to the Frontend Directory**
```bash
  cd frontend
```
7. 🚀 **Install Frontend Dependencies**
```bash
  npm install
```
8. ⚙️ **Configure Environment Variables**

   Create a .env file in the frontend folder and add:
```bash
   VITE_API_URL = http://localhost:5000/api
   # http://localhost:5000/api

   VITE_IMAGE_URL = http://localhost:5000
   # http://localhost:5000/uploads (for upload image)
```
9. 🚀 **Start the Frontend Dev Server**
```bash
  npm run dev
```
10. 🖥️ **Open in Browser**
 http://localhost:5173

---

## 📛 Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)

[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 💡Contributing
Contributions are welcome! Please open issues or submit pull requests for suggestions and improvements.
