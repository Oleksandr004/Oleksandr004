# Oleksandr (Sasha) — Fullstack / Frontend Developer

> Pragmatic fullstack developer delivering working solutions for business and e-commerce applications. From frontend prototype to backend deployment — I turn ideas into production-ready products.

---

## 🔎 About Me
- **Name:** Oleksandr (Sasha), 18 years old, Ireland (temporary protection)  
- **Profile:** Fullstack developer with commercial freelance experience and independent projects.  
- **Approach:** Delivery-focused, pragmatic, deadline-oriented. I prioritize working solutions and clear documentation over theory.

---

## 🛠 Technologies & Stack

**Frontend (confident/practical)**
- **React / Next.js (app-directory)** — modern web applications  
- **TypeScript, Redux, Zustand, React Hook Form** — state management, form handling  
- **Responsive Layout:** Flexbox, Grid, Tailwind CSS, SCSS Modules  
- **Animations:** CSS transitions, framer-motion  
- **UI Components:** Radix UI, Recharts

**Backend**
- **Node.js, Express.js, NestJS** — structured backend (controller → service → repository)  
- **Databases:** MongoDB (Atlas), PostgreSQL (via Prisma ORM)  
- **Authentication:** JWT, role-based authorization  
- **APIs:** REST API, CRUD operations, DTO/validation (Zod planned)  
- **Extras:** Redis caching, queues (BullMQ), WebSocket real-time updates

**DevOps / Tools**
- Docker, docker-compose  
- Git / GitHub versioning  
- CI/CD (basic GitHub Actions pipelines planned)  
- Deployment: Vercel, Render, Railway  

---

## ✅ Selected Projects

### 💍 Jewellery Store — Fullstack Online Jewellery Store
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue?style=flat-square) ![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react) ![Express](https://img.shields.io/badge/Express.js-5.x-green?style=flat-square) ![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-brightgreen?style=flat-square&logo=mongodb) ![SCSS](https://img.shields.io/badge/SCSS-Modules-CC6699?style=flat-square&logo=sass) ![Zustand](https://img.shields.io/badge/Zustand-Global%20State-orange?style=flat-square) ![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

**Описание:** полнофункциональный fullstack интернет-магазин ювелирных изделий на React (TypeScript) + Express + MongoDB.  

**Основной функционал:**  
- 🔐 Регистрация и авторизация (JWT + cookies)  
- 🛒 Корзина покупок (Zustand для глобального состояния)  
- 📦 Просмотр товаров с фильтрацией и сортировкой  
- 💬 Система комментариев для товаров и блога  
- 📰 Блог с системой комментариев  
- 🔑 Восстановление пароля  
- 📱 Полностью адаптивный UI (SCSS Modules + MUI)  
- 🎞️ Слайдер на главной странице  
- 🔍 Поиск и фильтрация товаров  
- 👤 Личный кабинет пользователя  
- 🛡️ Безопасность (Helmet, rate limiting, XSS защита, MongoDB sanitization)  

**Технологии:**  
- **Frontend:** React 19, TypeScript 5.8, Vite 6, React Router DOM 7, Zustand 5, React Hook Form 7, SCSS Modules, Material-UI 7, Swiper 11, Axios  
- **Backend:** Node.js, Express 5, MongoDB, Mongoose 8, JWT, bcrypt, Helmet, express-rate-limit, express-mongo-sanitize, xss-clean, hpp, compression, cookie-parser, CORS  

---

### ⚡ Energy Dashboard — Fullstack Energy Management Dashboard

**Описание:** веб-приложение для мониторинга энергопотребления с интеграцией Censo API, визуализацией данных и административной панелью.  

**Основной функционал:**  
- 🔌 Мониторинг потребления и производства электроэнергии  
- 🌡️ Отслеживание газопотребления и выбросов CO₂  
- ⚡ Управление зарядными станциями EV  
- 📊 Визуализация метрик и сравнительные графики  
- 📰 Пользовательский и админ интерфейс с ролями и модулями  
- 🌤 Интеграция с погодными API и внешними источниками  

**Технологии:**  
- **Frontend:** React 19, TypeScript, Tailwind CSS 4, Material-UI, React Hook Form, Axios, GSAP, Vite  
- **Backend:** Node.js + TypeScript, Express.js, MongoDB + Mongoose, JWT, bcryptjs, Nodemailer, Axios, CORS, cookie-parser  
---

### 🛡️ Uptime Sentinel — Fullstack Monitoring Platform
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue?style=flat-square) ![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react) ![NestJS](https://img.shields.io/badge/NestJS-11-E0234E?style=flat-square&logo=nestjs) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-blue?style=flat-square&logo=postgresql) ![Redis](https://img.shields.io/badge/Redis-7-DC382D?style=flat-square&logo=redis) ![Docker](https://img.shields.io/badge/Docker-24-blue?style=flat-square&logo=docker) ![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

**Описание:** полноценная система мониторинга доступности сайтов, API и сервисов в реальном времени с современным веб-интерфейсом, уведомлениями в Telegram и детальной аналитикой.

**Основной функционал:**  
- ⚡ Real-time мониторинг веб-сервисов через WebSocket  
- 📊 Детальная аналитика: uptime %, response time, история инцидентов  
- 📱 Telegram уведомления о падениях и восстановлении сервисов  
- 🔐 Безопасная авторизация JWT (access + refresh)  
- 🎨 Адаптивный и современный интерфейс  
- 📦 Экспорт данных в CSV/PDF  
- 🚀 Масштабируемая архитектура с BullMQ, Redis и PostgreSQL  

**Технологии:**  
- **Frontend:** Next.js 16, React 19, TypeScript, Tailwind, Framer Motion, Recharts, Radix UI, FSD (Feature-Sliced Design)  
- **Backend:** NestJS 11, TypeScript, Prisma, PostgreSQL, Redis, BullMQ, JWT, WebSocket Gateway, Telegram Bot (Telegraf), Swagger  
- **DevOps:** Docker, docker-compose, CI/CD (GitHub Actions), деплой на Vercel / Render / Railway  

**Особенности архитектуры:**  
- FSD структура: frontend — entities / features / widgets / shared  
- Backend: auth / monitor / events / notify / prisma  
- Реализованы очереди проверок, Telegram уведомления, JWT авторизация  
- Полное покрытие тестами (unit + E2E, Jest, Vitest, Cypress)  

**Преимущества для клиента:**  
- Готовое production-ready решение для мониторинга  
- Легко масштабируется и расширяется новыми сервисами  
- Прозрачная документация и инструкции по деплою  


---


## 🚀 How I Work / What You Get
- Чёткие оценки сроков и фиксированная цена  
- Предоплата 20–30% для крупных задач  
- Доставка: рабочий релиз + README + инструкции по деплою  
- Поддержка: исправление багов после релиза (по договорённости)  
- Прозрачная коммуникация и документация для лёгкой передачи проекта  

---

## 📫 Contact / Hire Me 
- Email: oleksandrzabolotniy04@gmail.com  
- Open to freelance and remote opportunities (fullstack/frontend focus)  

---
