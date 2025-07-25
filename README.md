# 🌐 Personal Portfolio - University Assignment

This is a **fullstack personal portfolio** project assigned by the university. It's built with **EJS**, **JavaScript**, **Node.js**, **Express**, **CSS**, and **SQLite**. The project showcases key fullstack functionalities such as **form handling**, **user authentication**, **email delivery**, **API integration**, and **analytics tracking**.

The portfolio includes a **contact form with reCAPTCHA**, sends emails via **Nodemailer** when a user registers, tracks visits using **Google Analytics**, and uses a **geolocation API** to identify user location on page load.

---

## ✨ Features

- **EJS**: Server-side rendering of dynamic views.
- **JavaScript**: Logic handled on both frontend and backend.
- **Node.js**: JavaScript runtime environment.
- **Express**: Web framework to build routes and APIs.
- **CSS**: Styling and responsive design.
- **SQLite**: Lightweight database for user data storage.
- **Nodemailer**: Sends confirmation emails upon user registration.
- **Google reCAPTCHA**: Protects the contact form from spam and bots.
- **Google OAuth**: Allows users to register and log in via Google.
- **Google Analytics**: Tracks user visits and behavior.
- **Geolocation API**: Fetches and stores approximate location of visitors.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Dixon282005/Pruebas-de-Express.git
```


2. ## Install Dependencies
```
npm install
```

3. ## Set Up Environment Variables
Create a .env file in the root directory and configure it:

```bash
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
RECAPTCHA_SECRET=your_recaptcha_secret
GEOLocation_API_KEY=your_api_key
```

4. ## Set Up the Database
Use SQLite to create a table for storing user messages and data.

5. ## Run the Project
```bash
npm start
```
Then visit:

```bash
http://localhost:3000
```

## 🛠  Tech Stack
<p align="left"> <img src="https://img.shields.io/badge/EJS-8FBC8F?style=for-the-badge&logo=ejs&logoColor=white" alt="EJS" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" /> <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" /> <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" /> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" /> <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" /> <img src="https://img.shields.io/badge/Nodemailer-4B8BBE?style=for-the-badge&logo=gmail&logoColor=white" alt="Nodemailer" /> <img src="https://img.shields.io/badge/reCAPTCHA-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="reCAPTCHA" /> <img src="https://img.shields.io/badge/Google%20OAuth-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google OAuth" /> <img src="https://img.shields.io/badge/Google%20Analytics-F9AB00?style=for-the-badge&logo=google-analytics&logoColor=black" alt="Google Analytics" /> <img src="https://img.shields.io/badge/Geolocation%20API-0A66C2?style=for-the-badge&logo=mapbox&logoColor=white" alt="Geolocation API" /> </p>



## 📌 Notes
This project was developed as a practical fullstack exercise to demonstrate a wide range of skills, including:

RESTful API creation

Secure form handling with validation and bot protection

Email notification system

OAuth authentication

Location-based features

Basic analytics integration

It represents an academic milestone in applying backend + frontend technologies together in a single working system.


