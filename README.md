# 🛒 ShopEase – Full-Stack E-Commerce Platform

ShopEase is a fully functional MERN stack e-commerce web application that allows users to browse products, manage their cart, register/login, and securely complete payments. It includes a full admin dashboard to manage products and orders.

---


## 🧰 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- React Router DOM

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- JWT Authentication
- Braintree Payment Gateway

### Tools & Deployment
- Render (Backend Hosting)
- Vercel (Frontend Hosting)
- dotenv, multer, morgan, cors

---

## 🚀 Features

- 🔐 User Registration & Login
- 🛍️ Product Listing & Search
- 🛒 Add to Cart & Checkout
- 💳 Secure Payment Integration with Braintree
- 👤 Admin Dashboard (Product Management)
- 📦 Order Placement
- 🌎 Fully deployed and cloud-based

---

## 📁 Project Structure
ShopEase/
├── client/                # React frontend
│   ├── src/
│   ├── public/
│   └── ...
├── server/                # Node.js backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── ...
├── .env                   # Environment variables
├── README.md              # This file
└── package.json


🛠️ Getting Started

Clone the repository
git clone https://github.com/AbhinashRao/ShopEase.git
cd ShopEase

Install dependencies
Backend:
cd server
npm install

Frontend:
cd ../client
npm install

Setup .env files for backend:
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
BRAINTREE_MERCHANT_ID=your_id
BRAINTREE_PUBLIC_KEY=your_key
BRAINTREE_PRIVATE_KEY=your_key

Backend:
cd server
npm run dev

Frontend:
cd client
npm start

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.


👨‍💻 Author
Abhinash Rao Madikonda
📧 abhinashrao28@gmail.com
🔗 LinkedIn • GitHub
