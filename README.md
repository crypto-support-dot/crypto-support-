# 🚀 Crypto Support Website

A simple support ticket system built with **Next.js + TailwindCSS + Prisma (SQLite)**.  
Includes user ticket submission and a basic admin dashboard.

## Features
- 🌐 Styled homepage
- 🎫 Submit support tickets
- 🔑 Admin dashboard (password protected)
- 🐳 Docker + docker-compose

## Setup

```bash
npm install
npx prisma migrate dev --name init
npm run dev
```

## Docker

```bash
docker-compose up --build
```

Admin password is set in `docker-compose.yml` (`NEXT_PUBLIC_ADMIN_PASS`).
