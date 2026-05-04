<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&reversal=true" />
</div>

<h1 align="center">
  Hi, I'm Franco Jeremias Soilan Lopez 
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35" />
</h1>

<h3 align="center">
  Backend-focused Web Developer | Python • Django • FastAPI • Flask • PostgreSQL • Docker
</h3>

<p align="center">
  <strong>Backend developer with experience building real-world business systems using Django, PostgreSQL, Docker, and clean backend workflows.</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Backend+Development+Enthusiast;Python+%7C+Django+%7C+FastAPI+%7C+Flask+%7C+PostgreSQL;Business+Management+Systems;Partner+Self-Quotation+Platforms;Dockerized+Backend+Workflows;Always+Learning,+Always+Improving&center=true&width=950&height=40">
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

My main interest is creating backend solutions that are reliable, maintainable, and useful in real business workflows. I enjoy backend development because it involves **designing systems, structuring data, organizing business logic, and solving real operational problems**.

Currently, I am studying **Bachelor's Degree in Computer Science with an emphasis in Systems Analysis** at the **National University of Asunción**, Faculty of Polytechnic.

<br clear="right"/>

---

## 🎯 Current Goal

I am actively looking for **remote opportunities as a Junior Backend Developer**, especially with:

**Python · Django · FastAPI · Flask · PostgreSQL · Redis · Docker · Docker Compose · REST APIs**

My goal is to contribute to real-world backend systems while growing through production-oriented development practices.

---

## 🚀 Backend Projects

A compact overview of the systems I have built, adapted, or prepared as public backend projects.  
I focus on **real-world workflows, relational database design, Docker-based setup, maintainable backend structure, pricing logic, role-based access, and practical business automation**.

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

**Clone the repository:**

```bash
git clone https://github.com/FrancoSoilan-DEV/swap-public.git
```

**Main setup command:**

```bash
docker compose exec web sh scripts/docker-init.sh
```

This command applies migrations, loads required initial data, creates default users/groups/statuses, and collects static files.

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
- Redis
- Cloudinary
- django-rosetta
- Brevo SMTP
- Spanish and English internationalization

**Clone the repository:**

```bash
git clone https://github.com/FrancoSoilan-DEV/s7-partners.git
```

**Development command:**

```bash
docker compose -f docker-compose.dev.yml up --build
```

Open locally:

```text
http://localhost:7000
```

</details>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧾 Inventory & Backup System

**Asset and backup tracking workflow**

System focused on managing IT assets, equipment records, backup states, and historical tracking.

<img src="https://img.shields.io/badge/Status-In%20Progress-yellow?style=for-the-badge" />

**Focus:**  
Inventory · Backups · Equipment · PostgreSQL · Internal workflows

<details>
  <summary><strong>View project details</strong></summary>

<br>

**Technical focus:**

- Relational database design for assets and equipment
- Backup state tracking
- Weekly backup workflow logic
- Duplicate prevention rules
- Administrative views and forms
- Historical records
- Structured backend logic for internal operations

**Planned public version:**

`inventory-management-api`

The public version will focus on a cleaner API-based structure with:

- Django or FastAPI backend
- PostgreSQL database
- Docker Compose setup
- Authentication
- CRUD operations
- API documentation
- Clean README and setup guide

</details>

</td>
<td width="50%" valign="top">

### 🛠️ Technical Service System

**Service workflow and payment tracking**

Backend module focused on managing technical services, workflow states, payment control, and operational records.

<img src="https://img.shields.io/badge/Status-In%20Progress-yellow?style=for-the-badge" />

**Focus:**  
Service lifecycle · Payments · Business rules · Admin workflows · Reporting

<details>
  <summary><strong>View project details</strong></summary>

<br>

**Technical focus:**

- Service registration and tracking
- Status-based workflow control
- Payment tracking
- Historical reporting
- User-facing forms
- Administrative dashboards
- Backend validations
- Business logic organization

**Planned public version:**

`service-management-system`

The public version will focus on:

- Clean Django architecture
- PostgreSQL-backed workflows
- Dockerized local environment
- Admin dashboard logic
- Payment status management
- Documentation for setup and usage

</details>

</td>
</tr>
</table>

---

## 💼 Experience Highlights

I have worked on internal business systems and backend modules focused on real operational needs:

- Designed relational database structures for **asset, inventory, backup, employee, partner, order, stock, and service tracking**
- Developed internal systems using **Django**, forms, templates, class-based views, function-based views, permissions, and administrative workflows
- Built partner-facing workflows for **self-quotation, order submission, pricing previews, stock management, and order history**
- Implemented business rules for **technical service management**, including status control, payment tracking, and historical reporting
- Built workflows for **employee gate access control**, check-in/check-out records, and historical tracking
- Created modules for **weekly backup management**, including backup states, weekly reset logic, and duplicate prevention
- Worked on **inventory and equipment management**, including equipment categories, maintenance calendars, and status tracking
- Created quotation-related features for **clients, suppliers, and commercial partners**, including structured request and response flows
- Implemented pricing logic involving **client types, quantity-based multiplicators, special user multiplicators, discounts, regions, and currencies**
- Organized backend logic across models, views, templates, forms, utilities, APIs, and management commands
- Worked with data consistency, validations, user-facing forms, dashboards, analytics, and internal reporting needs

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
- Authentication and authorization basics
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

### Frontend Basics

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts" />
</p>

- HTML
- CSS
- JavaScript basics
- TypeScript basics
- Responsive interfaces
- Frontend integration with backend systems
- Django templates
- Internationalized UI basics

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
- Clear separation of models, views, forms, APIs, business rules, and configuration
- Custom Django management commands for repeatable setup
- Initial data seeding for predictable local environments
- API testing and validation with **Postman**
- Authentication, permissions, groups, staff roles, and protected workflows
- Gunicorn/Nginx-based deployment flow
- Static files handling with WhiteNoise
- Public repository safety with `.env.example` and secret isolation
- Git-based collaboration using **Git, GitHub, and GitLab**

---

## 🧠 Backend Mindset

I enjoy backend development because it involves designing systems, structuring data, and solving real-world operational problems.

I am especially interested in:

- Designing clean and maintainable data models
- Building APIs and backend workflows that are easy to understand and consume
- Keeping business logic organized and reusable
- Improving internal tools and administrative systems
- Connecting databases, services, users, permissions, and business workflows
- Writing code that is practical, readable, and easier to improve over time
- Creating systems that can be initialized and reproduced with clear setup commands
- Turning real operational processes into structured software systems

---

## 📚 Currently Learning

- Advanced Django development
- Django REST Framework best practices
- API design best practices
- Docker-based development workflows
- Scalable database structures
- Clean code and software architecture
- Production-ready web applications
- Better testing practices
- Backend project documentation
- Deployment workflows with Gunicorn and Nginx

---

## 🛠️ What I Like to Build

- Backend systems
- REST APIs
- Admin dashboards
- Database-driven applications
- Authentication systems
- Partner portals
- Self-service quotation systems
- Inventory and stock management systems
- Automation tools
- Internal business systems
- Dockerized web platforms
- Management systems with real-world use cases

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
