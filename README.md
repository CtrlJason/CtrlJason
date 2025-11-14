<h1 align="center">
  👾 Yeison Mosquera — Full Stack Developer
</h1>

<p align="center">
  <b>Building scalable web applications with React, NestJS & TypeScript.<br>
  Currently @ <a href="https://cloudcity.com.co">CloudCity Colombia</a></b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yeison-david-mosquera-murillo-55a142222/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=fff&style=flat-square" alt="LinkedIn"></a>
  <a href="mailto:yeisondamosquera@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=fff&style=flat-square" alt="Gmail"></a>
  <a href="https://wa.link/ygzb40" target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?logo=whatsapp&logoColor=fff&style=flat-square" alt="WhatsApp"></a>
  <a href="https://j-dev-solutions-m9394x7x4-ctrljasons-projects.vercel.app/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=fff&style=flat-square" alt="Portfolio"></a>
</p>

---

## 👨‍💻 About Me

Full Stack Developer building web applications with React, TypeScript, and Node.js. I've worked on enterprise projects ranging from game development to platform refactoring and e-commerce systems. I focus on writing clean, maintainable code and learning from each project.

- 🚀 **Current Role:** Full Stack Developer at [CloudCity Colombia](https://cloudcity.com.co)
- 🎯 **Experience:** 9 months formal + internship | Building production applications
- 🌱 **Currently Learning:** Advanced English (A2 → B2), improving architectural patterns
- 💡 **Approach:** Solve problems pragmatically, leverage modern tools, keep learning

---

## 🛠️ Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=000&style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff&style=flat-square)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff&style=flat-square)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=fff&style=flat-square)
![Astro](https://img.shields.io/badge/Astro-FF5D01?logo=astro&logoColor=fff&style=flat-square)

### Backend
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=fff&style=flat-square)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=fff&style=flat-square)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=fff&style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=flat-square)

### Databases & ORMs
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=fff&style=flat-square)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?logo=mongoose&logoColor=fff&style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=fff&style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff&style=flat-square)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=fff&style=flat-square)

### DevOps & Tools
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff&style=flat-square)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=fff&style=flat-square)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=fff&style=flat-square)

