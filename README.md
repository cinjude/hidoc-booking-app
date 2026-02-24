🏥 HIDOC – Healthcare Appointment Platform

HIDOC is a full-stack web application that connects patients with specialized doctors.
Doctors can register and offer their medical services, while patients can search, filter, and book appointments based on their specific health needs.

🚀 Features

👨‍⚕️ Doctor registration and profile management

🏥 Specialty-based filtering (e.g., Dermatology, Cardiology, etc.)

🔍 Patient filtering by symptoms/allergies to find the right specialist

📅 Real-time appointment scheduling via Cal.com API

🔐 Secure authentication using JWT

📊 Doctor dashboard for managing availability and services

🧠 How It Works
For Doctors

Register and create a professional profile

Add specialization, location, and biography

Connect availability through Cal.com

Manage appointments via dashboard

For Patients

Search doctors by specialty

Filter by symptoms or allergies

View doctor profiles with detailed information

Book appointments instantly

🛠 Tech Stack
Frontend

React.js

JavaScript (ES6+)

HTML5

CSS3

Bootstrap

Backend

Python

Flask

SQLAlchemy

RESTful APIs

JSON Web Token (JWT)

Database

SQL

Testing & Collaboration

Jest

Git

GitHub

Third-Party Integration

Cal.com API (appointment scheduling)

🏗 Architecture

RESTful API structure

Component-based React frontend

Secure token-based authentication

Relational database design

Modular backend organization

👥 Team

Developed by a team of 4 developers.
My contribution (~35%) included:

All doctor-related backend endpoints

Doctor profile rendering and pagination

Doctor dashboard implementation

📦 Installation
# Clone repository
git clone https://github.com/4GeeksAcademy/Final-Project-VAJR.git

# Backend setup
pip install -r requirements.txt
flask db upgrade
flask run

# Frontend setup
npm install
npm run dev
🎯 Project Goal

The goal of HIDOC is to simplify access to healthcare services by enabling patients to quickly find the right specialist and schedule appointments efficiently.
