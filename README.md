# 🏥 UFUQ (أفق) - Donation Charity Platform

## 📌 Overview
UFUQ (**أفق**) is a **donation-charity platform** where users can register, browse campaigns, and donate to approved charitable causes. Beneficiary organizations can submit applications to request funding for medical tools, and admins review and approve/reject these applications.

## 🔥 Features

### 🏛️ User Roles
- **Donors**: Register/Login, browse campaigns, and donate.
- **Beneficiary Organizations**: Submit applications with required documents.
- **Admins**: Review applications, approve/reject campaigns, and manage reports.

### 📋 Application & Donation Flow
1. **Organizations submit applications** with required documents.
2. **Admin reviews the application** and either approves or rejects it.
3. **Approved campaigns become visible** to users.
4. **Users browse campaigns**, view details, and donate.
5. **Donation progress updates in real-time**.
6. **Admins & users track donations** via a dashboard with reports.

## 🛠️ Technologies Used

### **Frontend (Client-Side)**
- ⚛️ **React.js** – User interface development.
- 🏛 **Redux** – State management.
- 🔗 **Axios** – API requests handling.

### **Backend (Server-Side)**
- 🟢 **Node.js** – Server-side environment.
- 🏗️ **MVC Structure** – Organized backend.
- 📄 **Sequelize ORM** – Database interaction.
- 🗄 **PostgreSQL** – Database storage.
- 🔐 **JWT Authentication** – Secure login & token storage in cookies.

### Security**
- 🔐 **HTTP-Only Cookies** – Secure token storage.

## 📂 Project Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/ufuq-charity-platform.git
cd ufuq-charity-platform
```

### **2️⃣ Install Dependencies**
#### Frontend
```bash
cd client
npm install
npm start
```

#### Backend
```bash
cd server
npm install
npm start
```

### **3️⃣ Environment Variables (.env)**
Create a `.env` file in the backend and add:
```env
PORT=5000
DATABASE_URL=your_postgresql_url
JWT_SECRET=your_secret_key
```

## 📊 Dashboard & Reports
- **Admin Dashboard**: Monitor total donations, campaigns, and generate reports.

## 🚀 Future Enhancements
- 📢 **Email Notifications** for donors & organizations.
- 📈 **Real-time updates** using WebSockets.
- 🏦 **Withdrawals management** for organizations.

## 🤝 Contributing
Feel free to fork this repository and submit pull requests! 🎉
---

### 🎯 Made with ❤️ by [Faisal Al-Ali](https://github.com/your-username)
