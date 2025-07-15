
# MERN E-commerce Platform

![E-commerce Banner](frontend/public/logo192.png)

A full-featured E-commerce web application built with the MERN stack (MongoDB, Express.js, React, Node.js). This project includes user authentication, product management, cart, order processing, payment integration, and an admin dashboard.

---

## 🚀 Features
- User authentication & profile management
- Product listing, search, and filtering
- Shopping cart & checkout
- Order management (user & admin)
- Payment integration (Stripe)
- Admin dashboard for products, orders, users, and reviews
- Responsive design

## 🛠️ Tech Stack
- **Frontend:** React, Redux, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Payment:** Stripe
- **Cloud Storage:** Cloudinary

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd E-commerce
   ```
2. **Install backend dependencies:**
   ```bash
   npm install
   ```
3. **Install frontend dependencies:**
   ```bash
   cd frontend
   npm install
   ```
4. **Set up environment variables:**
   - Copy `backend/config/config.env.example` to `backend/config/config.env` and fill in your values (see below).

## ⚙️ Environment Variables
Create a `config.env` file in `backend/config/` with the following:
```
PORT=
DB_URI=
STRIPE_API_KEY=
STRIPE_SECRET_KEY=
JWT_SECRET=
JWT_EXPIRE=
COOKIE_EXPIRE=
SMPT_SERVICE=
SMPT_MAIL=
SMPT_PASSWORD=
SMPT_HOST=
SMPT_PORT=
CLOUDINARY_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

## ▶️ Usage
- **Start backend:**
  ```bash
  npm start
  ```
- **Start frontend:**
  ```bash
  cd frontend
  npm start
  ```
- Visit `http://localhost:3000` in your browser.

## 📁 Folder Structure
```
E-commerce/
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── config/
│   ├── app.js, server.js
├── frontend/
│   ├── src/
│   ├── public/
│   ├── build/
│   ├── package.json
├── package.json
├── README.md
```

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License
This project is licensed under the MIT License.
