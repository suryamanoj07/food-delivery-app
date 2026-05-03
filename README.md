# 🍔 Food Ordering Application

This is a full-stack online food delivery platform with three main components:

---
<p align="center">
  <img src="https://github.com/user-attachments/assets/3943b3dc-1f44-4570-a1e5-45e9c9a92ce7" width="90%" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/66b2ab7d-5c51-48d0-99fd-3fcfc467878f" width="45%" />
  <img src="https://github.com/user-attachments/assets/26543fe8-73e1-47f2-b1a9-66ceafc1ffac" width="45%" />
</p>



## 🧩 Backend (foodiesapi) — Spring Boot (Java 21)

- **Framework:** Spring Boot 3.4.3 with REST API  
- **Database:** MongoDB (NoSQL)  
- **Authentication:** Spring Security + JWT (jjwt)  
- **Storage:** AWS S3 for images  

### 🔑 Key Entities
- User  
- Food  
- Cart  
- Order  

### 🎮 Controllers
- Auth Controller  
- User Controller  
- Food Controller  
- Cart Controller  
- Order Controller  

### ⚙️ Services
- User/Auth Services  
- Food Services  
- Cart Services  
- Order Services  
- Implemented using interfaces + implementations  

### 🔐 Configuration
- SecurityConfig (JWT authentication & authorization)  
- AWSConfig (S3 integration)  

---

## 💻 Frontend - Foodies (React + Vite)

Customer-facing application for browsing and ordering food.

### 📦 Key Dependencies
- React 18.2  
- React Router 7  
- Axios  
- Bootstrap  
- Razorpay (payment)  

### 📄 Pages
- Home  
- ExploreFood  
- FoodDetails  
- Cart  
- PlaceOrder  
- MyOrders  
- Contact  

### 🧱 Components
- Header  
- Menubar  
- Login/Register  
- FoodDisplay  
- ExploreMenu  
- FoodItem  

### 🌐 State Management
- Global StoreContext  

### 🔗 Services (API Calls)
- authService  
- foodService  
- cartService  
- orderService  

---

## 🛠️ Frontend - Admin Panel (React + Vite)

Admin dashboard for restaurant management.

### 📦 Key Dependencies
- React 19  
- React Router 7  
- Axios  
- Bootstrap  

### 🧱 Components
- Menubar  
- Sidebar  

### 🎯 Purpose
- Admin controls for food and order management  

---

## ✅ Key Functionalities

- User authentication & JWT authorization  
- Browse and search food items  
- Shopping cart management  
- Order placement and tracking  
- Payment integration (Razorpay)  
- Admin panel for food and order management  
- AWS S3 image storage  

---

## 🏗️ Architecture

The application follows:

- 3-tier architecture (Frontend, Backend, Database)  
- RESTful API design  
- MVC pattern on the backend  

---

## 🚀 Getting Started

### Clone the repository
- git clone https://github.com/suryamanoj07/food-delivery-app.git
- cd food-delivery-app

## Backend Setup
- cd backend
- mvn spring-boot:run

## Frontend Setup (User)
- cd frontend
- npm install
- npm run dev

## Admin Panel Setup
- cd admin
- npm install
- npm run dev


## Make sure to configure:
MongoDB connection
JWT secret key
AWS S3 credentials


## 📬 Author
Surya Manoj
