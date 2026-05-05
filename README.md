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
  <strong>Backend developer building real-world business systems, partner portals, API-driven platforms, and Dockerized backend tools with clean, maintainable workflows.</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Backend+Development+Enthusiast;Django+%7C+FastAPI+%7C+PostgreSQL+%7C+Docker;Business+Management+Systems;Partner+Self-Quotation+Platforms;Role-Based+REST+APIs;Flask+API+Integrations;Always+Learning,+Always+Improving&center=true&width=950&height=40">
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

My main interest is creating backend solutions that are reliable, maintainable, and useful in real business workflows. I enjoy backend development because it involves **designing systems, structuring data, organizing business logic, integrating external services, and solving real operational problems**.

Currently, I am studying **Bachelor's Degree in Computer Science with an emphasis in Systems Analysis** at the **National University of Asunción**, Faculty of Polytechnic.

<br clear="right"/>

---

## 🎯 Current Goal

I am actively looking for **remote opportunities as a Junior Backend Developer**, especially with:

**Python · Django · FastAPI · PostgreSQL · Redis · Docker · Docker Compose · REST APIs**

My goal is to contribute to real-world backend systems while growing through production-oriented development practices.

---

## 🚀 Backend Projects

A compact overview of the systems I have built, adapted, or prepared as public backend projects.

These projects are designed to be **reproducible locally using Docker**, with clear setup commands, environment-based configuration, external API integration, and production-like backend structure.

<table>
  <tr>
    <td width="50%" valign="top">

### 🔹 SWAP Public

**Django Business Management System**

Public version of an internal business management system built with **Django, PostgreSQL, Docker, Redis, Gunicorn, and WhiteNoise**.

<p>
  <a href="https://github.com/FrancoSoilan-DEV/swap-public">
    <img src="https://img.shields.io/badge/View%20Repository-GitHub-black?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

**Focus:**  
Business workflows · Role-based access · PostgreSQL · Docker Compose · Initial data seeding

**Run locally:**

```bash
git clone https://github.com/FrancoSoilan-DEV/swap-public.git
docker compose up --build
docker compose exec web sh scripts/docker-init.sh
```

<details>
  <summary><strong>View project details</strong></summary>

<br>

**What it demonstrates:**

- Modular Django project architecture
- PostgreSQL-backed relational database structure
- Docker and Docker Compose local setup
- Role-based access using Django groups and permissions
- Custom initialization script for repeatable setup
- Static files handled with WhiteNoise
- Initial data seeding through Django management commands
- Multiple business modules inside one system

**Main modules included:**

- Authentication and role-based redirection
- Human Resources / TTHH
- IT / Informatica
- Gatehouse / Porteria
- Technician panel / Tecnico
- Technical Service / Servicio Tecnico
- Weekly backup control
- Backup history
- Inventory management
- Equipment management
- Maintenance scheduling
- Entry and exit records
- Excel and PDF exports

</details>

</td>
<td width="50%" valign="top">

### 🔹 S7 Partners

**Partner Self-Quotation & Order Management Portal**

Django-based partner portal where commercial partners can browse enabled products, generate self-quotations, preview automatic pricing, submit orders, manage stock, and receive email notifications after staff review.

<p>
  <a href="https://github.com/FrancoSoilan-DEV/s7-partners">
    <img src="https://img.shields.io/badge/View%20Repository-GitHub-black?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

**Focus:**  
Self-quotation · Pricing rules · Order approvals · Stock tracking · Email notifications · i18n

**Run locally:**

```bash
git clone https://github.com/FrancoSoilan-DEV/s7-partners.git
docker compose -f docker-compose.dev.yml up --build
```

<details>
  <summary><strong>View project details</strong></summary>

<br>

**What it demonstrates:**

- Django-based partner portal with separate partner and admin areas
- Custom Django user model with partner-specific business fields
- Automatic quotation and pricing preview workflow
- Order approval/rejection flow for staff users
- Stock updates after accepted orders
- Email notifications using Brevo SMTP
- Internationalization with Spanish and English support
- Docker Compose setup for development, test, and production-style environments
- Gunicorn + Nginx test/production deployment flow
- Cloudinary integration for media storage
- Django REST Framework usage

