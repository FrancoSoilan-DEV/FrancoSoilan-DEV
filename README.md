<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&reversal=true" />
</div>

<h1 align="center">
  Hi, I'm Franco Jeremias Soilan Lopez 
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35" />
</h1>

<h3 align="center">
  Backend Developer | Django • FastAPI • NestJS • Express.js • PostgreSQL • Docker
</h3>

<p align="center">
  <strong>Backend developer specialized in building production-like systems with Django, FastAPI, NestJS, Express.js, PostgreSQL, Docker, and real-world business workflows.</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Backend+Development+Enthusiast;Django+%7C+FastAPI+%7C+NestJS+%7C+Express.js+%7C+PostgreSQL;Production-like+Backend+Systems;Role-Based+REST+APIs;Real-time+Django+Applications;NestJS+%2B+Prisma+%2B+AI+Agents;Always+Learning,+Always+Improving&center=true&width=950&height=40">
</p>

---

## ⚡ Quick Proof

- Built **7+ backend systems** with real business workflows.
- Developed **real-time applications** using Django Channels, Redis, WebSockets, and ASGI.
- Built **role-based REST APIs** with FastAPI, JWT authentication, refresh token rotation, and PostgreSQL.
- Built a **fullstack logistics system** with Express.js, TypeScript, Prisma, EJS, and Docker from scratch.
- Built a **NestJS maritime fleet management platform** with role-based portals, Prisma, and an AI agent using tool calling.
- Created **Dockerized environments** for reproducible local testing.
- Worked with **pricing logic, stock management, payments, reports, dashboards, and protected workflows**.

---

## 🚀 What I Build

Built multiple production-like systems including:

- **Real-time restaurant platform** with WebSockets, Stripe payments, table workflows, and role-based dashboards.
- **Multi-branch inventory management system** with real-time stock updates, inter-branch transfers, and JWT auth.
- **Partner quotation and order management portal** with pricing rules, stock tracking, approvals, and email notifications.
- **Fullstack logistics and transport management system** with Express.js, TypeScript, Prisma, automatic cost calculation, and EJS frontend.
- **Maritime fleet management platform** built with NestJS, Prisma, PostgreSQL, and a Groq-powered AI agent with tool calling.
- **Role-based REST APIs** with JWT authentication, refresh token rotation, SQLAlchemy, Alembic, and Docker.
- **Internal business management systems** with inventory, backups, technical service, reports, and reproducible setup.

---

## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="25px"> About Me

<img 
  src="https://raw.githubusercontent.com/MicaelliMedeiros/micaellimedeiros/master/image/computer-illustration.png" 
  alt="Computer illustration" 
  width="370px" 
  align="right"
/>

I'm **Franco Jeremias Soilan Lopez**, a Computer Science student and backend-focused web developer.

I build **practical, database-driven systems** using **Python, Django, FastAPI, Flask, Node.js, TypeScript, NestJS, Express.js, PostgreSQL, Prisma, Redis, Docker, Docker Compose, REST APIs, Git, GitHub, and GitLab**.

My main interest is creating backend solutions that are reliable, maintainable, and useful in real business workflows. I enjoy backend development because it involves **designing systems, structuring data, organizing business logic, integrating services, and solving real operational problems**.

Currently, I am studying **Bachelor's Degree in Computer Science with an emphasis in Systems Analysis** at the **National University of Asunción**, Faculty of Polytechnic.

<br clear="right"/>

---

## 🎯 Current Goal

I am actively looking for **remote opportunities as a Backend Developer**, especially with:

**Python · Django · FastAPI · Node.js · TypeScript · NestJS · Express.js · PostgreSQL · Redis · Docker · Docker Compose · REST APIs**

Open to remote opportunities and ready to contribute to production backend systems.

---

## 🧪 How to Test My Projects

All main projects are designed to be **reproducible locally using Docker**.

```bash
docker compose up --build
```

Each repository includes, when applicable:

