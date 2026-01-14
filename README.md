# Login-System-using-React-Django-Rest-Framework

Project Overview: 
This project is a full-stack authentication system built using React for the frontend and Django REST Framework (DRF) for the backend.
It allows users to register, log in, and access a protected dashboard where their personal details (name and email) are displayed.
The system uses JWT (JSON Web Tokens) for secure authentication and authorization between the frontend and backend.

🚀 Features
- User Registration
- User Login with Authentication
- JWT-based Authentication
- Protected Dashboard Route
- Displays Logged-in User’s Name and Email
- Secure API Communication
- React Frontend + Django REST Backend

🛠️ Tech Stack

Frontend: 
React.js,
Axios,
React Router DOM,
CSS

Backend: 
Django,
Django REST Framework,
Simple JWT

Tools:
 - Python
 - Node.js
 - VS Code

⚙️ How It Works: 

User registers through the Register page.
Data is sent to Django REST API.
User logs in using valid credentials.
Backend verifies the user and returns a JWT token.
Token is stored in the browser (localStorage).
User is redirected to the Dashboard.
Dashboard fetches protected user data and displays name and email.

▶️ Installation & Setup:

 🔹 Backend Setup
 - cd backend
 - python -m venv env
 - env\Scripts\activate   # for Windows
 - pip install -r requirements.txt
 - python manage.py migrate
 - python manage.py runserver

  🔹 Frontend Setup
  - cd frontend
  - npm install
  - npm start
