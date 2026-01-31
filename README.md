# 🛒 MERN Stack eCommerce Application

This is a full-stack eCommerce web application built using the **MERN** stack — **MongoDB, Express.js, React.js,** and **Node.js**. It features a fully responsive user interface, shopping cart functionality, secure authentication, and an admin panel for managing products.

## 🚀 Features

### 🔹 User Side
- Responsive React.js frontend
- Add/remove products from cart
- Secure user authentication (login/register)
- View product details and checkout flow

### 🔹 Admin Panel
- Admin authentication
- Add, update, delete products
- Dashboard for product management

### 🔹 Backend
- Built with Node.js and Express.js
- MongoDB database integration
- RESTful APIs for user and product management
- JWT-based authentication for secure access

---

## 🧰 Tech Stack

- **Frontend:** React.js, Axios, React Router
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Authentication:** JWT, Bcrypt
- **Styling:** CSS, Bootstrap/Tailwind (based on your project)
- **Deployment:** (Add here if deployed – e.g., Vercel/Netlify & Render/Heroku)

---

## 📂 Folder Structure

ecommerce/ │ ├── client/ # React.js frontend │ ├── public/ # Static assets │ └── src/
│ ├── assets/ # Images, logos │ ├── components/ # Reusable React components │ ├── pages/ # Main pages (Home, Login, Cart, etc.) │ ├── context/ # Auth or cart context │ ├── App.js # Main app entry │ └── index.js # ReactDOM render │ ├── server/ # Node.js backend │ ├── config/ # DB config, env setup │ ├── controllers/ # Request handlers │ ├── middleware/ # Auth and error middlewares │ ├── models/ # Mongoose schemas │ ├── routes/ # Express routes │ ├── server.js # Entry point │ └── .env # Environment variables │ ├── package.json # Project metadata (root or client/server) ├── README.md └── .gitignore



---

## 🛠️ Getting Started

### Prerequisites
- Node.js & npm
- MongoDB (local or cloud-based like MongoDB Atlas)

### Clone and Run

```bash
# Clone the repo
git clone https://github.com/hemanth-1116/e-commerce
cd mern-ecommerce

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install

# Create environment variables
# server/.env
MONGO_URI=mongodb+srv://hem:hemanth123@cluster0.vgtlq.mongodb.net

# Run both client and server (concurrently)
npm run dev
