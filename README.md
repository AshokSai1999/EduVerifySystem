# EduVerifySystem 🎓🔐

A simple College Management System built with Python that integrates email-based OTP verification for secure logins. This project demonstrates object-oriented programming, voice feedback via text-to-speech, and basic email authentication.

## 🚀 Features

- Add and manage multiple colleges
- Add students and teachers to colleges
- Email-based OTP login system
- Voice feedback using `pyttsx3`

## 🧱 Project Structure

EduVerifySystem/ ├── oop.py # Main application with college, student, and teacher logic ├── otp_module.py # Email OTP generator and verification logic


## 🛠️ Technologies Used

- Python 3.x
- `smtplib`, `email` — for sending OTP via Gmail SMTP
- `random` — for OTP generation
- `pyttsx3` — for offline text-to-speech

## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/AshokSai1999/EduVerifySystem

Install required packages:
pip install pyttsx3

Update the email and password in otp_module.py:

Make sure to use App Passwords from your Google account for better security.

📢 Voice Assistant
This project includes voice feedback for various actions using the pyttsx3 module. This works offline and enhances accessibility.
   
