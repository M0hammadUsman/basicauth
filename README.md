# 🌟 Kotlin-Golang Full Stack App 🌟

This repository contains a **frontend Kotlin app** and a **backend Golang API** working together to deliver a seamless user experience for authentication and user data management. 🚀

---

## 📋 Features

1. 🔑 **Login API**  
   Handle user login functionality using **JWT authentication**.  
   On successful login, users are redirected to the **User List** page.

2. ✍️ **Register API**  
   Allow new users to register an account with secure credentials.

3. ❓ **Forgot Password API**  
   Help users recover their password by answering a **security question** for verification.

4. 👥 **Display Users Data API**  
   Retrieve and display user data for authenticated users with a valid **JWT token**.

---

## 🛠️ Tech Stack

### Backend: ⚙️ Golang API  
- **JWT**: Secure authentication and token-based authorization.  
- **Security Questions**: Used for resetting passwords in the Forgot Password flow.  
- RESTful APIs for all interactions with the frontend.

### Frontend: 📱 Kotlin App  
- A user-friendly **Android app** built with Kotlin.  
- Displays users' data after successful login.  

---

## 🚀 How It Works

1. 📝 **User Registration**  
   New users register by providing their username, email, password, and a security question-answer pair.  

2. 🔑 **Login Process**  
   Users log in with their credentials. If successful, a **JWT token** is issued to authenticate the session.

3. ❓ **Forgot Password Flow**  
   Users answer their security question to reset their password.

4. 👥 **Display Users List**  
   Upon successful login, authenticated users can view a list of all registered users.

---

## 📦 API Endpoints

### 🔑 **Authentication APIs**:
- `/login`  
  Handle user login. Requires username and password. Returns a **JWT token** if credentials are valid.

- `/register`  
  Register a new user with their details and a security question.

- `/forgot-password`  
  Reset a user's password by verifying their response to the security question.

### 👥 **User Data APIs**:
- `/users`  
  Fetch the list of registered users. Requires a valid **JWT token**.

---

## ⚡ Quick Start

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/M0hammadUsman/basicauth.git