- Step-by-step setup instructions.
- `.env.example` or documented environment configuration.
- Docker-based local development.
- Initial data seeding or setup commands.
- Ready-to-test local workflows without needing a deployed demo.

> 📺 Want to see the projects in action before running them locally? Check out my **[YouTube channel](https://www.youtube.com/@FrancoSoilanDev)** for beta previews and walkthroughs.

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">

### <img src="https://skillicons.dev/icons?i=nestjs" width="24"/> <a href="https://github.com/FrancoSoilan-DEV/ships-system"><u>Ships System</u></a>

**Tech:** NestJS · TypeScript · Prisma · PostgreSQL · Groq AI · Docker  
**Run:** `docker compose up --build` → `npx prisma db push` → `npx prisma db seed`  
**Type:** Maritime fleet management platform  
**Preview:** [▶ Watch on YouTube](https://www.youtube.com/watch?v=PE-0fHkedaw)

<details>
  <summary><strong>View details</strong></summary>

<br>

**Repository**

```bash
git clone https://github.com/FrancoSoilan-DEV/ships-system.git
cd ships-system
docker compose up --build -d
docker compose exec app npx prisma db push
docker compose exec app npx prisma db seed
```

Open at `http://localhost:3000`

Default credentials:

| Email | Password | Role |
|---|---|---|
| superadmin@ships.com | super123 | Superadmin |
| admin@ships.com | admin123 | Admin |
| captain@ships.com | captain123 | Captain |
| client@ships.com | client123 | Client |

**Highlights**

- Built a NestJS project from scratch, focused on understanding *why* the framework structures things the way it does (modules, providers, guards, strategies), coming from Django/FastAPI/Express.js.
- Implemented **JWT authentication** with access + refresh token rotation and route-level `@Roles()` guards across 4 role-based portals.
- Integrated an **AI agent (Groq / Llama 3.3 70B)** with native tool calling — quotes voyages, lists ships, self-registers clients, and escalates to a human.
- Built an **automatic tariff-based pricing engine** shared between the AI agent and the real booking endpoint.
- Modeled a relational schema with **13 Prisma models** covering users, ships, crew, voyages, cargo, tariffs, maintenance, and an AI chat/escalation system.
- Implemented a **bilingual (ES/EN) i18n system** across landing, auth, and all 4 portals.

</details>

</td>
    <td width="50%" valign="top">

### <img src="https://skillicons.dev/icons?i=django" width="24"/> <a href="https://github.com/FrancoSoilan-DEV/Django-Burgers-System"><u>Django Burgers System</u></a>

**Tech:** Django · Channels · Redis · PostgreSQL · Stripe · Docker · Nginx  
**Run:** `docker compose up --build`  
**Type:** Real-time restaurant management platform  
**Preview:** [▶ Watch on YouTube](https://www.youtube.com/watch?v=XlfOE74Rb2g&t=4s)

<details>
  <summary><strong>View details</strong></summary>

<br>

**Repository**

```bash
git clone https://github.com/FrancoSoilan-DEV/Django-Burgers-System.git
cd Django-Burgers-System
docker compose up --build
```

**Highlights**

- Built real-time order workflows using Django Channels, Redis, WebSockets, and ASGI.
- Implemented role-based dashboards for clients, waiters, kitchen staff, and managers.
- Integrated Stripe payments, cash payment flow, and backend payment records.
- Added table sessions, waiter calls, kitchen order tracking, and live client updates.
- Used Daphne, Nginx, PostgreSQL, Redis, Cloudinary, Google OAuth, and Docker Compose.

</details>

</td>
  </tr>
  <tr>
    <td width="50%" valign="top">

### <img src="https://skillicons.dev/icons?i=express" width="24"/> <a href="https://github.com/FrancoSoilan-DEV/vi-trucking"><u>VI-Trucking</u></a>

**Tech:** Express.js · TypeScript · Prisma · PostgreSQL · EJS · JWT · Docker  
**Run:** `docker compose up --build` → `npx prisma migrate dev --name init` → `npm run seed`  
**Type:** Fullstack logistics and transport management system  
**Preview:** [▶ Watch on YouTube](https://www.youtube.com/watch?v=hM_EGe7JYCY)

<details>
  <summary><strong>View details</strong></summary>

<br>

**Repository**

```bash
git clone https://github.com/FrancoSoilan-DEV/vi-trucking.git
cd vi-trucking
docker compose up --build
npx prisma migrate dev --name init
npm run seed
```

Open at `http://localhost:3000`

Default credentials:

| Email | Password | Role |
|---|---|---|
| admin@vitrucking.com | admin123 | Superadmin |
| carlos@vitrucking.com | admin123 | Admin |
| roberto@vitrucking.com | driver123 | Driver |
| ana@exportaciones.com | client123 | Client |

**Highlights**

- Built a fullstack system from scratch using **Express.js and TypeScript** — first Node.js project after experience with Django and FastAPI.
- Implemented **JWT cookie-based authentication** with four roles: Superadmin, Admin, Driver, and Client.
- Automatic **trip cost calculation** via configurable tariff matching by country, distance, and cargo type (`finalCost = baseAmount × multiplier + fixedAmount`).
- Multi-branch architecture — drivers and vehicles belong to specific branches.
- Vehicle fleet tracking with km, total trips, maintenance dates, and license expiry.
- Client company tracking with total orders, trucks sent, and revenue generated.
- **Dual layer architecture** — REST API (JSON) and server-rendered EJS frontend sharing the same services.
- Prisma ORM with PostgreSQL, layered architecture (config → database → utils → middlewares → services → controllers → routers).
- Sidebar dashboard layout built with plain CSS and CSS variables, no frameworks.

</details>

</td>
    <td width="50%" valign="top">

### <img src="https://skillicons.dev/icons?i=fastapi" width="24"/> <img src="https://skillicons.dev/icons?i=vue" width="24"/> <a href="https://github.com/FrancoSoilan-DEV/stockflow"><u>Stockflow</u></a>

**Tech:** FastAPI · Vue 3 · PostgreSQL · WebSockets · JWT · Docker  
**Run:** `make up-b` → `make migrate` → `make seed`  
**Type:** Multi-branch inventory management system  
**Preview:** [▶ Watch on YouTube](https://www.youtube.com/watch?v=IgxghIRCrqA)

<details>
  <summary><strong>View details</strong></summary>

<br>

**Repository**

```bash
git clone https://github.com/FrancoSoilan-DEV/stockflow.git
cd stockflow
make up-b
make migrate
make seed
```

Open at `http://localhost:5173`

Default credentials:

| Email | Password | Role |
|---|---|---|
| admin@stockflow.com | admin123 | Admin |
| juan@stockflow.com | juan123 | Staff |

**Highlights**

- Built a full-stack system with FastAPI backend and Vue 3 frontend, fully Dockerized.
- Implemented JWT authentication with role-based access control (admin / staff).
- Real-time stock updates, private chat, and user presence via native WebSockets.
- Inter-branch stock transfer request system with admin approval workflow.
- Point-of-sale sales recording with automatic stock deduction and price snapshots.
- SQLAlchemy 2.0 async, Alembic migrations, Pinia state management, Tailwind CSS v4.

</details>

</td>
  </tr>
</table>

---

<details>
<summary><strong>📂 More Projects</strong></summary>

<br>

<table>
  <tr>
    <td width="50%" valign="top">

### <img src="https://skillicons.dev/icons?i=django" width="24"/> <a href="https://github.com/FrancoSoilan-DEV/Django-s7-partners"><u>Django S7 Partners</u></a>

**Tech:** Django · DRF · PostgreSQL · Docker · Nginx · Cloudinary · i18n  
**Run:** `docker compose -f docker-compose.dev.yml up --build`  
**Type:** Partner self-quotation and order portal  
**Preview:** [▶ Watch on YouTube](https://www.youtube.com/watch?v=uTcYgSbRcPY&t=56s)

<details>
  <summary><strong>View details</strong></summary>

<br>

**Repository**

```bash
git clone https://github.com/FrancoSoilan-DEV/Django-s7-partners.git
cd Django-s7-partners
docker compose -f docker-compose.dev.yml up --build
```

**Highlights**

- Built partner-facing workflows for catalog browsing, self-quotation, order submission, and order history.
- Implemented pricing logic with client types, quantity multiplicators, special user multiplicators, regions, and currencies.
- Created staff-side order approval/rejection flow with stock updates.
- Added email notifications, Cloudinary media handling, and Spanish/English support.
- Structured the project with separated partner, admin, and API areas.

</details>

</td>
    <td width="50%" valign="top">

### <img src="https://skillicons.dev/icons?i=django" width="24"/> <a href="https://github.com/FrancoSoilan-DEV/Django-swap"><u>Django SWAP</u></a>

**Tech:** Django · PostgreSQL · Redis · Docker · Gunicorn · WhiteNoise  
**Run:** `docker compose up --build` + init script  
**Type:** Internal business management system  
**Preview:** [▶ Watch on YouTube](https://www.youtube.com/watch?v=SDcmgBUWU2s)

<details>
  <summary><strong>View details</strong></summary>

<br>

**Repository**

```bash
git clone https://github.com/FrancoSoilan-DEV/Django-swap.git
cd Django-swap
docker compose up --build
docker compose exec web sh scripts/docker-init.sh
```

**Highlights**

- Built role-based modules for HR, IT, gatehouse, technicians, and technical service.
- Implemented inventory, equipment, maintenance, backup, entry/exit, and technical work workflows.
- Added repeatable project initialization with migrations, seed data, default users, groups, and static collection.
- Created Excel and PDF export workflows.
- Used Docker, PostgreSQL, Redis, Gunicorn, and WhiteNoise for a reproducible setup.

</details>

</td>
  </tr>
  <tr>
    <td width="50%" valign="top">

### <img src="https://skillicons.dev/icons?i=fastapi" width="24"/> <a href="https://github.com/FrancoSoilan-DEV/FastAPI-vet-software"><u>FastAPI Vet Software</u></a>

**Tech:** FastAPI · PostgreSQL · SQLAlchemy · Alembic · JWT · Docker · Nginx  
**Run:** `docker compose -f docker/docker-compose.yml up --build`  
**Type:** Role-based veterinary clinic REST API

<details>
  <summary><strong>View details</strong></summary>

<br>

**Repository**

```bash
git clone https://github.com/FrancoSoilan-DEV/FastAPI-vet-software.git
cd FastAPI-vet-software
docker compose -f docker/docker-compose.yml up --build
```

**Highlights**

- Built a structured FastAPI backend with routers, services, schemas, models, and database layers.
- Implemented secure authentication with JWT, refresh token rotation, Argon2 hashing, and token versioning.
- Added role-based workflows for managers, receptionists, and veterinarians.
- Used SQLAlchemy 2.0 and Alembic for database modeling and migrations.
- Included Swagger docs, PostgreSQL health checks, Nginx reverse proxy, and Dockerized setup.

</details>

</td>
    <td width="50%" valign="top">

### <img src="https://skillicons.dev/icons?i=flask" width="24"/> <a href="https://github.com/FrancoSoilan-DEV/Flask-Lightning"><u>Flask Lightning</u></a>

**Tech:** Flask · Weatherbit API · Docker · OpenStreetMap · JavaScript · CSV  
**Run:** `docker compose up --build`  
**Type:** Lightning strike data tracker

<details>
  <summary><strong>View details</strong></summary>

<br>

**Repository**

```bash
git clone https://github.com/FrancoSoilan-DEV/Flask-Lightning.git
cd Flask-Lightning
docker compose up --build
```

**Highlights**

- Built a Flask proxy between the browser and the Weatherbit API.
- Kept API key handling server-side.
- Added real-time and historical lightning search by coordinates, radius, and date range.
- Integrated OpenStreetMap as a visual reference.
- Added summary statistics, progress feedback, and CSV export.

</details>

</td>
  </tr>
</table>

</details>

---

## 💼 Experience Highlights

I build backend systems around **data modeling, business rules, authentication, APIs, reporting, and operational workflows**.

<table>
  <tr>
    <td width="50%" valign="top">

### Backend Systems

- Django systems with role-based modules, dashboards, reports, exports, and protected workflows.
- NestJS systems with modular architecture, guards, strategies, and Prisma-backed relational models.
- Express.js + TypeScript fullstack systems with layered architecture, EJS frontend, and REST API.
- Relational models for inventories, orders, users, services, stock, payments, and operational records.
- Backend logic organized across models, views, services, APIs, consumers, and management commands.

</td>
    <td width="50%" valign="top">

### APIs & Real-time

- FastAPI backends with routers, schemas, services, SQLAlchemy, Alembic, JWT auth, and role-based access.
- NestJS REST APIs with Passport strategies, `@UseGuards()`, and `@Roles()` decorators for role-based access.
- Real-time Django workflows using Channels, Redis, WebSockets, ASGI, and role-specific dashboards.
- Flask tools for external API proxying, data filtering, visualization, and CSV export.
- Express.js dual-layer backends serving both REST API and server-rendered EJS pages.

</td>
  </tr>
  <tr>
    <td width="50%" valign="top">

### Business Logic

- Quotation, pricing, stock, payment, backup, service, inventory, and access-control workflows.
- Automatic tariff matching and cost calculation based on configurable rules.
- Discounts, multiplicators, currencies, order states, approval flows, and historical records.
- Systems built around real operational processes instead of isolated demo features.

</td>
    <td width="50%" valign="top">

### AI Integration

- AI agents with native tool calling (Groq SDK) — quoting, data lookups, account creation, and human escalation.
- Separate system prompts and tool sets for public vs. authenticated AI endpoints to avoid context bleed.
- AI-driven workflows wired directly into the same business logic used by the regular REST endpoints.

</td>
  </tr>
</table>

---

## <img src="https://media.giphy.com/media/juua9i2c2fA0AIp2iq/giphy.gif" width="27px"> Tech Stack

<table>
  <tr>
    <td width="50%" valign="top">

### Backend Development

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,django,fastapi,flask,nodejs,ts,nestjs,express" />
</p>

- Python · Django · Django REST Framework · Django Channels
- FastAPI · Flask
- Node.js · TypeScript · **NestJS** · Express.js
- REST API development · Backend architecture
- Business logic implementation
- Authentication and authorization
- Prisma ORM · SQLAlchemy · Alembic
- API testing with Postman

</td>
    <td width="50%" valign="top">

### Databases & Cache

<p align="left">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,redis" />
</p>

- PostgreSQL · MySQL · Redis
- Relational database design · Data modeling
- Query optimization basics
- Redis channel layer for WebSockets
- Cache usage basics

</td>
  </tr>
  <tr>
    <td width="50%" valign="top">

### DevOps & Tools

<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,git,github,gitlab,postman,bash,linux,nginx" />
</p>

- Docker · Docker Compose
- Git · GitHub · GitLab
- Postman · Bash basics · Linux basics
- Gunicorn · Daphne · Nginx
- Environment configuration with `.env`

</td>
    <td width="50%" valign="top">

### Framework Tools

<p align="left">
  <img src="https://skillicons.dev/icons?i=fastapi,django,nestjs,flask,express,postgres,docker" />
</p>

- SQLAlchemy · Alembic · Prisma
- Pydantic schemas · JWT authentication
- Refresh token rotation · Argon2 · bcrypt
- Role-based access control
- NestJS modules, providers, guards, and Passport strategies
- Swagger / OpenAPI documentation
- WebSocket consumers
- EJS server-rendered templates
- External API integration · CSV export · Stripe

</td>
  </tr>
</table>

---

## 🧩 Engineering Practices

I focus on backend projects that are **structured, reproducible, secure, and easy to review locally**.

<table>
  <tr>
    <td width="50%" valign="top">

### Architecture

- Modular Django apps, organized around models, views, services, consumers, and management commands.
- Service-oriented FastAPI and Flask structures (routers/proxies → services → schemas → SQLAlchemy/Alembic).
- Modular NestJS architecture (modules → controllers → services → guards/strategies → Prisma).
- Layered Express.js architecture (config → database → utils → middlewares → services → controllers → routers).
- Vue 3 frontends structured with Composition API, Pinia stores, and Axios API modules, consuming FastAPI/NestJS backends.
- Clear separation of models, views, routers, schemas, services, consumers, and configuration across every stack.

</td>
    <td width="50%" valign="top">

### Reproducibility

- Docker and Docker Compose setup.
- `.env` based configuration.
- Setup scripts, initial data seeding, and documented local workflows.

</td>
  </tr>
  <tr>
    <td width="50%" valign="top">

### Security & Data

- PostgreSQL-backed application design.
- Authentication, permissions, roles, groups, and protected workflows.
- Secret isolation, server-side API proxying, and public repository safety.

</td>
    <td width="50%" valign="top">

### Deployment Mindset

- Gunicorn/Nginx, Uvicorn/Nginx, and Daphne/Nginx flows.
- WhiteNoise or shared Docker volumes for static files.
- API validation with Postman, Swagger/OpenAPI, and framework-level tooling.

</td>
  </tr>
</table>

---

## 🧠 Backend Mindset

I enjoy backend development because it involves designing systems, structuring data, integrating services, and solving real-world operational problems.

I focus on building software that is:

- Practical for users.
- Structured for developers.
- Reproducible for reviewers.
- Maintainable over time.

---

## 📚 Currently Learning

- Advanced Django and FastAPI development
- **NestJS** in depth — modules, providers, guards, custom decorators, and Passport-based strategies
- Node.js and TypeScript ecosystem (NestJS, Express.js, Prisma)
- Django Channels and real-time backend workflows
- API design and authentication best practices
- Docker-based development and deployment workflows
- Testing, documentation, and production-ready backend architecture

---

## 🛠️ What I Like to Build

- REST APIs and backend systems
- Real-time web applications
- Admin dashboards and partner portals
- Authentication and role-based workflows
- Inventory, stock, quotation, ordering, logistics, and management systems
- AI-powered agents with tool calling wired into real business logic
- External API integrations and data tools
- Dockerized web platforms with real-world business use cases

---

## 🌐 Connect With Me

<p align="left">
  <a href="mailto:francosoilanwork@gmail.com">
    <img src="https://img.shields.io/badge/Email-francosoilanwork@gmail.com-red?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://glittering-meringue-bce383.netlify.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20My%20Site-7c9ef8?style=for-the-badge&logo=netlify&logoColor=white" />
  </a>
  <a href="https://github.com/FrancoSoilan-DEV">
    <img src="https://img.shields.io/badge/GitHub-FrancoSoilan--DEV-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.youtube.com/@FrancoSoilanDev">
    <img src="https://img.shields.io/badge/YouTube-FrancoSoilanDev-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
  </a>
  <a href="https://www.instagram.com/franco_soilan/">
    <img src="https://img.shields.io/badge/Instagram-franco__soilan-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
  <a href="https://wa.me/595982686373">
    <img src="https://img.shields.io/badge/WhatsApp-%2B595%20982%20686%20373-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
  </a>
</p>

---

<div align="center">
  <h3>☕ Fueled by coffee, curiosity, and backend development 🐱</h3>
</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&section=footer" />
</div>