### Other
![Godot](https://img.shields.io/badge/Godot-478CBF?logo=godot-engine&logoColor=fff&style=flat-square)
![React Query](https://img.shields.io/badge/React_Query-FF4154?logo=react-query&logoColor=fff&style=flat-square)
![Axios](https://img.shields.io/badge/Axios-5A29E4?logo=axios&logoColor=fff&style=flat-square)
![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=fff&style=flat-square)

---

## 🚀 Featured Projects

### 🎮 Educational Games Suite — Cámara de Comercio Bogotá
**3 entrepreneurship games | 4-month development cycle**

⚠️ *Proprietary project — code under NDA*

Developed 3 interactive educational games about entrepreneurship for a Colombian government institution public event.

**My Responsibilities:**
- Full game development and programming in Godot Engine
- Animations using Adobe Animate and AnimatedSprite nodes
- Project organization and modular architecture
- SCORM packaging for LMS integration
- Documentation and QA testing

**Technical Highlights:**
- **Architecture:** Modular design with reusable components (globals, layouts, mini-games, modals)
- **Systems:** Save/load system, analytics tracking, settings management
- **Challenge:** Limited Godot documentation, aggressive timeline (3 games in 3 months + testing)

**Result:** ✅ Successfully delivered all 3 games on schedule, deployed at public event

**Stack:** Godot, GDScript, Adobe Animate, SCORM

---

### 🏗️ Falcon — Wheelchair Assistance Platform Refactoring
**Complete architectural overhaul of airport wheelchair service platform**

⚠️ *Proprietary project — CloudCity Colombia*

Refactored a production web application for managing wheelchair runners at airports. The platform connects supervisors who assign services to mobile app runners.

**The Problem:**
- Chaotic React codebase with all business logic in Context components
- Poor separation of concerns (components, pages, styles mixed)
- Weak TypeScript typing and inconsistent patterns
- Express backend with all logic in route handlers
- No clear project structure or architectural patterns

**My Solution (80% of refactoring work):**

**Frontend:**
- Separated business logic into custom hooks
- Contexts refactored to only transmit data via providers
- Implemented React Query for server state management
- Integrated Axios for API calls
- Added React Hot Toast for notifications
- Proper TypeScript typing throughout
- Implemented React Hook Form with Zod validation

**Backend:**
- Implemented repository pattern for database operations (Mongoose models)
- Created service layer for business logic
- Extracted utilities for reusable code
- Routes now only handle HTTP requests/responses
- Improved MongoDB queries and indexing

**Results:**
- ✅ Clean, maintainable architecture following industry patterns
- ✅ Proper separation of concerns (repositories, services, utils)
- ✅ Delivered in 5 days under tight deadline
- ✅ Successfully deployed to production

**Stack:** React, TypeScript, Express, Mongoose, MongoDB, React Query, Axios, Socket.io

---

### 🎓 Moodle LMS Migration — ANLA
**Enterprise-level migration from Moodle 4.1.3 to 5.1 LTS**

⚠️ *Ongoing project — CloudCity Colombia*

Large-scale migration for Colombia's National Environmental Licensing Authority (ANLA).

**Scope:**
- 32 course versions across 9 different courses
- Plugin compatibility testing and updates
- Custom business logic migration (registration forms, enrollment rules, certificates)
- AI assistant integration (GeniAI plugin)
- Custom Excel reporting modules for characterization data and surveys

**My Role (Team of 3 developers):**
- Full-stack development support across migration tasks
- Expected responsibilities: Course migration, plugin updates, custom module development

**Technologies:** Moodle 5.1 LTS, PHP, MySQL, JavaScript, GeniAI Plugin

**Timeline:** 2 months | **Status:** In progress

---

### 🐾 Mascotas Eddisson
**Pet health management & natural food e-commerce platform** *(Independent Client Project)*

Full-stack web platform and mobile app for pet health tracking and natural food ordering.

**Core Features:**
- **Pet Management:** Registration with photos, breed, age, clinical records, and medical history
- **Health Tracking:** Weight monitoring with automated food recommendations
- **E-commerce:** Natural food catalog with customizable protein options and ingredients
- **Shopping Cart:** Order management with payment gateway integration (MercadoPago/PayU)
- **Order Tracking:** Real-time notifications (processing, shipped, delivered)
- **Admin Dashboard:** User/pet management, daily order control, sales reports and statistics

**Technical Implementation:**
- **Frontend:** React 19, TypeScript, React Query, React Hook Form, Zod validation
- **Backend:** NestJS, Prisma ORM, PostgreSQL
- **Auth:** JWT with httpOnly cookies, bcrypt password hashing
- **Storage:** Cloudinary for image management
- **Email:** Nodemailer with Handlebars templates
- **Mobile:** React Native app planned

**Status:** MVP in development (2-4 months timeline)

**Stack:** React, TypeScript, NestJS, Prisma, PostgreSQL, React Query, Cloudinary

---

### 👴 Hogar Abuela Sara
**Senior care landing page** *(Independent Client Project)*

Single-page application for senior care service marketing and information.

**Original Scope:** Full platform with doctor dashboard (reduced due to budget constraints)

**Delivered:**
- Clean, accessible UI optimized for target audience
- Service information and pricing
- Contact integration
- Responsive design

**Stack:** React, Django, Python, Tailwind CSS

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=CtrlJason&theme=radical&show_icons=true&hide_border=true&count_private=true" alt="GitHub Stats" width="420">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CtrlJason&theme=radical&show_icons=true&hide_border=true&layout=compact" alt="Top Languages" width="320">
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=CtrlJason&theme=radical&hide_border=true" alt="GitHub Streak">
</div>

---

## 💼 What I Bring

- **Adaptability:** I learn new technologies quickly when projects require it (picked up Godot in 1 month for game delivery)
- **Practical Problem Solving:** I find solutions that work, even under tight deadlines
- **Full-Stack Capability:** Comfortable working across frontend, backend, and databases
- **Architectural Awareness:** I understand separation of concerns and can refactor messy codebases into maintainable structures
- **Tool Leverage:** I use AI and modern tools effectively to boost productivity without compromising quality
- **Production Experience:** I've shipped real applications used by actual users and businesses
- **Continuous Learning:** Still growing - I make mistakes, learn from them, and improve with each project

---

## 📬 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/yeison-david-mosquera-murillo-55a142222/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=fff&style=flat-square" alt="LinkedIn"></a>
  <a href="mailto:yeisondamosquera@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=fff&style=flat-square" alt="Gmail"></a>
  <a href="https://wa.link/ygzb40" target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?logo=whatsapp&logoColor=fff&style=flat-square" alt="WhatsApp"></a>
  <a href="https://j-dev-solutions-m9394x7x4-ctrljasons-projects.vercel.app/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=fff&style=flat-square" alt="Portfolio"></a>
</p>

---

<p align="center">
  <i>Open to remote opportunities | English: B1 (in progress)</i><br>
  <b>Last updated: November 2025</b>
</p>
