<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&reversal=true" />
</div>

<h1 align="center">
  Hi, I'm Franco Jeremias Soilan Lopez 
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35" />
</h1>

<h3 align="center">
  Backend Developer | Django • FastAPI • PostgreSQL • Docker
</h3>

<p align="center">
  <strong>Backend developer specialized in building production-like systems with Django, FastAPI, PostgreSQL, Docker, and real-world business workflows.</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Backend+Development+Enthusiast;Django+%7C+FastAPI+%7C+PostgreSQL+%7C+Docker;Production-like+Backend+Systems;Role-Based+REST+APIs;Real-time+Django+Applications;Always+Learning,+Always+Improving&center=true&width=950&height=40">
</p>

---

## ⚡ Quick Proof

- Built **5+ backend systems** with real business workflows.
- Developed **real-time applications** using Django Channels, Redis, WebSockets, and ASGI.
- Built **role-based REST APIs** with FastAPI, JWT authentication, refresh token rotation, and PostgreSQL.
- Created **Dockerized environments** for reproducible local testing.
- Worked with **pricing logic, stock management, payments, reports, dashboards, and protected workflows**.

---

## 🚀 What I Build

Built multiple production-like systems including:

- **Real-time restaurant platform** with WebSockets, Stripe payments, table workflows, and role-based dashboards.
- **Partner quotation and order management portal** with pricing rules, stock tracking, approvals, and email notifications.
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

I build **practical, database-driven systems** using **Python, Django, FastAPI, Flask, PostgreSQL, Redis, Docker, Docker Compose, REST APIs, Git, GitHub, and GitLab**.

My main interest is creating backend solutions that are reliable, maintainable, and useful in real business workflows. I enjoy backend development because it involves **designing systems, structuring data, organizing business logic, integrating services, and solving real operational problems**.

Currently, I am studying **Bachelor's Degree in Computer Science with an emphasis in Systems Analysis** at the **National University of Asunción**, Faculty of Polytechnic.

<br clear="right"/>

---

## 🎯 Current Goal

I am actively looking for **remote opportunities as a Backend Developer**, especially with:

**Python · Django · FastAPI · PostgreSQL · Redis · Docker · Docker Compose · REST APIs**

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

---

## 🚀 Projects

A compact overview of my main backend projects.

<table>
  <tr>
    <td width="50%" valign="top">

### 🍔 <a href="https://github.com/FrancoSoilan-DEV/Django-Burgers-System"><u>Django Burgers System</u></a>

**Tech:** Django · Channels · Redis · PostgreSQL · Stripe · Docker · Nginx  
**Run:** `docker compose up --build`  
**Type:** Real-time restaurant management platform

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
<td width="50%" valign="top">

### 🤝 <a href="https://github.com/FrancoSoilan-DEV/Django-s7-partners"><u>Django S7 Partners</u></a>

**Tech:** Django · DRF · PostgreSQL · Docker · Nginx · Cloudinary · i18n  
**Run:** `docker compose -f docker-compose.dev.yml up --build`  
**Type:** Partner self-quotation and order portal

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
</tr>
<tr>
<td width="50%" valign="top">

### 🏢 <a href="https://github.com/FrancoSoilan-DEV/Django-swap"><u>Django SWAP</u></a>

**Tech:** Django · PostgreSQL · Redis · Docker · Gunicorn · WhiteNoise  
**Run:** `docker compose up --build` + init script  
**Type:** Internal business management system

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
<td width="50%" valign="top">

### 🐾 <a href="https://github.com/FrancoSoilan-DEV/FastAPI-vet-software"><u>FastAPI Vet Software</u></a>

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
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ <a href="https://github.com/FrancoSoilan-DEV/Flask-Lightning"><u>Flask Lightning</u></a>

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
<td width="50%" valign="top">

### 🧪 More Backend Projects

**Tech:** Django · FastAPI · Flask · PostgreSQL · Docker · APIs  
**Status:** Always building and improving  
**Focus:** Real-world backend workflows

<details>
  <summary><strong>View direction</strong></summary>

<br>

Project areas I continue exploring:

- Backend APIs
- Business management systems
- Real-time applications
- Inventory and stock workflows
- Role-based access control
- External API integrations
- Reporting and data export tools
- Dockerized development environments

</details>

</td>
</tr>
</table>

---

## 💼 Experience Highlights

I build backend systems around **data modeling, business rules, authentication, APIs, reporting, and operational workflows**.

<table>
  <tr>
    <td width="50%" valign="top">

### Backend Systems

- Django systems with role-based modules, dashboards, reports, exports, and protected workflows.
- Relational models for inventories, orders, users, services, stock, payments, and operational records.
- Backend logic organized across models, views, services, APIs, consumers, and management commands.

</td>
<td width="50%" valign="top">

### APIs & Real-time

- FastAPI backends with routers, schemas, services, SQLAlchemy, Alembic, JWT auth, and role-based access.
- Real-time Django workflows using Channels, Redis, WebSockets, ASGI, and role-specific dashboards.
- Flask tools for external API proxying, data filtering, visualization, and CSV export.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Business Logic

- Quotation, pricing, stock, payment, backup, service, inventory, and access-control workflows.
- Discounts, multiplicators, currencies, order states, approval flows, and historical records.
- Systems built around real operational processes instead of isolated demo features.

</td>
<td width="50%" valign="top">

### Reliability

- Validation, protected workflows, repeatable initialization, and environment-based configuration.
- Docker-based setups for local execution, testing, and technical review.
- Clean structure, reproducible setup, and practical documentation.

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
  <img src="https://skillicons.dev/icons?i=python,django,fastapi,flask" />
</p>

- Python
- Django
- Django REST Framework
- Django Channels
- FastAPI
- Flask
- REST API development
- Backend architecture
- Business logic implementation
- Authentication and authorization
- Django management commands
- API testing with Postman

</td>
<td width="50%" valign="top">

### Databases & Cache

<p align="left">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,redis" />
</p>

- PostgreSQL
- MySQL
- Redis
- Relational database design
- Data modeling
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

- Docker
- Docker Compose
- Git
- GitHub
- GitLab
- Postman
- Bash basics
- Linux basics
- Gunicorn
- Daphne
- Nginx
- Environment configuration with `.env`

</td>
<td width="50%" valign="top">

### Backend Framework Tools

<p align="left">
  <img src="https://skillicons.dev/icons?i=fastapi,django,flask,postgres,docker" />
</p>

- SQLAlchemy
- Alembic migrations
- Pydantic schemas
- JWT authentication
- Refresh token rotation
- Argon2 password hashing
- Role-based access control
- Swagger / OpenAPI documentation
- WebSocket consumers
- External API integration
- CSV export workflows
- Stripe payment workflows

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

- Modular Django apps.
- Service-oriented FastAPI structure.
- Clear separation of models, views, routers, schemas, services, consumers, and configuration.

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
- Inventory, stock, quotation, ordering, and management systems
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
