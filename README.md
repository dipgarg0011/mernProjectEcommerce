# 🛒 MERN E-Commerce Application

A complete, production-ready **MERN Stack E-Commerce Application** built using **MongoDB, Express, React, and Node.js**.  
This project follows the tutorial series by **Abhishek Singh (6 Pack Programmer)** and is designed to be a clean, well-structured reference for MERN learners and open-source contributors.

---

## 🚀 Features Overview

### 👤 User Features
- User Signup & Login (JWT Authentication)  
- Update Profile & Change Password  
- Add to Cart  
- Create Orders & Track Order History  
- Forgot / Reset Password via Email  
- Cloud-based product image storage (Cloudinary)  

### 🛠️ Admin Features
- Create / Edit / Delete Products  
- Manage Users  
- Manage Orders  
- Admin Dashboard (Upcoming)  
- Fully Protected Admin Routes  

---

## 📦 Tech Stack

### **Frontend**
- React  
- Redux  
- Axios  
- React Router  

### **Backend**
- Node.js  
- Express  
- MongoDB + Mongoose  
- Cloudinary  
- Stripe Integration (Optional)  

---

## 📁 Project Structure

```
mernProjectEcommerce/
│── backend/        # Node.js + Express API
│── frontend/       # React Application
└── config/         # Environment Variables
```

---

## ⚙️ Setup & Installation

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/dipgarg0011/mernProjectEcommerce.git
cd mernProjectEcommerce
```

### **2️⃣ Install Backend Dependencies**
```bash
cd backend
npm install
```

### **3️⃣ Install Frontend Dependencies**
```bash
cd ../frontend
npm install
```

---

# 🧩 Environment Variables (Copy & Paste)

Create a file named **`.env`** inside the **backend/** folder and paste this:

```bash
# -----------------------------------------
# BASIC SERVER CONFIG
# -----------------------------------------
PORT=4000
DB_URI=your_mongodb_connection_string

# -----------------------------------------
# JWT AUTH
# -----------------------------------------
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRE=5d
COOKIE_EXPIRE=5

# -----------------------------------------
# STRIPE PAYMENT (Optional)
# -----------------------------------------
STRIPE_API_KEY=your_stripe_public_key
STRIPE_SECRET_KEY=your_stripe_secret_key

# -----------------------------------------
# SMTP EMAIL (For Forgot Password)
# -----------------------------------------
SMPT_SERVICE=gmail
SMPT_MAIL=your_email@gmail.com
SMPT_PASSWORD=your_email_app_password
SMPT_HOST=smtp.gmail.com
SMPT_PORT=465

# -----------------------------------------
# CLOUDINARY CONFIG
# -----------------------------------------
CLOUDINARY_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

---

## 🎓 Tutorial Reference
This project is inspired by the following MERN course playlist:

- **Node.js** — https://youtu.be/BSO9C8Z-YV8  
- **React** — https://youtu.be/99kgUCIMboY  
- **Express.js** — https://youtu.be/teipbke8c4A  
- **MongoDB** — https://youtu.be/AYDP1S5BbTo  
- **REST API (Optional)** — https://youtu.be/AhCSfuG9Jxw  

---


