# DJPost - A Simple Django CRUD App

## 📌 Overview
DJPost is a **basic CRUD web application** built using Django. It allows users to:
- **Sign up & Log in** securely
- **Create, Edit, and Delete** short posts (tweets)
- **Upload Images** with their posts
- **View posts** from other users

## 🚀 Features
- User Authentication (Sign up, Log in, Log out)
- Create, Read, Update, Delete (CRUD) functionality for posts
- Image upload support
- Responsive UI

## 🛠️ Tech Stack
- **Backend:** Django, Django ORM
- **Frontend:** HTML, CSS, Bootstrap 
- **Database:** SQLite

## 🔧 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/DJtweet.git
cd DJtweet
```

### 2️⃣ Create a Virtual Environment & Install Dependencies
```sh
python -m venv venv  # Create virtual environment
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
pip install -r requirements.txt  # Install dependencies
```

### 3️⃣ Apply Migrations & Run the Server
```sh
python manage.py migrate
python manage.py runserver
```

