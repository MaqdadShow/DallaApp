# 🛒 Dalla E-Commerce Mobile Application

A mobile e-commerce platform built with **React Native** for the frontend and **Python microservices** for the backend. The app functions similarly to platforms like Amazon and Facebook Marketplace, allowing users to browse products, upload items for sale, manage listings, and place orders.

## 📱 Features

### 🔐 User Accounts
- Register and create new accounts  
- Login & logout  
- Change password  
- Persistent user sessions  

### 🛍 Product Management
- Upload product images  
- Add product details:
  - Name
  - Description
  - Price
  - Quantity  
- Retrieve product lists and details  

### 📦 Order Tracking
- Place new orders  
- Generate order IDs  
- Save and manage order records  
- Track purchase history  

## 🧰 Tech Stack

### Frontend
- **React Native**  
- Responsive, mobile-friendly UI  
- Communicates with backend via HTTPS API  

### Backend – Python (Three Services)

#### 1️⃣ User Management Service
- Handles registration, login/logout, password updates  
- **Libraries Used:** os, websockets, asyncio, json, time  

#### 2️⃣ Product & Media Service
- Handles image upload and product metadata storage (name, description, price, quantity)  
- **Libraries Used:** flask, flask_cors, werkzeug.utils, uuid, json, os, time  

#### 3️⃣ Order Tracking Service
- Handles new order creation, order status, and tracking  
- **Libraries Used:** http.server, uuid, json, os, time  

### ☁️ Cloud & Deployment
- **AWS EC2** for hosting backend services  
- **AWS Load Balancer** for traffic distribution  
- Port forwarding for external access  
- Custom domain for API endpoints  

## 🚀 How It Works
1. The user interacts with the mobile app  
2. The frontend sends HTTPS requests to the backend services  
3. Each service handles a specific system responsibility:
   - **User Service:** Authentication  
   - **Product Service:** Data & image storage  
   - **Order Service:** Purchase management  

## 🔧 Possible Improvements
- Add JWT authentication  
- Containerize services with Docker  
- Implement a proper database backend (PostgreSQL, MongoDB)  
- Add push notifications for orders and updates  

## 🙌 Author
Developed by Maqdad Asheer (Developer), k7k7 (Developer), bosi (Designer)
