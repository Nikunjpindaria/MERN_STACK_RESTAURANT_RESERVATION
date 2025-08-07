# 🍽️ MERN Restaurant Reservation App

A full-stack restaurant reservation system built with the **MERN stack** (MongoDB, Express, React, Node.js), enabling seamless booking and management for both customers and restaurant owners.

---

## 🚀 Features

- 🔐 **User Authentication**: Customers and admins can register, log in, and manage their bookings.
- 🧑‍💼 **Admin Dashboard**: Restaurant owners manage reservations and restaurant details.
- 🌐 **Responsive Frontend**: Built with React and styled for both desktop and mobile.
- 💬 **Real-time Updates (optional)**: Uses WebSocket/Sockets for live reservation status changes.

---

## 🛠 Technologies Used

| Layer     | Tech Stack                                                            |
|-----------|-----------------------------------------------------------------------|
| Backend   | Node.js, Express.js, MongoDB, Mongoose     |
| Frontend  | React.js, React Router, Context API  |
---

## 📂 Folder Structure (example)

```text
backend/        # Server-side files (Node, Express, APIs)
frontend/       # Client-side React app
  ├── public/
  └── src/
README.md       # Project overview & instructions
.env.example    # Environment variable template

# Clone the repository
git clone https://github.com/Nikunjpindaria/MERN_STACK_RESTAURANT_RESERVATION.git
cd MERN_STACK_RESTAURANT_RESERVATION

# Backend setup:
cd backend
cp .env.example .env
# Edit .env: add PORT, MONGO_URI, FRONTEND_URL
npm install
npm start

# Frontend setup (in separate terminal):
cd ../frontend
npm install
npm start

