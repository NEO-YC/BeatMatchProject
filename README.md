BeatMatch Project

A full-stack platform connecting musicians, producers, and event organizers.
Includes links to the live website, the frontend repository, and the backend repository.

✨ Status: Currently in development (≈70%)

🌐 Live Website

https://beatmatchfrontweb.onrender.com/

📦 Repositories
Frontend

React + Vite
🔗 https://github.com/NEO-YC/BeatMatchFrontWeb

Backend

Node.js + Express + MongoDB
🔗 https://github.com/NEO-YC/BeatMatchBackWeb

🎵 BeatMatch – Platform for Musicians

A modern platform where musicians can build profiles, get discovered, manage availability, and participate in events.
Built full-stack with scalable architecture and integration with PayPal and Cloudinary.

🚀 Features

🎸 Musician profile creation

🔍 Smart search filters

⭐ PRO membership for premium visibility

💳 PayPal payment integration

🖼️ Media upload via Cloudinary

📅 Availability calendar

🎵 Event creation & management

🛠️ Tech Stack
Frontend

React 18

React Router

Vite

CSS3

Backend

Node.js

Express.js

MongoDB (Mongoose)

JWT Authentication

PayPal REST API

Cloudinary API

📂 Project Structure
BeatMatchProject/
├── Server/
│   ├── Controllers/
│   ├── Models/
│   ├── Routers/
│   ├── Middleware/
│   ├── .env.example
│   └── index.js
│
└── Client/
    ├── public/
    └── src/
        ├── components/
        ├── pages/
        └── services/

⚙️ Setup Instructions
Backend Setup
cd Server
npm install
cp .env.example .env
npm start


Runs at http://localhost:3000

Frontend Setup
cd Client
npm install
npm run dev


Runs at http://localhost:5173

🔐 Security Notes

.env is never committed

JWT for authentication

Tokens stored securely on client

PayPal sandbox for testing

CORS configured safely

📡 API Examples
Public
POST /user/register
POST /user/login
GET  /user/musicians/search
GET  /user/musicians/:id

Protected (requires JWT)
PUT    /user/musician/profile
GET    /user/me/musician-profile
POST   /user/payments/create
POST   /user/payments/capture
DELETE /user/account

⭐ Membership System
Free

Create musician profile

Basic browsing

Limited search visibility

PRO

PRO badge

Higher ranking

Priority search placement

Expanded dashboard

📄 License

Educational purposes only.
