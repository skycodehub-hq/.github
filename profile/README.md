<div align="center">

# 🚀 SkyCodeHub

### Secure Coding Assessments. Real-Time Judging. Zero Compromise.

[![Website](https://img.shields.io/badge/Website-skycodehub.com-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://skycodehub.com)
[![Status](https://img.shields.io/badge/Status-Active%20Development-success?style=for-the-badge)]()
[![Org](https://img.shields.io/badge/Private%20Org-Restricted%20Access-orange?style=for-the-badge&logo=github)]()

</div>

---

## What is SkyCodeHub?

SkyCodeHub is a **coding assessment & exam platform built for colleges** — letting institutions run secure, proctored coding tests with real-time code execution, MCQs, and anti-cheat enforcement via a locked-down exam browser.

No more Google Forms for coding tests. No more screen-sharing chaos for proctoring. Just one platform: create → assign → proctor → grade → analyze.

---

## 🧩 The Stack

<div align="center">

| Layer | Tech |
|---|---|
| **Dashboard** | ![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-6-646CFF?logo=vite&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-4-06B6D4?logo=tailwindcss&logoColor=white) |
| **Backend** | ![Node](https://img.shields.io/badge/Node.js-20-339933?logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express-5-000000?logo=express&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-7-2D3748?logo=prisma&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-4169E1?logo=postgresql&logoColor=white) |
| **Code Judger** | ![Judge0](https://img.shields.io/badge/Judge0-Sandboxed%20Execution-1F2937) ![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker&logoColor=white) |
| **Proctoring** | ![Electron](https://img.shields.io/badge/Electron-SEB-47848F?logo=electron&logoColor=white) |
| **Infra** | ![AWS](https://img.shields.io/badge/AWS-EC2-FF9900?logo=amazonaws&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-Reverse%20Proxy-009639?logo=nginx&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-Queues-DC382D?logo=redis&logoColor=white) |

</div>

---

## 🏗️ How It Fits Together

```
                          ┌──────────────────────┐
                          │   skycodehub.com      │   ← marketing site (Vercel)
                          └──────────────────────┘

                          ┌──────────────────────┐
              ┌──────────▶│  app.skycodehub.com  │◀──────────┐
              │           └──────────────────────┘           │
              │                       │                       │
       ┌──────┴──────┐        ┌───────┴───────┐       ┌───────┴────────┐
       │  Dashboard  │        │    Backend    │       │  SEB (Desktop)  │
       │   (React)   │◀──────▶│ (Node/Express)│◀─────▶│   (Electron)    │
       └─────────────┘        └───────┬───────┘       └────────────────┘
                                       │
                       ┌───────────────┼───────────────┐
                       ▼               ▼               ▼
                 ┌──────────┐   ┌──────────┐    ┌─────────────┐
                 │ Postgres │   │  Judger  │    │    Redis    │
                 │ (Neon)   │   │ (Judge0) │    │  (BullMQ)   │
                 └──────────┘   └──────────┘    └─────────────┘
```

---

## 📦 Repositories

| Repo | Purpose |
|---|---|
| 🖥️ **Dashboard (frontend)** | Admin/teacher/student web app — test creation, analytics, live monitoring |
| ⚙️ **Backend API** | Auth, test orchestration, submissions, college/org management |
| 🧪 **Code Judger** | Sandboxed multi-language code execution & grading engine |
| 🔒 **SEB (Safe Exam Browser)** | Locked-down Electron app for proctored exam sessions |

> All repositories are private. Access is granted per-team-member.

---

## ✨ What Makes It Different

- 🔐 **Real proctoring** — not just a webcam feed. Tab-switch detection, focus-loss tracking, app-lock via SEB.
- ⚡ **Live code judging** — submissions run against real test cases in sandboxed containers, not string-matching.
- 🏫 **Multi-tenant by design** — every college gets isolated data, roles, and resource limits out of the box.
- 📊 **Built-in analytics** — student/teacher/department performance, not bolted on as an afterthought.

---

<div align="center">

**Building the exam infrastructure colleges actually deserve.**

[skycodehub.com](https://skycodehub.com) · app.skycodehub.com

</div>
