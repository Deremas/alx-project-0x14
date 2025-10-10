# 🎬 CineSeek — API Explorer: Mastering RESTful Connections

![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=nextdotjs) 
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript) 
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-38bdf8?logo=tailwindcss) 
![Status](https://img.shields.io/badge/Status-In_Progress-orange)
![Weight](https://img.shields.io/badge/Project_Weight-1-lightgrey)

> **CineSeek** is a modern movie discovery web application that lets users browse, search, and explore movies using the MoviesDatabase API.  
> Built with **Next.js**, **TypeScript**, and **Tailwind CSS**, this project emphasizes clean architecture, API integration, and responsive design.

---

## 📖 Table of Contents

- [🎯 Project Description](#-project-description)
- [🧠 Learning Objectives](#-learning-objectives)
- [🧰 Tech Stack & Requirements](#-tech-stack--requirements)
- [📁 File Structure](#-file-structure)
- [💡 Best Practices](#-best-practices)
- [🔑 API Integration](#-api-integration)
- [⚠️ Authentication & Error Handling](#️-authentication--error-handling)
- [📊 Usage Limits & Best Practices](#-usage-limits--best-practices)
- [🧪 Assessment Guide](#-assessment-guide)
- [📝 Tasks Breakdown](#-tasks-breakdown)
- [🖼️ UI Preview](#%EF%B8%8F-ui-preview)
- [👨🏽‍💻 Author](#-author)

---

## 🎯 Project Description

CineSeek is a **movie discovery platform** where users can:

- Browse popular and trending movies
- Filter by **year** or **genre**
- View detailed movie information
- Enjoy a clean, responsive UI
- Learn how to work with RESTful APIs in a **real project** context.

---

## 🧠 Learning Objectives

- 📡 Understand API documentation and integration  
- ✍🏽 Implement TypeScript interfaces for API responses  
- 🧩 Create reusable React components  
- 📱 Build responsive layouts with Tailwind CSS  
- 🧭 Manage application state for filtering and pagination  
- 🛡️ Handle errors and loading states gracefully  
- 🔐 Secure API keys with environment variables  
- ⚡ Set up Next.js API routes for server-side data fetching.

---

## 🧰 Tech Stack & Requirements

### **Frontend Stack**
- [Next.js 14](https://nextjs.org/) (Pages Router)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)
- [MoviesDatabase API](https://moviesdatabase.io/) *(Public API)*

### **Development Tools**
- Node.js ≥ 16
- npm or yarn
- Git for version control
- `.env.local` for API key management

---

## 📁 File Structure

```plaintext
alx-movie-app/
├── components/
│   ├── commons/
│   │   ├── Button.tsx
│   │   ├── Loading.tsx
│   │   └── MovieCard.tsx
│   └── layouts/
│       ├── Footer.tsx
│       ├── Header.tsx
│       └── Layout.tsx
├── interfaces/
│   └── index.ts
├── pages/
│   ├── api/
│   │   └── fetch-movies.ts
│   ├── movies/
│   │   └── index.tsx
│   ├── _app.tsx
│   └── index.tsx
├── public/
├── styles/
│   └── globals.css
├── .env.local
├── .eslintrc.json
├── .gitignore
├── next.config.js
├── package.json
└── tsconfig.json
```

## 🧑🏽‍💻 Author

Dereje Masresha
📧 derejemasresha27@gmail.com

🌍 Ethiopia
💻 Full-Stack Developer | AWS & Next.js Enthusiast