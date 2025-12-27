# ✈️ Travel Agency Platform


<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success" />
  <img src="https://img.shields.io/badge/Frontend-React%2019-blue" />
  <img src="https://img.shields.io/badge/Build-Vite-purple" />
  <img src="https://img.shields.io/badge/Styling-TailwindCSS-cyan" />
  <img src="https://img.shields.io/badge/Backend-Appwrite-orange" />
</p>

<p align="center">
  <strong>A full‑stack, production‑style Travel Agency application with AI‑assisted trip planning, booking, and an advanced admin dashboard.</strong>
</p>

---

## 🧭 Overview

This project is a modern **travel booking and management platform** designed to simulate a real‑world SaaS product. It includes a public website for users to explore and book trips, and a protected admin dashboard to manage trips, users, and analytics.

The goal of this project is not just UI — but **architecture, scalability, and real integrations**.

---

## 🎯 Why this project matters

✅ Mirrors real production applications
✅ Demonstrates modern frontend & backend integration
✅ Excellent portfolio project for frontend / full‑stack roles
✅ Focuses on clean architecture, not just visuals

This project can be adapted for:

* Travel startups
* Admin dashboards
* SaaS analytics panels
* AI‑powered content generation apps

---

## 🧠 What I learned building this

* Designing scalable **React application architecture**
* Using **React Router v7** for nested & protected routes
* Managing global state and derived data efficiently
* Building responsive UIs with **Tailwind CSS**
* Integrating **AI APIs** to generate structured content
* Secure authentication and role‑based access control
* Handling payments and bookings workflow
* Visualizing data using charts and tables
* Working with environment‑based configurations
* Writing clean, reusable, and maintainable code

---

## ✨ Key Features

🌍 **AI‑Powered Trip Planner**
Generate travel itineraries based on destination, budget, group type, and interests.

🧳 **Public Booking Platform**
Browse trips, view details, and make bookings.

🛠️ **Admin Dashboard**
Create, edit, and manage trips and users from a single panel.

📊 **Analytics & Insights**
Track user growth, booking trends, and trip performance.

🔐 **Authentication & Security**
Secure login system with protected admin routes.

🖼️ **Dynamic Media Integration**
Auto‑fetch trip images using external image APIs.

📱 **Fully Responsive Design**
Optimized for desktop, tablet, and mobile devices.

🧩 **Modular Codebase**
Reusable components, hooks, and services for easy scaling.

---

## 🛠️ Tech Stack

### Frontend

* ⚛️ React 19
* ⚡ Vite
* 🎨 Tailwind CSS
* 🧭 React Router v7

### Backend & Services

* 🗄️ Appwrite (Auth, Database)
* 🤖 AI API (Itinerary generation)
* 💳 Stripe (Payments)
* 🖼️ Unsplash API (Images)

### Tooling

* 📦 npm
* 🔐 Environment Variables
* 📊 Charting Library

---

## 🚀 Getting Started

### 📋 Prerequisites

* Node.js (LTS)
* npm
* Git

---

### 📥 Installation

```bash
git clone https://github.com/your-username/travel-agency-platform.git
cd travel-agency-platform
npm install
```

---

### 🔑 Environment Variables

Create a `.env` file in the project root:

```env
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_API_ENDPOINT=
VITE_APPWRITE_API_KEY=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_USERS_COLLECTION_ID=
VITE_APPWRITE_ITINERARY_COLLECTION_ID=
VITE_SYNCFUSION_LICENSE_KEY=
GEMINI_API_KEY=
STRIPE_SECRET_KEY=
UNSPLASH_ACCESS_KEY=
VITE_BASE_URL=http://localhost:5173
```

> ⚠️ Never commit `.env` files to version control.

---

### ▶️ Run Locally

```bash
npm run dev
```

Open **[http://localhost:5173](http://localhost:5173)** in your browser.

---

## 🗂️ Project Structure

```
src/
├─ assets/        # images & banners
├─ components/    # reusable UI components
├─ hooks/         # custom React hooks
├─ lib/           # utilities & helpers
├─ routes/        # public & admin routes
├─ services/      # API & backend logic
├─ styles/        # global styles
└─ main.tsx       # application entry point
```

---



⭐ If you found this project helpful, consider starring the repository!
