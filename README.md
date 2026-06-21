# Hi, I'm Abdalla Mahamid 👋

CS graduate based in Germany. I build production systems end-to-end — from database design and distributed architecture to deployment and operations.

Currently administering two organizations KHS-Glass and Clarifood with production platforms serving real users.

---

## 🏢 Organizations

### **KHS Glass** — Glass & Hardware E-commerce Platform
**Live:** [khsglass.com](https://khsglass.com)

A full-stack microservices system supporting a glass business in Israel, serving customers in Hebrew, Arabic, and English.

**Highlights:**
- 🤖 **AI Chatbot** — GPT-4o-mini multilingual support (Hebrew/Arabic/English with RTL/LTR)
- 📷 **Handwritten Order Scanner** — Vision OCR extracts dimensions from handwritten notes; server-side aggregation into m² summaries grouped by glass type
- 🔐 **Secure Admin Panel** — Photo management, measurements, activity audit log with IP tracking
- 🖼️ **Infinite-scroll Gallery** — Optimized image compression (Sharp/libvips → WebP), Supabase Storage integration
- 📊 **Currency Calculator** — Real-time exchange rates with discount management
- ♿ **Accessibility** — Israeli Standard IS 5568 compliant
- 🛡️ **Security Hardened** — CSRF protection, DOMPurify XSS sanitization, rate limiting at gateway, DDoS mitigation

**Tech Stack:**  
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat&logo=railway&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

**Status:** ✅ Live in production  
**Repo:** [github.com/khsglass](https://github.com/khsglass)

---

### **Clarifood** — Food Transparency & Compliance Scanner
**App:** iOS & Android (React Native + Expo)

A mobile app helping consumers understand exactly what's in their food by scanning barcodes and ingredient labels against official EU & FDA databases.

**Features:**
- 📱 **Barcode & Label Scanning** — Real-time product lookup via Open Food Facts integration
- 🔍 **Substance Verification** — Cross-references every ingredient against EU and FDA approved/banned lists
- 🌍 **Regional Compliance** — EU, USA, and international regulatory frameworks
- 🔬 **OCR Pipeline** — Extracts ingredient text from product photos for analysis
- 🎯 **Halal Verification** — In development; classification database upcoming
- 👤 **User Profiles** — Personal scan history and preferences
- 📲 **Push Notifications** — Alerts for flagged substances and new regulations

**Microservices Architecture:**
- **clarifood-mobile** — iOS/Android app (React Native)
- **clarifood-gateway** — API routing, auth, rate limiting
- **clarifood-auth-service** — JWT + OAuth2
- **clarifood-product-service** — Barcode lookup
- **clarifood-substance-service** — EU + FDA compliance engine
- **clarifood-ocr-service** — Label photo → ingredient text
- **clarifood-user-service** — Profiles and scan history
- **clarifood-notification-service** — Push alerts
- **clarifood-data-sync** — Daily substance list updater
- **image-compression-service** — Photo optimization

**Tech Stack:**  
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**Status:** 🔨 In active development (Phase 1: EU + FDA compliance)  
**Repo:** [github.com/Clarifood](https://github.com/Clarifood)

---

## 📚 Public Portfolio

Key projects demonstrating algorithms, systems design, and problem-solving:

| Project | Description | Language | Topic |
|---------|-------------|----------|-------|
| [**CloudDatabase**](https://github.com/abedkhma/CloudDatabase) | Hands-on course: containerization → persistent key-value store design and implementation | Java | Distributed Systems |
| [**Peano-Meander-Curve**](https://github.com/abedkhma/Peano-Meander-Curve) | Space-filling curve generator — recursive algorithm for curve traversal of specified orders | C | Algorithms & Geometry |
| [**Checkers**](https://github.com/abedkhma/Checkers) | Checkers game with Model-View-Controller architecture and game logic | Java | Design Patterns |
| [**Sudoku**](https://github.com/abedkhma/Sudoku) | Backtracking algorithm solver for n×n grids — constraint satisfaction | Python | Algorithms |
| [**Automated-Braking-System**](https://github.com/abedkhma/Automated-Braking-System) | Mechanical design + LabVIEW programming for robot safety device | LabVIEW | Robotics & Control Systems |

---

## 🛠️ Core Tech Stack

**Frontend**  
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

**Backend**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

**Data & Infrastructure**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat&logo=railway&logoColor=white)

**Deployment & CI/CD**  
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

---

## 🎯 Approach & Philosophy

- **Production-first** — Systems designed for reliability, security, and scale from day one
- **Microservices & modularity** — Independent services with clear boundaries and contracts
- **No over-engineering** — YAGNI principle; technologies chosen for actual requirements
- **Audit-then-fix** — Security vulnerabilities identified and hardened systematically
- **End-to-end ownership** — Database schema → deployment → operations

---

## 📊 GitHub Stats

![Abdalla's GitHub stats](https://github-readme-stats.vercel.app/api?username=abedkhma&show_icons=true&theme=default&hide_border=true&count_private=true)

---

## 📬 Contact

- **Email:** [abedkh.gl@gmail.com](mailto:abedkh.gl@gmail.com)
- **KHS Glass Org:** [github.com/khsglass](https://github.com/khsglass)
- **Clarifood Org:** [github.com/Clarifood](https://github.com/Clarifood)
- **Website:** [khsglass.com](https://khsglass.com)

---

<div align="center">
  <sub>Building reliable systems that solve real-world problems</sub>
</div>
