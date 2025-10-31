 # 🗒️ Django Notes API

A simple **Django REST Framework (DRF)** project for managing personal notes with **JWT authentication**, **search**, and **user-based access control**.

---

## 🚀 Features

- ✅ Full CRUD operations for Notes  
- 🔍 Search notes by title or content  
- 🔒 Secure JWT authentication (via `SimpleJWT`)  
- 👤 User-specific notes (each user only sees their own)  
- 🧩 RESTful API design  

---

## 🧰 Tech Stack

- **Python 3.10+**
- **Django 4+**
- **Django REST Framework**
- **djangorestframework-simplejwt**
- **Postgres** (default)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/zeecoworld/note-app.git
cd note-app

POST /api/token/

{
  "username": "yourusername",
  "password": "yourpassword"
}

