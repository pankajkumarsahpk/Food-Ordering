# 🍴 Tomato Food Ordering
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/username/Tomato-Food-Delivery-Web-App/blob/main/LICENSE)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-%3E%3D5.0-green)](https://www.mongodb.com/)
A full-stack food delivery platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js). Tomato provides a seamless ordering experience for customers and powerful management tools for restaurant administrators.  
# 📸 Screenshots

### Customer Interface
![Home Page](https://github.com/pankajkumarsahpk/Food-Ordering/blob/my-new-branch/Screenshot%202026-02-06%20091754.png)
*Beautiful landing page with hero section and call-to-action*)
*Beautiful landing page with hero section and call-to-action* 

![Menu Categories](https://github.com/pankajkumarsahpk/Food-Ordering/blob/my-new-branch/Screenshot%202026-02-06%20091846.png)
*Explore diverse menu categories and discover top dishes near you*

## ✨ Features

- **🔐 Secure Authentication** - Password hashing and salting for both customers and administrators
- **👨‍💼 Admin Dashboard** - Complete restaurant, menu, and order management system
- **📱 Responsive Design** - Optimized experience across desktop, tablet, and mobile devices
- **🚀 Real-time Updates** - Live order tracking and status notifications
- **🎨 Intuitive Interface** - User-friendly design for effortless navigation and ordering
- **⚡ High Performance** - Scalable architecture built on the MERN stack

  ## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB](https://www.mongodb.com/) (v5 or higher)
- npm or yarn package manager
- Git
## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/username/GrabitGo-Food-Delivery-Web-App.git
   cd GrabitGo-Food-Delivery-Web-App
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure environment variables**
   
   Create a `.env` file in the root directory:
   ```env
   MONGO_URI=your_mongodb_connection_string
   NODE_ENV=development
   PORT=5000
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Start the application**
   ```bash
   npm start
   # or
   yarn start
   ```

5. **Access the application**
   
   Open your browser and navigate to `http://localhost:5000`

## 📁 Project Structure

```
GrabitGo-Food-Delivery-Web-App/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── services/
│       └── App.js
├── server/                 # Express backend
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── .env.example
├── package.json
└── README.md
```
