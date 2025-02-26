# 📝 TNA - Task and Notification Application

TNA is a Django-based web application designed for managing tasks, relationships, and notifications in a streamlined workflow. It supports vintage and showroom image galleries, user management with email notifications, and advanced task scheduling using Celery and ASGI.

---

## 🚀 Features

- 📦 Manage tasks with hierarchical relationships and automatic scheduling.
- 🖼️ Image gallery with vintage and showroom categories, subcategories, and tags.
- 📨 Email notifications with system-generated passwords for new users.
- 🔒 Secure password change on first login.
- ⏰ Task management with Celery and ASGI for real-time notifications.
- 🌐 Single API endpoint for complete history tracking across related models.
- 🎨 Color-coded relationship hierarchies for easy visualization.

---

## ⚙️ Technologies Used

- **Backend**: Django, Django REST Framework (DRF)
- **Task Management**: Celery, Redis
- **Real-Time Support**: ASGI, Django Channels
- **Database**: PostgreSQL / SQLite (configurable)
- **Authentication**: Django's built-in auth system with SMTP for email
- **Frontend**: (Frontend framework here if any)
- **Deployment**: Gunicorn, Nginx (if deployed)

---

## 💾 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Gulabchandyadav800/TNA.git
   cd TNA
