# -UserVault
# 🔐 UserVault – Secure Registration & Login System

## 📌 Overview

UserVault is a full-stack authentication system that allows users to register, log in, and manage their personal information securely.
It features a modern UI, password encryption using bcrypt, and stores user data in an Excel file.

---

## 🚀 Features

* ✅ User Registration with full details
* 🔑 Secure Login System
* 🔒 Password Hashing using bcrypt
* 📊 Data stored in Excel (`user.xlsx`)
* 🎨 Modern UI with animations
* 📱 Responsive design
* 📁 Profile photo upload (filename stored)
* ⚡ Fast Flask backend API

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3 (Modern UI + Animations)
* JavaScript (Vanilla JS)

### Backend

* Python (Flask)
* Flask-CORS

### Database

* Excel (`openpyxl`)

### Security

* bcrypt (password hashing)

---

## 📂 Project Structure

```
project/
│
├── index.html        # Frontend UI
├── server.py         # Flask backend
├── user.xlsx         # Database (auto-created)
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/uservault.git
cd uservault
```

### 2️⃣ Install dependencies

```
pip install flask flask-cors openpyxl bcrypt
```

### 3️⃣ Run the server

```
python server.py
```

### 4️⃣ Open in browser

```
http://localhost:5000
```

---

## 🧠 How It Works

### 🔹 Registration

* User fills the form
* Data is sent to Flask API
* Password is hashed using bcrypt
* Data is saved in Excel

### 🔹 Login

* User enters credentials
* Server checks email
* Password is verified using bcrypt
* User is authenticated

---

## 🔐 Security Features

* Passwords are NEVER stored in plain text
* bcrypt hashing is used
* Duplicate email prevention
* Basic input validation

---

## 📊 Data Storage

All user data is stored in:

```
user.xlsx
```

Includes:

* Name
* Email
* Password (hashed)
* Location details
* Registration timestamp

---

## 🎯 Future Improvements

* 🔄 Replace Excel with MySQL / MongoDB
* 🌐 Deploy online (Render / Vercel / Railway)
* 🔐 Add JWT authentication
* 📧 Email verification
* 👤 User dashboard

---

## 👨‍💻 Author

Developed by **Aabhash**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
