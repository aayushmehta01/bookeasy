
# 🏨 Hotel Booking App

## 📜 Description

The **Hotel Booking App** is a web application that allows users to search for hotels based on the city, filter them by price, view hotel photos, authenticate users, reset passwords via email, and book rooms. The application is built using the **MERN stack** (MongoDB, Express, React, Node.js) with **Nodemailer** for sending emails.

---

## ⚡ Features

### 🌐 Frontend Features
- **Search by City** 🌆: Users can search for hotels by the city they are planning to visit.
- **Filter by Price** 💸: Users can filter hotels based on their preferred price range.
- **Hotel Photos** 📸: Users can view photos of hotels and rooms to help with their booking decisions.
- **User Authentication** 🔒: Secure login, registration, and session management for users.
- **Password Reset** 🔑: Users can reset their password by receiving a reset link in their email.
- **Room Selection** 🛏️: Users can select rooms based on availability and room numbers.

### ⚙️ Backend Features
- **User Authentication** 🔐: Secure user login and registration using **JWT** (JSON Web Tokens).
- **Password Hashing** 🔑: Passwords are securely hashed using **bcryptjs** before storing them in the database.
- **Email Integration** 📧: **Nodemailer** is used for sending password reset emails.
- **MongoDB** 🗄️: The backend uses **MongoDB** for storing hotel, user, and room data.
- **CORS** 🌍: Configured to allow communication between the frontend and backend.

---

## 📥 Installation

### 🛠️ Prerequisites
Ensure that you have the following installed:
- **Node.js**
- **npm** (or **yarn**)

### Step-by-Step Setup

1. **Clone the repository**

   ```bash
   git clone --recurse-submodules https://github.com/aayushmehta01/bookeasy.git
   cd <project_directory>
   ```

2. **Install frontend dependencies**

   Navigate to the **frontend** directory and run:

   ```bash
   cd bookingapp-frontend
   npm install
   ```

3. **Install backend dependencies**

   Navigate to the **backend** directory and run:

   ```bash
   cd bookingapp-api
   npm install
   ```

4. **Set up environment variables**

   - In the **backend** directory, create a `.env` file and add your environment variables (e.g., for MongoDB, JWT secret, and Nodemailer credentials):

     ```
     JWT_SECRET=your_jwt_secret
     MONGO_URI=mongodb://localhost:27017/hotel-booking
     SMTP_HOST=smtp.your-email-provider.com
     SMTP_PORT=587
     SMTP_USER=your-email@example.com
     SMTP_PASS=your-email-password
     ```

5. **Start the backend**

   Navigate to the **backend** folder and run:

   ```bash
   cd backend
   npm run dev
   ```

6. **Start the frontend**

   Navigate to the **frontend** folder and run:

   ```bash
   cd frontend
   npm run dev
   ```

   The frontend will be available at [http://localhost:5173](http://localhost:5173).

---

## 🧑‍💻 Contributing

Feel free to fork the repository and submit pull requests. Ensure that you follow the coding style and provide meaningful commit messages.

---

## 📧 Contact

For questions or feedback, please reach out to:  
**Email:** [aayush2511m@gmail.com](aayush2511m@gmail.com)

---

## 🎉 Credits

Special thanks to **[Lamadev](https://github.com/safak)** for inspiration and guidance throughout the development of this project.
