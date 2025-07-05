# Ecommerce-Backend-API
A robust and scalable backend API built for an ecommerce platform using Node.js, Express.js, and MongoDB. It handles core functionalities like user authentication (JWT), product management (CRUD operations), cart and wishlist features, order processing, payment integration (e.g., Stripe), and admin controls for inventory and analytics. 

---

## 🚀 Key Features

- ✅ User registration & login (JWT-based)
- 🛍️ Product, category CRUD
- 🛒 Cart & wishlist handling
- 📦 Order placement & tracking
- 🧑‍💼 Admin access control
- 💳 Payment gateway integration-ready (Stripe/PayPal)
- 🧰 Middleware for auth, error handling, logging
- 📘 API Docs via Swagger (`swagger.yaml`)

---

## 📁 Folder Structure

📦 root/
- 📂configs/ → DB & env setup
- 📂controllers/ → Business logic
- 📂middlewares/ → Auth, error handlers
- 📂models/ → Mongoose schemas
- 📂routes/ → API routes
- 📂utils/ → Helpers (tokens, logger)
- 📄app.js → Express app config
- 📄index.js → Server entry point
- 📄.env → Env variables
- 📄swagger.yaml → Swagger API docs


## ⚙️ Getting Started

### 1. Clone & install dependencies

```bash
git clone https://github.com/your-username/ecommerce-backend-api.git
cd ecommerce-backend-api
npm install
```

### 2. Create .env file

```bash
env
Copy
Edit
PORT=5000
MONGO_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=your_jwt_secret
```

### 3. Run the server
```bash
Copy
Edit
npm run dev
Access API: http://localhost:5000
Swagger Docs: http://localhost:5000/api-docs
```

### Sample Endpoints
```bash

-> Method	Endpoint	Description
-> POST	/api/auth/register	Register user
-> POST	/api/auth/login	Login & get JWT
-> GET	/api/products	Fetch all products
-> POST	/api/cart/add/:id	Add item to cart
-> POST	/api/orders/create	Place an order
```

All using postman..........

📄 License
MIT © 2025 — Built for scalable ecommerce solutions

