# 🍽️ Restaurant Management System (Full-Stack MERN Project)

### 🚀 A complete restaurant ecosystem with real-time order tracking, analytics, and user ordering app — built using the **MERN stack**.


---

## 📁 Project Overview

This repository brings together three independently deployed applications — **User App**, **Restaurant Dashboard**, and **Backend API** — into a single organized project hub.

| Module | Description | Deployment |
|---------|--------------|-------------|
| 👤 **User App** | Interactive food ordering interface for customers with category filtering, infinite scrolling, and smooth checkout. | [🔗 Live Demo]([#](https://usersappt.netlify.app/)) |
| 🍴 **Restaurant Dashboard** | Real-time restaurant control panel with analytics, table management, chef assignments, and order tracking. | [🔗 Live Demo]([#](https://restaurantpp.netlify.app/)) |
| ⚙️ **Backend API** | Node.js + Express server managing data flow between the restaurant and user apps, connected to MongoDB. | [🔗 API Endpoint]([#](https://hotelbackend-7ibf.onrender.com)) |

---

## 🧠 Features at a Glance

### 👤 **User App**
- 🧾 Popup form for collecting user details (name, people count, address, etc.) with validation & localStorage persistence  
- 📱 Infinite scroll pagination for food items and category-wise filters  
- 🔍 Live search functionality  
- ➕ Dynamic quantity controls for adding/removing items  
- 🍽️ Option to choose **Dine-in / Takeaway** with real-time order cost  
- 🧾 Swipe-to-confirm order screen  
- ⏱️ Auto redirect after successful order submission  
- 🧮 Data synced to backend via REST API

<img width="425" height="704" alt="image" src="https://github.com/user-attachments/assets/59497024-3642-4936-ace8-1e1692fef164" />

---

### 🍴 **Restaurant Dashboard**
- 📊 **Analytics Page** showing:
  - Total Chefs 👨‍🍳
  - Total Revenue 💰
  - Total Clients 👥
  - Total Orders 🍱  
  - Weekly/Monthly/Yearly donut and line charts  
  - Real-time table availability (green = occupied, white = free)
  - Chef orders summary table  
- 🪑 **Tables Page** for dynamically adding tables with number of chairs and viewing stored DB entries  
- 🕒 **Orders Page** showing live order cards with timers (color-coded for dine-in/takeaway)  
- 🍔 **Items Page** displaying the menu items fetched from database  

<img width="1898" height="881" alt="image" src="https://github.com/user-attachments/assets/45abab31-a83f-4b45-8230-fe784cc15646" />
<img width="1900" height="877" alt="image" src="https://github.com/user-attachments/assets/5e74d6cb-9607-43be-a95c-62b036aac6fe" />


---

### ⚙️ **Backend API**
- Built with **Node.js**, **Express**, and **MongoDB**
- RESTful endpoints for orders, items, tables, and chefs
- Mongoose models for structured schema
- Input validation & error handling
- CORS and environment-based configuration for production deployment

---

## 🏗️ Tech Stack

| Layer | Technologies |
|--------|---------------|
| Frontend | React.js, React Router, Chart.js / Recharts |
| Backend | Node.js, Express.js |
| Database | MongoDB (Mongoose ODM) |
| Hosting | Netlify (Frontend), Render / Vercel (Backend) |
| Others | LocalStorage, Context API, REST API integration |

---

## 🧩 Folder Structure
```
finalProject/
├── user/ # Frontend - Customer Ordering App
├── restaurant/ # Frontend - Restaurant Dashboard
└── backend/ # Node.js + Express API
```

Each module has its own README for detailed setup instructions.

---

## ⚡ Setup Instructions

```bash
# Clone the main project
git clone https://github.com/htanmai/finalProject.git
cd finalProject

# Initialize submodules (if using them)
git submodule update --init --recursive

# Navigate to individual modules
cd user
npm install
npm start

cd ../restaurant
npm install
npm start

cd ../backend
npm install
npm run dev
```

## 🧠 Future Enhancements

- 🔐 JWT Authentication for user login

- 💬 Real-time order updates using WebSockets

- 📈 Exportable analytics reports

## ✨ Author

👨‍💻 Hekkadka Tanmai
📍 Hyderabad, Telangana
📧 htanmai.23@gmail.com
