# NoteHub — Authenticated Notes App

NoteHub is web application built with Next.js that allows users to register, log in, and manage personal notes.

🚀 Live Demo:
https://09-auth-one-sigma.vercel.app/

---

## Overview

The application provides:

- User registration and authentication
- Creating and viewing personal notes
- Protected routes for authenticated users
- Deployment on Vercel

---

## Technologies Used

- Next.js
- React
- TypeScript
- API Routes
- Vercel

---

## Project Structure

09-auth/
├── app/ # Next.js App Router pages and layouts  
│ ├── auth/ # Authentication pages (login / register)  
│ ├── notes/ # Notes pages (protected routes)  
│ └── layout.tsx # Root layout  
├── components/ # Reusable UI components  
├── lib/ # Utility functions and helpers  
├── middleware.ts # Route protection and auth middleware  
├── next.config.ts # Next.js configuration  
├── package.json  
└── README.md

---

## Features

- Authentication (Sign up / Sign in)
- Notes management
- Protected pages
- Responsive layout

---

## Running Locally

```
git clone https://github.com/Yurii-Voronich/NoteHub-App.git
cd NoteHub-App
npm install
npm run dev
```

Open http://localhost:3000

---

## Deployment

The project is deployed on Vercel.

Live URL:
https://09-auth-one-sigma.vercel.app/

---

## Environment Variables

Create .env.local file:

NEXT_PUBLIC_API_URL=...

---
