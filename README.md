# 🎓 DigiScholar Scholarship Portal

A full-stack web application built using **Firebase** and **Vanilla JavaScript** to streamline the PMSSS scholarship application process. It supports student registration, application submission, document upload, and admin-side verification.

---

## ✨ Features

- 🔐 Firebase Authentication for student login/signup
- 📝 Scholarship application form submission
- 📤 Document upload to Firebase Storage
- 📡 Firebase Realtime Database for storing form data
- 🧑‍💼 Admin access to verify, approve, or reject applications
- 🎯 Clean and responsive UI

---

## 🛠️ Tech Stack

- ReactJs, CSS3, JavaScript
- Firebase Authentication
- Firebase Realtime Database
- Firebase Storage

---

## 📁 Folder Structure

- `index.html` – Landing & Login Page  
- `register.html` – New student signup  
- `application.html` – Scholarship application form  
- `admin.html` – Admin dashboard (basic access control)
- `firebase.js` – Firebase project configuration  
- `script.js` – Form handling, auth, and upload logic

---

## 🚀 How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/Khushal22j/digischolar-scholarship-portal.git
cd digischolar-scholarship-portal
Create a Firebase project at console.firebase.google.com

Enable the following in Firebase:

Firebase Authentication (Email/Password)

Firebase Realtime Database

Firebase Storage

Replace the config in firebase.js with your Firebase project config.

Open index.html in your browser to get started.

🔒 Admin Access
Admins can log in with specific Firebase-authenticated credentials and access:

All student applications

Uploaded documents

Status change controls (Approve / Reject)

📌 Future Improvements
Add email notifications for status updates

Role-based auth enforcement (admin vs student)

Better UI/UX for application form

📄 License
This project is licensed under the MIT License.
