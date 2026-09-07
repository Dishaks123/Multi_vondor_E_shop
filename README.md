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
- Upload shop images
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
- Send images through chat
- Manage shop information
- Add bank details
- Request withdrawals
- View shop reviews
- View shop products
- View running events

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
- Delete users and sellers
- Verify seller withdrawal requests
- Manage images
- Send email notifications

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
- Cash on Delivery (COD)

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
- Profile image upload

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
- Upload profile picture
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

# 📹 Video Demo

You can watch the project demonstration here:

[▶️ Watch Project Demo](https://www.youtube.com/watch?v=J7PWBRnEIv8)

---

# 📸 Screenshots

## 🏠 Home Page

![Home Page](https://github.com/pattjoshi/Multi_vondor_E_shop/assets/78966839/14dfa843-e495-4fd7-bffe-b10b7a65cfc9)

## 👤 User Profile

![User Profile](https://github.com/pattjoshi/Multi_vondor_E_shop/assets/78966839/e3fcdef1-460b-4ed6-bb51-425e6dfe3379)

## 🛍️ Product Page

![Product Page](https://github.com/pattjoshi/Multi_vondor_E_shop/assets/78966839/60d125e1-c4b5-4ab7-9ae5-ca922f44cd62)

## 🧾 Receipt

![Receipt](https://github.com/pattjoshi/Multi_vondor_E_shop/assets/78966839/370e357d-8248-46fc-8749-37aed7f5efd3)

## 🏪 Seller Dashboard

![Seller Dashboard](https://github.com/pattjoshi/Multi_vondor_E_shop/assets/78966839/386b48a1-9139-4b19-be0b-0b86c9cb8ccb)

## 👑 Admin Dashboard

![Admin Dashboard](https://github.com/pattjoshi/Multi_vondor_E_shop/assets/78966839/df7f3d6c-d429-48a0-b9bc-1673c7532faf)

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
│
├── .gitignore
└── README.md

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

Open another terminal and navigate to the server:

cd server

Install dependencies:

yarn install

Create an uploads folder:

server/
└── uploads/

Create a .env file inside the configuration folder.

Example:

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

Then start the backend:

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

The project requires a MongoDB connection.

Add your MongoDB connection string to:

DB_URL=""

Example:

DB_URL=mongodb://localhost:27017/multi_vendor_ecommerce

Do not upload real database credentials, API keys, passwords, or secret keys to GitHub.

💳 Payment Configuration

The application supports:

Stripe
PayPal
Cash on Delivery

Configure your payment credentials in the backend .env file.

📧 Email Configuration

Nodemailer is used for email communication such as:

Email verification
Notifications
Seller notifications
Order-related communication

Configure your SMTP credentials in the .env file.

📱 Responsive Design

The application is designed to work across different screen sizes, including:

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

Built using the MERN stack with real-time communication, seller management, customer management, product management, order processing, and payment integration.

