<<<<<<< HEAD
# E-commerce Backend

This is the backend server for the e-commerce application built with FastAPI and SQLAlchemy.

## Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd ecommerce-backend
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Running the Server

1. Start the FastAPI server:
```bash
uvicorn main:app --reload
```

The server will start at `http://localhost:8000`.

## API Documentation

Once the server is running, you can access the API documentation at:
- Swagger UI: `http://localhost:8000/docs`
- ReDoc: `http://localhost:8000/redoc`

## API Endpoints

### Authentication
- `POST /token` - Login and get access token
- `POST /register` - Register a new user

### Users
- `GET /users/me` - Get current user details
- `PUT /users/me` - Update current user details

### Products
- `GET /products` - Get all products with optional filters
- `GET /products/{product_id}` - Get a specific product

### Cart
- `GET /cart` - Get current user's cart
- `POST /cart` - Add item to cart
- `PUT /cart` - Update cart item quantity
- `DELETE /cart/{product_id}` - Remove item from cart

### Orders
- `GET /orders` - Get all orders for current user
- `GET /orders/{order_id}` - Get a specific order
- `POST /orders` - Create a new order

## Database

The application uses SQLite as the database. The database file will be created automatically at `./ecommerce.db` when you first run the application.

## Environment Variables

The following environment variables can be set:

- `SECRET_KEY` - Secret key for JWT token generation (default: "your-secret-key")
- `ALGORITHM` - Algorithm for JWT token generation (default: "HS256")
- `ACCESS_TOKEN_EXPIRE_MINUTES` - Token expiration time in minutes (default: 30) 
=======
# MotionVault — Online Store

A modern and fully responsive online shop built with React.js and Framer Motion.  
Designed for elegant UI, smooth animations, and scalable architecture.

---

## 🚀 Features

- Clean and professional UI
- Fully responsive design (mobile-first)
- Framer Motion animations
- Modular React component structure
- React Hooks and Context API
- Easily extendable for real-world use (API, database, etc.)

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/motionvault.git
cd motionvault
npm install
npm start
MIT License

Copyright (c) 2025
All rights reserved to PAS — AryanaDev.com, Motherf**ker.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
>>>>>>> dd226a48f0e61706e69e7bca3814051fcda84747
