<div align="center">

# Juan López Cantavella

**Full-stack & multiplatform developer** · **Java** · TypeScript · React / Next.js · Node.js · SQL

Castellón, Spain · Spanish (native) · Valencian (C1) · English (C1)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Juan%20López%20Cantavella-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juan-lopez-cantavella/)
[![Email](https://img.shields.io/badge/Email-juan.lopezcantavella%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:juan.lopezcantavella@gmail.com)

</div>

---

## About

I build web and mobile products end to end: data model, API, interface and deployment. My strongest language is **Java** (object-oriented programming, SQL databases, Android); on the web I work with TypeScript, React, Next.js and Node.js. I care about typed code, tested business logic and interfaces that non-technical users understand on first use.

- Studying **Multiplatform Application Development (DAM)** at Davante MEDAC Castellón, graduating in 2027.
- Two years of **Mechanical Engineering** before switching to software: that is where I learned to work with models, constraints and tolerances before writing a single line.
- Currently building my own SaaS product for appointment-based businesses.

---

## Featured projects

### Core Reservas — multi-tenant booking SaaS
White-label platform that lets small appointment-based businesses (salons, clinics, studios) take online bookings and manage their schedule, staff and clients from one dashboard.

- **Stack:** TypeScript (strict) · Next.js App Router · Node.js + Express · PostgreSQL + Prisma · Zod · JWT auth with role-based access · Resend (transactional email) · Docker
- Multi-tenant architecture: one codebase, per-business branding injected from configuration, data isolated by tenant.
- Clean Architecture split into controllers, services and repositories; shared types package across API and web (npm workspaces).
- Public booking portal per business, staff calendar, client records, absences and closures, email notifications and WhatsApp notices (Meta Cloud API) with opt-in/opt-out.
- 90+ test files, CI verification script (typecheck, lint, tests, build) and an internal security review before deployment.
- Status: MVP complete. Public demo and pilot with real businesses in progress.

### GoalStreet — football trading game (mobile)
Free-to-play app where users sign "cards" of real players from Europe's top 5 leagues; each card's value rises or falls with the player's real performance.

- **Stack:** React Native + Expo · TypeScript · Expo Router · Zustand · Three.js / React Three Fiber (3D cards) · Skia · Supabase (Postgres)
- Pricing engine written in pure TypeScript, decoupled from React: bonding-curve market against the house and post-match revaluation with capped daily moves.
- Data pipeline that turns public sources (openfootball, Fantasy Premier League) into normalised CSV, SQL seed and an in-app catalogue of 2,600+ players.
- Four working zones: market, squad, match news and private leagues. 105 tests cover the engine, data and game logic.
- Product rule: the interface speaks like a football fan, not like an investor — no financial jargon in the UI.

### Yayos — care app for elderly people and caregivers *(DAM team project)*
Two connected apps: a caregiver dashboard (location radar, medication schedule, contacts and alerts) and a high-accessibility app for the elderly user (SOS button, spoken pill reminders, one-tap calls).

- **Stack:** React + Vite · Tailwind CSS + Radix (shadcn/ui) · Framer Motion · Zustand · Firebase (Firestore, Auth, FCM) · Google Maps · Piper TTS in the browser
- My role: lead of the caregiver module. Real-time sync between both apps, shared data model and scheduling logic, tests with Vitest.

> The repositories above are private while the products are in development. I can share a code walkthrough or a live demo on request.

**Other work:** [Programacion_Java](https://github.com/jlopez051/Programacion_Java) (Java coursework: OOP, inheritance, recursion, arrays, file handling) · [PROYECTO_MARKETING-SHAKE-GO-](https://github.com/jlopez051/PROYECTO_MARKETING-SHAKE-GO-) (multi-page website for a smoothie brand concept, with a JavaScript shopping cart).

---

## Tech stack

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frontend & mobile**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white)

**Backend & data**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Tooling**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

---

## How I work

- **Types and tests first on business logic.** Pricing engines, booking rules and scheduling live in plain TypeScript modules with their own tests, separate from the UI.
- **Documented decisions.** Each milestone gets a written spec and an architecture note, so the reasoning behind the code is traceable.
- **Security and privacy by default.** Role-based access, input validation with Zod, no secrets or personal data in logs.

---

## Experience

**Camp Counselor** — Banner Day Camp, Chicago, USA · Summer 2026
Responsible for groups of children in an English-speaking environment: daily planning, coordination with a multicultural team and communication with families.

---

<div align="center">

Open to internships (FCT) and junior developer roles · [Get in touch](mailto:juan.lopezcantavella@gmail.com)

</div>
