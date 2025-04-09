Echo – A Django Blog Application
Overview
Echo is a simple, yet functional blog application built with Django. It enables users to perform essential CRUD operations for blog posts, along with image uploads and user authentication features.

Key Capabilities:
Secure user authentication (Sign up, Log in, Log out)

Create, update, and delete blog posts

Upload and display images with posts

View posts from other users

Fully responsive user interface

Features
User registration and login system

Create, read, update, and delete functionality for blog posts

Image upload support for posts

Clean, responsive front-end design using Bootstrap

Tech Stack
Backend: Django, Django ORM

Frontend: HTML, CSS, Bootstrap

Database: SQLite (default for development)

Getting Started
Follow the steps below to set up the project on your local machine:

1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/DJPost.git
cd DJPost
2. Set Up a Virtual Environment and Install Dependencies
bash
Copy
Edit
python -m venv venv                  # Create virtual environment
source venv/bin/activate             # Activate on macOS/Linux
venv\Scripts\activate                # Activate on Windows
pip install -r requirements.txt      # Install project dependencies
3. Apply Migrations and Start the Development Server
bash
Copy
Edit
python manage.py migrate             # Apply database migrations
python manage.py runserver           # Start the Django development server
Once the server is running, visit http://127.0.0.1:8000/ in your browser to access the application.
