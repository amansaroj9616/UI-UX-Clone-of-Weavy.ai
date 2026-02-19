# 🚀 Weaave – Visual AI Workflow Builder (UI/UX Clone)

![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)
![React Flow](https://img.shields.io/badge/React_Flow-12-purple)
![Trigger.dev](https://img.shields.io/badge/Trigger.dev-Enabled-green)

![Preview](https://github.com/user-attachments/assets/0b02ef9d-c5d8-430d-a598-fc1e88cc3a9b)

A pixel-perfect UI/UX clone of [Weaave.ai](https://weaave.ai) — a modern visual workflow builder for creating LLM-powered automations.  
This project focuses on frontend architecture, visual workflows, and scalable background execution inspired by real-world AI automation platforms.

🎥 **Demo Video:**  
👉 [Watch Demo](https://drive.google.com/file/d/1nvQmwF1iAUaH0JjeI3jRUtwsZ-R7XV3T/view?usp=sharing)

---

## 📌 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Project Structure](#project-structure)
- [Documentation](#documentation)
- [License](#license)
- [Connect](#connect)

---


Open http://localhost:3000 to view the app.



## 📖 Overview

Weaave Clone is a frontend-focused project that replicates the visual workflow automation experience of Weaave.ai.  
Users can visually connect AI nodes, upload media, and execute workflows through a clean and scalable UI.

---

## ✨ Features

- 🧩 Visual workflow builder with drag & drop canvas  
- 🔗 6 node types: Text, Image Upload, Video Upload, LLM, Crop Image, Extract Frame  
- 🤖 AI-powered execution using Google Gemini API  
- ⚙️ Background jobs with Trigger.dev  
- 🧠 Workflow execution history  
- 🟢 Real-time node status indicators  
- 🔀 Parallel execution of independent branches  
- 🎞 Media processing using FFmpeg  
- ⏱ Smart timestamps (seconds or percentage-based frame extraction)  
- 🛡 Robust error handling and failure propagation  
- ☁️ Secure file uploads via Transloadit  
- 🔐 Authentication with Clerk  
- 🗄 Persistent data storage using PostgreSQL + Prisma  

---

## 🛠 Tech Stack

| Category | Technology |
|---------|------------|
| Framework | Next.js 16 (App Router) |
| Language | TypeScript |
| UI | React 19, React Flow |
| Styling | Tailwind CSS |
| State | Zustand |
| Database | PostgreSQL + Prisma |
| Auth | Clerk |
| AI | Google Gemini API |
| Background Jobs | Trigger.dev |
| Validation | Zod |

---


| Variable                            | Description                  | Source           |
| ----------------------------------- | ---------------------------- | ---------------- |
| DATABASE_URL                        | PostgreSQL connection string | Neon / Supabase  |
| NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY   | Clerk public key             | Clerk            |
| CLERK_SECRET_KEY                    | Clerk secret key             | Clerk            |
| GEMINI_API_KEY                      | Google Gemini API key        | Google AI Studio |
| TRIGGER_SECRET_KEY                  | Trigger.dev secret key       | Trigger.dev      |
| NEXT_PUBLIC_TRANSLOADIT_AUTH_KEY    | Transloadit Auth Key         | Transloadit      |
| NEXT_PUBLIC_TRANSLOADIT_TEMPLATE_ID | Transloadit Template ID      | Transloadit      |


## 🚀 Getting Started

### ✅ Prerequisites

- Node.js 18+  
- PostgreSQL (Neon)  
- Clerk account  
- Google Gemini API key  
- Trigger.dev account  

---

### ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/amansaroj9616/UI-UX-Clone-of-Weavy.ai
cd weaave-clone

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env

# Push database schema
npx prisma db push

# Run development server
npm run dev

# Run Trigger.dev (in a separate terminal)
npm run trigger:dev
```


🔐 Environment Variables
| Variable                            | Description                  | Source           |
| ----------------------------------- | ---------------------------- | ---------------- |
| DATABASE_URL                        | PostgreSQL connection string | Neon / Supabase  |
| NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY   | Clerk public key             | Clerk            |
| CLERK_SECRET_KEY                    | Clerk secret key             | Clerk            |
| GEMINI_API_KEY                      | Google Gemini API key        | Google AI Studio |
| TRIGGER_SECRET_KEY                  | Trigger.dev secret key       | Trigger.dev      |
| NEXT_PUBLIC_TRANSLOADIT_AUTH_KEY    | Transloadit Auth Key         | Transloadit      |
| NEXT_PUBLIC_TRANSLOADIT_TEMPLATE_ID | Transloadit Template ID      | Transloadit      |


```
```
🗂 Project Structure
src/
├── app/                 # Next.js App Router pages
├── components/          # Reusable UI components
│   └── workflow/        # Workflow canvas & nodes
├── lib/                 # Utilities & helpers
├── store/               # Zustand state management
├── trigger/             # Trigger.dev background tasks
└── prisma/              # Database schema
```
```
📚 Documentation
| Document | Description                                         |
| -------- | --------------------------------------------------- |
| HLD      | High-Level Design (System architecture & data flow) |
| LLD      | Low-Level Design (Schema, APIs, execution flow)     |


```
```
📄 License

This project is licensed under the MIT License.
See the LICENSE file for details.
```
```

🤝 Connect

🔗 Portfolio / Contact:
https://github.com/amansaroj9616/UI-UX-Clone-of-Weavy.ai
