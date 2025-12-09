<div align="center">

# 🎵 BeatMatch
### The Ultimate Hub for Musicians & Event Organizers

<p align="center">
  A full-stack ecosystem bridging the gap between professional talent and event planners in Israel.
  <br />
  <b>Discover. Connect. Perform.</b>
</p>

<br />

| 🌐 **Live Platform** | 💻 **Frontend Source** | 🔌 **Backend Source** |
|:---:|:---:|:---:|
| [![Website](https://img.shields.io/badge/Visit-Live_Site-00D9FF?style=for-the-badge&logo=google-chrome&logoColor=white)](https://beatmatchfrontweb.onrender.com/) | [![Frontend](https://img.shields.io/badge/View-Frontend_Repo-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://github.com/NEO-YC/BeatMatchFrontWeb) | [![Backend](https://img.shields.io/badge/View-Backend_Repo-68A063?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://github.com/NEO-YC/BeatMatchBackWeb) |

<br />

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

</div>

---

## 📋 Table of Contents

- [🎯 Overview](#-overview)
- [✨ Key Features](#-key-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🏗️ Architecture](#️-architecture)
- [🚀 Quick Start](#-quick-start)
- [💳 Monetization (PRO)](#-monetization-pro)
- [👥 Authors](#-authors)

---

## 🎯 Overview

**BeatMatch** solves a common industry friction: Event organizers struggle to find specific musical talent within budget and location, while talented musicians lack a centralized platform to showcase their work.

### The Solution
A dedicated marketplace featuring smart filtering, rich media profiles, and a secure environment for connecting artists with clients.

<div align="center">
  <img src="https://via.placeholder.com/800x400.png?text=BeatMatch+Dashboard+Preview" alt="BeatMatch Preview" width="100%" />
</div>

---

## ✨ Key Features

### 🎸 For Musicians
* **Professional Portfolio:** Showcase bio, experience, and musical styles.
* **Media Gallery:** Integrated YouTube links and image uploads (Cloudinary).
* **PRO Membership:** Unlock the "Gold Badge," priority ranking, and increased exposure.
* **Availability Management:** Real-time calendar updates.

### 🎭 For Organizers
* **Smart Search:** Filter by instrument, genre, region, and budget.
* **Direct Contact:** Connect via WhatsApp, Phone, or Email instantly.
* **Verified Reviews:** View ratings and feedback before booking.
* **Event Posting:** Publish event requirements and receive applications.

### 🛡️ Admin Dashboard
* Comprehensive user management.
* Role-based access control (RBAC).
* Analytics and reporting.

---

## 🛠️ Tech Stack

### **Frontend** (Client Side)
| Tech | Description |
| :--- | :--- |
| ⚛️ **React 18** | UI Library for building interactive interfaces |
| ⚡ **Vite** | Next Generation Frontend Tooling |
| 🎨 **Vanilla CSS** | Custom styling without heavy frameworks |
| 🧭 **React Router** | Client-side routing and navigation |
| 🔐 **JWT Decode** | Secure token handling |

### **Backend** (Server Side)
| Tech | Description |
| :--- | :--- |
| 🟢 **Node.js** | JavaScript runtime environment |
| 🚂 **Express.js** | Fast, unopinionated web framework |
| 🍃 **MongoDB** | NoSQL Database (via Atlas) |
| 💳 **PayPal API** | Secure payment processing for PRO upgrades |
| ☁️ **Cloudinary** | Image and video management CDN |
| 🔐 **Bcrypt & JWT** | Security, hashing, and authentication |

---

אני מבין. נשלח לך את החלק המבוקש מהארכיטקטורה ועד הסוף, כשהפעם נמנע מכל סמליל או עיצוב שעלול ליצור בעיות תצוגה ב-GitHub. כל הטקסט יהיה באנגלית.

🏗️ Architecture
The project follows a classic decoupled MERN architecture hosted on Render.

📂 Ecosystem Overview
BeatMatch Ecosystem

💻 Frontend (React + Vite): Handles User Interface, Search, and Payment UI.

🔌 Backend (Node.js + Express): Manages RESTful API, Authentication, and Database Models.

☁️ External Services: MongoDB Atlas, Cloudinary CDN, PayPal Payment Gateway.

🚀 Quick Start
Since the repositories are separated, here is how to get the ecosystem running locally.

Prerequisites
Node.js >= 16.x

npm or yarn

Account for MongoDB Atlas

Account for PayPal Developer (Sandbox)

Account for Cloudinary

1. Clone and Install the Repositories
Bash

# Clone Frontend
git clone https://github.com/NEO-YC/BeatMatchFrontWeb.git
cd BeatMatchFrontWeb
npm install

# Clone Backend (in a separate terminal)
git clone https://github.com/NEO-YC/BeatMatchBackWeb.git
cd BeatMatchBackWeb
npm install
2. Environment Setup
Backend (.env file)

MONGODB_URI=your_mongodb_connection_string
PORT=3000
JWT_SECRET=your_super_secret_key_min_32_chars
JWT_EXPIRE=7d

PAYPAL_MODE=sandbox
PAYPAL_CLIENT_ID=your_sandbox_client_id
PAYPAL_CLIENT_SECRET=your_sandbox_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

FRONTEND_URL=http://localhost:5173
Frontend (.env file)

VITE_API_URL=http://localhost:3000
VITE_PROFILE_ACTIVATION_AMOUNT=49
3. Run Locally
Bash

# Terminal 1 - Backend
cd BeatMatchBackWeb
npm start
# Server: http://localhost:3000

# Terminal 2 - Frontend
cd BeatMatchFrontWeb
npm run dev
# App: http://localhost:5173
💳 Monetization (PRO)
We implemented a real-world business model using PayPal:

Free Tier: Basic profile creation.

PRO Tier (49₪):

Gold Badge next to the name.

Top placement in search results.

Higher trust factor for organizers.

👥 Authors
<table align="center"> <tr> <td align="center"> <a href="https://github.com/NEO-YC"> <img src="https://github.com/NEO-YC.png" width="100px;" alt="Neorai"/><br /> <sub><b>Neorai</b></sub> </a><br /> Full Stack Developer </td> <td align="center"> <a href="https://github.com/danielnisenholz"> <img src="https://github.com/danielnisenholz.png" width="100px;" alt="Daniel"/><br /> <sub><b>Daniel</b></sub> </a><br /> Full Stack Developer </td> </tr> </table>

<div align="center">

BeatMatch © 2025 | Made with ❤️|🧠.

</div>
