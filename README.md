# 🛒 Multi-Vendor E-Commerce Marketplace

A full-stack MERN-based multi-vendor e-commerce platform that connects customers, sellers, and administrators through a single online marketplace.

The platform allows customers to browse products, add items to their wishlist and cart, place orders, communicate with sellers, make payments, and track their orders. Sellers can create and manage products, shops, events, coupons, orders, and withdrawals. Administrators can manage users, sellers, products, orders, events, and withdrawal requests.

---

## 🌟 Project Overview

This application is designed as a multi-vendor marketplace where multiple sellers can create their own shops and sell products.

### 👤 Customers

Customers can:

- Create an account
- Verify their email
- Upload a profile image
- Login securely
- Browse products
- Search for products
- Filter products by category
- View product details
- View seller information
- Add products to wishlist
- Add products to cart
- Apply coupon codes
- Place orders
- Make payments
- Choose Cash on Delivery
- View order history
- Track orders
- Request refunds
- Manage addresses
- Write product reviews
- Chat with sellers

### 🏪 Sellers

Sellers can:

- Create a seller account
- Verify their email
- Create and manage their shop
- Add products
- Edit products
- Delete products
- Manage product stock
- Create events
- Manage events
- Create discount coupons
- Manage orders
- Update delivery status
- Communicate with customers
- Manage shop information
- Add bank details
- Request withdrawals
- View shop reviews
- View shop products
- Manage customer messages

### 👑 Administrators

Administrators can:

- Login securely
- View dashboard statistics
- View total earnings
- Manage sellers
- Manage customers
- Manage orders
- Manage products
- Manage events
- Manage withdrawal requests
- Manage application data

---

# 🛠️ Tech Stack

## Frontend

- React 18
- React Router
- Redux
- Tailwind CSS
- Material UI
- Axios
- React Icons
- JavaScript

## Backend

- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Multer
- Nodemailer

## Real-Time Communication

- Socket.IO

## Payments

- PayPal
- Stripe
- Cash on Delivery

## Package Manager

- Yarn

---

# 🚀 Main Features

## 🔐 Authentication

- Customer registration
- Customer login
- Seller registration
- Seller login
- Admin authentication
- Email verification
- Password management
- Profile management

## 🏠 Home Page

- Product listings
- Category filtering
- Best-selling products
- Events
- FAQ section
- Product search

## 🛍️ Product Management

- Product listing
- Product details
- Product categories
- Original price
- Discount price
- Product stock
- Product description
- Related products
- Seller information
- Product reviews
- Wishlist
- Shopping cart

## 💳 Checkout & Payments

The application supports:

- PayPal
- Stripe
- Cash on Delivery

Customers can also apply coupon codes during checkout.

## 👤 Customer Profile

Customers can:

- Update profile information
- Change password
- View orders
- Track orders
- Request refunds
- Manage addresses
- Chat with sellers
- Write reviews

## 💬 Real-Time Chat

Socket.IO is used for real-time communication between customers and sellers.

Features include:

- Text messages
- Image sharing
- Active status
- Message timestamps

## 🏪 Seller Dashboard

Sellers can manage:

- Products
- Orders
- Events
- Coupons
- Shop information
- Bank details
- Withdrawals
- Customer messages
- Shop reviews

## 👑 Admin Dashboard

Administrators can manage:

- Customers
- Sellers
- Products
- Orders
- Events
- Withdrawal requests
- Application statistics

---

# 📁 Project Structure

```text
Multi_vondor_E_shop/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── Admin/
│   │   │   ├── Cart/
│   │   │   ├── Checkout/
│   │   │   ├── Events/
│   │   │   ├── Layout/
│   │   │   ├── Payment/
│   │   │   ├── Products/
│   │   │   ├── Profile/
│   │   │   ├── Route/
│   │   │   ├── Shop/
│   │   │   ├── Signup/
│   │   │   └── Wishlist/
│   │   │
│   │   ├── pages/
│   │   ├── redux/
│   │   │   ├── action/
│   │   │   └── reducer/
│   │   ├── static/
│   │   ├── App.js
│   │   └── index.js
│   │
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controller/
│   ├── db/
│   ├── middleware/
│   ├── models/
│   ├── uploads/
│   ├── utils/
│   ├── mlter.js
│   ├── server.js
│   └── package.json
│
├── socket/
│   ├── index.js
│   ├── package.json
│   └── .env

⚙️ Installation & Setup
Step 1 — Clone the Repository
git clone https://github.com/Dishaks123/Multi_vondor_E_shop.git
cd Multi_vondor_E_shop
Step 2 — Setup Frontend
cd client

Install dependencies:

yarn install

Start the frontend:

yarn start
Step 3 — Setup Backend

Open another terminal:

cd server

Install dependencies:

yarn install

Create an uploads folder:

server/
└── uploads/

Create a .env file and configure the required environment variables:

PORT=8000
DB_URL=""
JWT_SECRET_KEY=""
JWT_EXPIRES=7d
ACTIVATION_SECRET=""
SMPT_HOST=smtp.gmail.com
SMPT_PORT=465
SMPT_PASSWORD=""
SMPT_MAIL=""
STRIPE_API_KEY=""
STRIPE_SECRET_KEY=""

Start the backend:

yarn start
🔌 Step 4 — Setup Socket Server

Navigate to the socket directory:

cd socket

Install dependencies:

yarn install

Create a .env file:

PORT=4000

Start the Socket.IO server:

yarn start
🗄️ MongoDB Configuration

The project requires a MongoDB database.

Configure your MongoDB connection inside the .env file:

DB_URL=""

Example:

DB_URL=mongodb://localhost:27017/multi_vendor_ecommerce

Do not upload database credentials or secret keys to GitHub.

💳 Payment Configuration

The application supports:

Stripe
PayPal
Cash on Delivery

Configure the required payment credentials in the backend .env file.

📧 Email Configuration

Nodemailer is used for email communication.

Configure your SMTP credentials inside the .env file.

📱 Responsive Design

The application is designed to work across:

Desktop
Laptop
Tablet
Mobile
🔒 Security

The application uses JWT-based authentication for secure user sessions.

Sensitive information such as:

Database credentials
JWT secrets
Payment API keys
SMTP passwords

should be stored in environment variables.

📦 Important Dependencies
React
React Router
Redux
Tailwind CSS
Material UI
Node.js
Express.js
MongoDB
JWT
Socket.IO
Axios
Multer
Nodemailer
React Icons
Yarn
⭐ Support

If you find this project useful, consider giving the repository a ⭐.

👨‍💻 Project
Multi-Vendor E-Commerce Marketplace

A MERN stack based e-commerce platform providing:

Multi-vendor shop management
Product management
Customer management
Order management
Payment integration
Admin dashboard
Seller dashboard
Real-time customer-seller communication
│
├── .gitignore
└── README.md