**Main business workflow:**

1. The company creates and manages partner users.
2. Staff configures products, regions, currencies, client types, and pricing rules.
3. Partners log in with assigned credentials.
4. Partners browse the catalog and select products.
5. The system calculates totals, discounts, multiplicators, and final prices.
6. Partners submit orders or quotations.
7. Staff users review pending orders.
8. Staff accepts or rejects orders.
9. Partners receive email notifications.
10. Stock and historical records are updated when orders are accepted.

**Main technologies:**

- Python 3.12
- Django 5.2
- Django REST Framework
- PostgreSQL 15
- Docker and Docker Compose
- Gunicorn
- Nginx
- WhiteNoise
- Cloudinary
- django-rosetta
- Brevo SMTP
- Spanish and English internationalization

</details>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔹 FastAPI Vet Software

**Role-Based Veterinary Clinic REST API**

Production-oriented RESTful backend for veterinary clinic management, built with **FastAPI, PostgreSQL, Docker, SQLAlchemy, Alembic, JWT authentication, and Nginx**.

<p>
  <a href="https://github.com/FrancoSoilan-DEV/FastAPI-vet-software">
    <img src="https://img.shields.io/badge/View%20Repository-GitHub-black?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

**Focus:**  
FastAPI · Role-based access · JWT auth · PostgreSQL · Alembic · Docker · Nginx

**Run locally:**

```bash
git clone https://github.com/FrancoSoilan-DEV/FastAPI-vet-software.git
docker compose -f docker/docker-compose.yml up --build
```

<details>
  <summary><strong>View project details</strong></summary>

<br>

**What it demonstrates:**

- RESTful backend architecture with FastAPI
- Role-based workflows for managers, receptionists, and veterinarians
- JWT access tokens with refresh token rotation
- Argon2 password hashing
- SQLAlchemy 2.0 ORM structure
- Alembic database migrations
- PostgreSQL-backed persistence
- Docker Compose setup with API, database, and Nginx
- Swagger documentation through FastAPI
- Structured routers, schemas, services, models, and database layers

**Main roles:**

- **Manager:** creates and manages users, views staff activity
- **Receptionist:** registers consultations and manages medication inventory
- **Veterinarian:** views assigned consultations and creates/edits diagnoses

**Main technical features:**

- JWT access token with short expiration
- Refresh token rotation
- Token versioning for session invalidation
- Role-based dependencies
- Consultation workflow
- Medication inventory
- Diagnosis workflow
- PostgreSQL health check
- Dockerized development environment

**Local URLs:**

```text
http://localhost
http://localhost:8000
http://localhost:8000/docs
http://localhost:8000/health/db
```

**Useful setup commands:**

```bash
docker compose -f docker/docker-compose.yml exec api sh -lc "alembic -c /code/config/migrations/alembic.ini upgrade head"
docker compose -f docker/docker-compose.yml exec api python /code/docker/speed.py
```

</details>

</td>
<td width="50%" valign="top">

### 🔹 Flask Lightning

**Lightning Strike Data Tracker**

Single-page Flask web application that searches real lightning strike data through the **Weatherbit API**, displays results in a table, and exports them as CSV.

<p>
  <a href="https://github.com/FrancoSoilan-DEV/Flask-Lightning">
    <img src="https://img.shields.io/badge/View%20Repository-GitHub-black?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

**Focus:**  
Flask · Weatherbit API · OpenStreetMap · Docker · CSV export · API proxy

**Run locally:**

```bash
git clone https://github.com/FrancoSoilan-DEV/Flask-Lightning.git
cd Flask-Lightning
docker compose up --build
```

<details>
  <summary><strong>View project details</strong></summary>

<br>

**What it demonstrates:**

- Flask backend acting as a proxy between the browser and Weatherbit API
- Server-side API key handling
- Real-time lightning search using latitude, longitude, radius, and minutes back
- Historical lightning search using date ranges
- OpenStreetMap iframe integration for location reference
- Coordinate selector with city presets and manual latitude/longitude input
- Results table with lightning timestamp, coordinates, and distance
- Summary statistics for total strikes, closest strike, and farthest strike
- Progress bar for multi-day historical queries
- CSV export from frontend results
- Dockerized local development environment

