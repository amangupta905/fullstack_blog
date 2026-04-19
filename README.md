# 🚀 Fullstack Blog Application

A full-stack blog application built using **Django REST Framework (Backend)** and **React (Frontend)**.
This project allows users to create posts, like posts, and manage content with authentication.

---

## 📌 Features

- 🔐 User Authentication (JWT)
- 📝 Create, Update, Delete Blog Posts
- ❤️ Like / Unlike Posts
- 🏷️ Category & Tag Management
- 🔍 Fetch All Posts with Pagination
- 👤 User-specific Data (liked posts, own posts)

---

## 🛠️ Tech Stack

### Backend

- Django
- Django REST Framework (DRF)
- JWT Authentication

### Frontend

- React (Vite)
- Fetch API / Axios
- Tailwind CSS (if used)

---

## 📂 Project Structure

```
fullstack_blog/
├── backend/        # Django + DRF API
├── frontend/       # React App
└── README.md
```

---

## ⚙️ Installation & Setup

### 🔹 Clone Repository

```
git clone https://github.com/amangupta905/fullstack_blog.git
cd fullstack_blog
```

---

### 🔹 Backend Setup (Django)

```
cd backend
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

### 🔹 Frontend Setup (React)

```
cd frontend
npm install
npm run dev
```

---

## 🔗 API Endpoints (Sample)

- `GET /api/posts/` → Get all posts
- `POST /api/posts/` → Create post
- `POST /api/like/<id>/` → Like/Unlike post

---

## ❤️ Like System

- Users can like/unlike posts
- Each post shows:
  - `is_liked` (true/false)
  - `likes_count`

---

## 📸 Screenshots (Optional)

_Add screenshots of your UI here_

---

## 🚀 Future Improvements

- 💬 Comments system
- 🔔 Notifications
- 🌐 Deployment (Render / Vercel)
- 📱 Mobile responsive UI

---

## 👨‍💻 Author

**Aman Gupta**

- GitHub: https://github.com/amangupta905

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
