# 🏠 SmartHomeSetu — High-Tech Student-Centric PG Discovery & Booking Ecosystem

[![React](https://img.shields.io/badge/Frontend-React.js%2019-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![Spring Boot](https://img.shields.io/badge/Backend-Spring%20Boot%203.2-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Language-Java%2017-ED8B00?logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Database](https://img.shields.io/badge/Database-MySQL%20%7C%20H2-4479A1?logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Vite](https://img.shields.io/badge/Bundler-Vite%208-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-22c55e?logo=github&logoColor=white)](https://arshmittal0907.github.io/SmartHomeSetu/)

> **SmartHomeSetu: High-Tech Student Accommodation & PG Management Platform**  
> Direct peer-to-peer connection between college students and verified PG hosts with **0% brokerage**, **upfront transparent pricing**, **1-to-1 owner booking request dispatch**, **15-state AI intelligence**, and **verifiable Confirmation IDs**.

🌐 **Live Global Link:** [https://arshmittal0907.github.io/SmartHomeSetu/](https://arshmittal0907.github.io/SmartHomeSetu/)

---

## 🎯 Key Capabilities & High-Tech Features

### 1. Mandatory Role-Based Registration & Authentication
* **Zero Synthetic Accounts:** New students and PG owners must explicitly register with their credentials (name, email, phone, college/student ID, or PG property details) before logging in.
* **Security & Segregation:** Student portal, PG Owner portal, and Central Administrator portal maintain strict role-based access control.

### 2. Verified Host Identity & 1-to-1 Booking Request Routing
* **Owner Host Badges:** Every PG card visibly displays the verified host's name and contact information.
* **Isolated Request Dispatch:** When a student requests a room, the booking notification routes exclusively to that specific PG host's dashboard.

### 3. 15 Indian States × 15 Educational Hubs (225 Locations Directory)
* **Master Coverage:** New PG listings feature dropdowns for 15 major Indian states and 15 renowned educational hubs per state (e.g., Kothrud, Hinjewadi, Koramangala, Indirapuram, Knowledge Park, Kota, etc.).
* **1-Click AI Benchmark:** Instant estimation of market rent based on selected locality and room amenities.

### 4. Dual Omni-AI Agents
* **Student AI Living Advisor:** Trained across 15 states with regional food profiles, rent spectrums, curfew regulations, and boys/girls safety guidelines.
* **Owner Market Yield Advisor:** Real-time pricing calculator, ROI advisor, and occupancy optimizer.

### 5. Campus Living Tools
* **College Commute Calculator:** Real-time transit cost and travel time estimation for walking, cycling, and public transport.
* **Nearby Essentials Map:** Visual radar for nearby libraries, mess halls, gyms, hospitals, and ATMs.
* **Side-by-Side Comparison:** Interactive matrix comparing up to 3 PGs across 12 distinct parameters.

---

## 📁 Repository Structure

```text
SmartHomeSetu/
├── backend/                       # Spring Boot 3.2 Java Backend
│   ├── src/main/java/             # Controllers, Entities, Repositories, Services
│   ├── src/main/resources/        # application.properties & SQL schemas
│   └── pom.xml                    # Maven dependencies
├── frontend/                      # React 19 + Tailwind CSS + Vite
│   ├── src/                       # Application components, context, and state
│   │   ├── components/            # UI Modals, Dashboards, Cards, and AI Portals
│   │   ├── context/               # AuthContext & Session management
│   │   ├── statesData.js          # 15 States x 15 Localities Master Directory
│   │   ├── featuresData.js        # Commute, reviews, essentials data models
│   │   ├── api.js                 # Unified API client & standalone fallback
│   │   └── App.jsx                # Main Application root
│   ├── dist/                      # Production-ready built assets
│   ├── package.json               # Dependencies & scripts
│   └── vite.config.js             # Vite configuration
├── scripts/                       # Deployment automation scripts
│   └── deploy-ghpages.js          # 1-Click GitHub Pages deployment automation
├── run-all.bat                    # One-click full-stack launcher
├── run-frontend.bat               # Frontend launcher
└── run-backend.bat                # Backend launcher
```

---

## 🚀 Running Locally

### Prerequisites
* **Node.js**: v20+ or v22+
* **Java**: JDK 17 or higher
* **Maven**: 3.8+ (optional, wrapper included)

### 1. Launch Frontend
```bash
cd frontend
npm install
npm run dev
```
Open [http://localhost:5173/homesetu/](http://localhost:5173/homesetu/) in your browser.

### 2. Launch Backend (Optional for standalone use)
```bash
cd backend
mvn spring-boot:run
```

---

## 🌐 Deploy to GitHub Pages

To build and deploy the latest frontend to GitHub Pages:
```bash
node scripts/deploy-ghpages.js
```
The live site will update automatically at [https://arshmittal0907.github.io/SmartHomeSetu/](https://arshmittal0907.github.io/SmartHomeSetu/).

---

## 📄 License
Academic and High-Tech Project Submission — Built with ❤️ for college students across India.