**Main features:**

- Real-time lightning search up to 45 minutes back
- Historical lightning search from supported Weatherbit dates
- Configurable search radius up to 75 km
- Weatherbit API integration
- OpenStreetMap visual reference
- CSV export
- Single-page frontend with HTML, CSS, and JavaScript
- Flask debug mode with auto-reload through Docker volumes

**Main technologies:**

- Python 3.11
- Flask 3.0.3
- Requests
- Docker
- Docker Compose
- Weatherbit API v2.0
- OpenStreetMap
- HTML, CSS, and JavaScript

**Local URL:**

```text
http://localhost:5000
```

**Useful commands:**

```bash
docker compose up
docker compose down
docker compose logs web
```

</details>

</td>
</tr>
</table>

---

## 💼 Experience Highlights

I have worked on internal business systems, backend APIs, external API integrations, and business modules focused on real operational needs:

- Designed relational database structures for **asset, inventory, backup, employee, partner, order, stock, consultation, medication, diagnosis, and service tracking**
- Developed internal systems using **Django**, forms, templates, class-based views, function-based views, permissions, and administrative workflows
- Built API-driven backend workflows using **FastAPI**, SQLAlchemy, Pydantic, routers, services, schemas, and role-based access
- Built Flask-based tools for **external API integration, data search, filtering, visualization, and CSV export**
- Built partner-facing workflows for **self-quotation, order submission, pricing previews, stock management, and order history**
- Implemented pricing logic involving **client types, quantity-based multiplicators, special user multiplicators, discounts, regions, and currencies**
- Implemented business rules for **technical service management**, including status control, payment tracking, and historical reporting
- Built workflows for **employee gate access control**, check-in/check-out records, and historical tracking
- Created modules for **weekly backup management**, including backup states, weekly reset logic, and duplicate prevention
- Worked on **inventory and equipment management**, including equipment categories, maintenance calendars, and status tracking
- Organized backend logic across models, views, templates, forms, utilities, APIs, services, schemas, and management commands
- Worked with data consistency, validations, authentication, protected workflows, dashboards, analytics, external APIs, and internal reporting needs

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
- External API integration
- CSV export workflows

</td>
</tr>
</table>

---

## 🧩 Production-oriented Practices

I am focused on building backend projects with practices closer to real production environments:

- Containerized applications using **Docker** and **Docker Compose**
- Environment-based configuration using `.env` files
- PostgreSQL-backed application design
- Structured backend architecture for maintainability
- Clear separation of models, views, routers, schemas, services, forms, APIs, business rules, and configuration
- Custom Django management commands for repeatable setup
- Alembic migrations for FastAPI/SQLAlchemy projects
- Initial data seeding for predictable local environments
- API testing and validation with **Postman** and Swagger docs
- Authentication, permissions, groups, roles, and protected workflows
- Gunicorn/Nginx and Uvicorn/Nginx deployment flows
- Static files handling with WhiteNoise
- Public repository safety with `.env.example` and secret isolation
- External API proxying to keep credentials server-side
- Git-based collaboration using **Git, GitHub, and GitLab**

---

## 🧠 Backend Mindset

I enjoy backend development because it involves designing systems, structuring data, integrating services, and solving real-world operational problems.

I am especially interested in:

- Designing clean and maintainable data models
- Building APIs and backend workflows that are easy to understand and consume
- Keeping business logic organized and reusable
- Improving internal tools and administrative systems
- Connecting databases, services, users, permissions, and business workflows
- Creating systems that can be initialized and reproduced with clear setup commands
- Turning real operational processes into structured software systems

---

## 📚 Currently Learning

- Advanced Django and FastAPI development
- API design and authentication best practices
- Docker-based development and deployment workflows
- Scalable database structures
- Testing, documentation, and production-ready backend architecture

---

## 🛠️ What I Like to Build

- REST APIs and backend systems
- Admin dashboards and partner portals
- Authentication and role-based workflows
- Inventory, stock, quotation, and management systems
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
