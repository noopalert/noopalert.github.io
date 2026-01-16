<!-- ===================== -->
<!--  GitHub Portfolio    -->
<!-- ===================== -->

<div align="center">

# 👋 Hi, I'm **Naufal Arie**
### Backend Engineer | Django & REST API Specialist

🚀 Building scalable backend systems & business forecasting platforms  

[![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)](#)
[![Django](https://img.shields.io/badge/Django-5.x-green?style=for-the-badge&logo=django)](#)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-blue?style=for-the-badge&logo=postgresql)](#)
[![REST API](https://img.shields.io/badge/REST-API-orange?style=for-the-badge)](#)

📍 Indonesia  
📧 Email: **your-email@email.com**  
💼 LinkedIn: **linkedin.com/in/yourprofile**

</div>

---

## 🧭 Navigation
- [👨‍💻 About Me](#-about-me)
- [🛠 Tech Stack](#-tech-stack)
- [📦 Featured Projects](#-featured-projects)
- [📊 System Architecture](#-system-architecture)
- [📈 Experience Highlights](#-experience-highlights)
- [📬 Contact](#-contact)

---

## 👨‍💻 About Me

I am a **Backend Engineer** with strong focus on **Django, Django REST Framework, and PostgreSQL**.  
I specialize in:

- Designing **clean REST APIs**
- Handling **complex business logic**
- Optimizing **database performance**
- Deploying production systems using **Nginx + Gunicorn**

💡 I enjoy turning complex requirements into **reliable and maintainable backend services**.

---

## 🛠 Tech Stack

### 🔹 Backend
- **Python 3.12**
- **Django 5.x**
- **Django REST Framework**
- **Celery (Async / Scheduler)**

### 🔹 Database
- **PostgreSQL**
- Table Partitioning
- Custom PL/pgSQL Functions
- Performance tuning & indexing

### 🔹 DevOps & Infrastructure
- **Nginx**
- **Gunicorn (Unix Socket)**
- **Linux (Ubuntu)**
- **Docker (Basic)**

### 🔹 Monitoring & Logging
- Prometheus
- Grafana
- Loki & Promtail
- django-prometheus

---

## 📦 Featured Projects

### 🚀 Foreplan – Business Forecasting Platform
**Role:** Backend Engineer / Technical Consultant  

**Tech:** Django, DRF, PostgreSQL, Machine Learning API

<details>
<summary><b>🔍 View Details</b></summary>

- Built REST APIs for:
  - Authentication & token validation
  - Project & forecasting process management
  - Data preprocessing & history uploads
- Implemented:
  - PostgreSQL **table partitioning per customer**
  - Custom **pagination & response format**
  - Background processing & long-running tasks
- Integrated:
  - Monitoring (Prometheus + Grafana)
  - Centralized logging (Loki)

</details>

---

### 📊 API Documentation & Integration
- Designed **Postman collections** for internal & client usage
- Created **training documentation** for API consumers
- Structured API modules:
  - Account
  - Validation
  - Upload Data
  - Forecasting
  - Project Management

---

## 📊 System Architecture

```text
[ Frontend (Django) ]
          |
          | REST API
          v
[ Backend API (DRF) ] -----> [ PostgreSQL ]
          |
          | Async / Jobs
          v
[ ML Engine (Python) ]
