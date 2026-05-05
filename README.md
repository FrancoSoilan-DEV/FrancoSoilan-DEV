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
  <strong>Backend developer building real-world business systems, APIs, real-time workflows, and Dockerized backend platforms.</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Backend+Development+Enthusiast;Django+%7C+FastAPI+%7C+PostgreSQL+%7C+Docker;Real-world+Business+Systems;Role-Based+REST+APIs;Real-time+Django+Applications;Always+Learning,+Always+Improving&center=true&width=950&height=40">
</p>

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

I am actively looking for **remote opportunities as a Junior Backend Developer**, especially with:

**Python · Django · FastAPI · PostgreSQL · Redis · Docker · Docker Compose · REST APIs**

My goal is to contribute to real-world backend systems while growing through production-oriented development practices.

---

## 🚀 Projects

A compact overview of my main backend projects.  
Most of them are designed to be **reproducible locally using Docker**, with clear setup commands and production-like structure.

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

### Systems & Data

- Designed relational models for inventories, orders, users, services, stock, payments, and operational records.
- Built Django systems with role-based modules, protected views, dashboards, reports, and exports.
- Organized backend logic across models, views, services, APIs, consumers, and management commands.

</td>
<td width="50%" valign="top">

### APIs & Real-time

- Built FastAPI backends with routers, schemas, services, SQLAlchemy, Alembic, JWT auth, and role-based access.
- Implemented real-time Django workflows using Channels, Redis, WebSockets, ASGI, and role-specific dashboards.
- Created Flask tools for external API proxying, data filtering, visualization, and CSV export.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Business Logic

- Implemented quotation, pricing, stock, payment, backup, service, inventory, and access-control workflows.
- Worked with discounts, multiplicators, currencies, order states, approval flows, and historical records.
- Built systems around real operational processes, not isolated demo features.

</td>
<td width="50%" valign="top">

### Reliability

- Applied validation, protected workflows, repeatable initialization, and environment-based configuration.
- Used Docker-based setups to make projects easier to run, test, and review locally.
- Focused on clean structure, reproducible setup, and practical documentation.

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

<table>
  <tr>
    <td width="50%" valign="top">

### Architecture & Structure

- Modular Django apps and service-oriented FastAPI structure.
- Clear separation of models, views, routers, schemas, services, forms, consumers, and configuration.
- Business logic organized for maintainability, not only for functionality.

</td>
<td width="50%" valign="top">

### Reproducible Environments

- Docker and Docker Compose for local development.
- `.env` based configuration and safe `.env.example` documentation.
- Initial data seeding and setup scripts for predictable environments.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Data & Security

- PostgreSQL-backed application design.
- Authentication, permissions, groups, roles, and protected workflows.
- Secret isolation, server-side API proxying, and public repository safety.

</td>
<td width="50%" valign="top">

### Deployment-oriented Setup

- Gunicorn/Nginx, Uvicorn/Nginx, and Daphne/Nginx deployment flows.
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
  <a href="mailto:TU_EMAIL_AQUI">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-red?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>

  <a href="https://www.linkedin.com/in/TU_LINKEDIN_AQUI">
    <img src="https://img.shields.io/badge/LinkedIn-Franco%20Soilan-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>

  <a href="https://github.com/FrancoSoilan-DEV">
    <img src="https://img.shields.io/badge/GitHub-FrancoSoilan--DEV-black?style=for-the-badge&logo=github&logoColor=white" />
  </a>

  <a href="https://gitlab.com/TU_USUARIO_DE_GITLAB">
    <img src="https://img.shields.io/badge/GitLab-Franco%20Soilan-orange?style=for-the-badge&logo=gitlab&logoColor=white" />
  </a>
</p>

---

<div align="center">
  <h3>☕ Fueled by coffee, curiosity, and backend development 🐱</h3>
</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&section=footer" />
</div>
