# 👋 Hi, I'm Daniel Garcia Araque

<div align="center">

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Orbitron&size=30&duration=3000&pause=1000&color=00B2FF&center=true&vCenter=true&width=700&lines=Senior+Software+Lead+Architect;Engineering+Team+Lead;B2B+Platform+Specialist;Marketplace+%7C+Insurance+Tech+%7C+IoT+%7C+Cloud)

[![GitHub followers](https://img.shields.io/github/followers/DanielAraqueStudios?style=social)](https://github.com/DanielAraqueStudios)
[![GitHub stars](https://img.shields.io/github/stars/DanielAraqueStudios?style=social)](https://github.com/DanielAraqueStudios)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5E00?style=flat&logo=google-chrome&logoColor=white)](https://danielaraquestudios.github.io/my_CV/)
![Profile Views](https://komarev.com/ghpvc/?username=DanielAraqueStudios&color=00B2FF&style=flat-square)

</div>

## 🚀 About Me

**6+ years** building production-grade B2B platforms specializing in **marketplace platforms**, **insurance tech**, **IoT infrastructure**, and **cloud-native solutions**. I now lead and manage an engineering team, owning architecture, security review, and delivery. I design scalable, well-documented systems with sustainable architecture—not quick fixes.

- 🏗️ **Architecture-first mindset** with ADRs and modular design
- 👥 **Leading and managing a technical team** across microservices, frontend, and analytics infrastructure
- 📊 **10+ production systems** delivered with 90%+ test coverage
- 🔧 **20+ client projects** across healthcare, insurance, manufacturing, retail
- 🌾 **8,176 sensors** managed in IoT infrastructure (8 distributed sites)
- 📄 **50,000+ records** processed with 100% data integrity
- 🌍 **Bogota, Colombia** | Open to remote work
- 🎓 **Mechatronics Engineering** @ Universidad Militar Nueva Granada (exp. 2027)
- 🗣️ **Languages:** Spanish (Native) | English (C1 Advanced)

---

## 💼 Current Role

**Senior Software Lead Architect** @ Reserve Study Institute *(Mar 2026 - Present, Florida USA, Remote)*

Leading and managing the team behind **CAMVendors**, a commercial property vendor marketplace, plus its own analytics data warehouse:
- 🧩 Microservices backend (NestJS) + Angular frontend
- 🔁 Vendor deduplication engine with conflict-review API
- 💳 Stripe payment race-condition fix (atomic guards + DB uniqueness)
- 🧠 Two-lane vendor classification with pgvector + async LLM review
- 🛡️ Architecture and security review (IDOR, API throttling, concurrency)

---

## 🛠️ Tech Stack

### **Backend & APIs**
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Core:** NestJS • FastAPI • Prisma • Pydantic • SQLAlchemy • Pandas • Express.js • RabbitMQ • Stripe

### **Architecture & Design**
- Microservices and event-driven messaging
- Domain-driven design (DDD)
- Multi-tier systems (Edge + Cloud + Database)
- API-first architecture
- Architecture Decision Records (ADRs)

### **Data & Databases**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/-DynamoDB-4053D6?style=flat-square&logo=amazon-dynamodb&logoColor=white)

**Skills:** pgvector semantic search • Partitioning • Triggers • Materialized Views • ETL Pipelines • Data Warehousing • Time-series optimization

### **DevOps & Cloud**
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

**Tools:** Terraform • CloudFormation • IoT Core • Kinesis • Lambda • LocalStack • CI/CD pipelines

### **Frontend & Desktop**
![Angular](https://img.shields.io/badge/-Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PyQt](https://img.shields.io/badge/-PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white)

**Skills:** Angular • React • TypeScript • PyQt6 GUI • ReportLab • PyInstaller

### **Security & Quality**
- Application security review (IDOR, rate limiting, concurrency)
- X.509 certificate management (mTLS)
- TLS 1.3 encryption
- Type safety with mypy
- 90%+ test coverage (pytest)

### **Leadership**
- Team management and technical direction
- Code review and quality assurance
- Technical standards definition
- Mentoring and stakeholder collaboration

---

## 🎯 Featured Projects

### 🏢 CAMVendors Ecosystem
**Vendor Marketplace + Analytics Data Warehouse** | Reserve Study Institute

Leading the team building the core operational platform and the analytics warehouse feeding it real-time intelligence.

- Vendor deduplication engine (detection + conflict-review API)
- Transactional email system across 5 microservices via RabbitMQ
- Multi-modal vendor import: CSV/Excel, templates, manual entry, email extraction
- Warehouse ingesting FIPS geographic and UNIFORMAT II taxonomy data

**Tech:** NestJS • Angular • PostgreSQL • Prisma • RabbitMQ • Stripe • pgvector • AWS • Terraform

---

### 🔄 Conciliator Softseguros Celer
**Insurance Data Reconciliation Platform** | Production System

Built production-grade backend to automate insurance portfolio reconciliation processing **50,000+ records** with **100% data integrity**.

- 3-tier matching logic with 9-digit receipt tolerance
- Streaming architecture for large datasets
- Column mapping: 49 inputs → 23 standardized outputs
- 90%+ test coverage with sprint-based delivery

**Tech:** Python • FastAPI • Pandas • Pydantic • PostgreSQL • pytest

---

### 📄 Insurance Document Automation
**Collection Letter Generator** | SEGUROS UNIÓN

Desktop application for automated insurance collection letters with **zero technical dependencies**.

- PyQt6 Dark Mode GUI with 3-layer architecture
- DIAN NIT verification (Colombian tax authority)
- 24+ insurance companies pre-configured
- 45.48 MB standalone .exe distribution

**Tech:** Python 3.13 • PyQt6 • Pydantic • ReportLab • PyInstaller

---

### 🌾 IoT Agriculture Platform
**Multi-Site Smart Farming Infrastructure** | Enterprise-Scale

Designed comprehensive IoT infrastructure with **8,176 sensors** across **8 distributed sites**.

- Three-tier architecture (Edge + Cloud + Frontend)
- IP addressing: 65,536 addresses with /19 subnets
- 48 VLANs for network segmentation
- 98.5% uptime across all sites

**Tech:** Python • TypeScript • PostgreSQL • AWS IoT Core • MQTT • LoRaWAN

---

### 🏥 AWS IoT Healthcare Monitoring
**Vital Signs Monitoring System** | Real-Time Streaming

End-to-end IoT system for healthcare device monitoring with real-time anomaly detection.

- Event-driven: MQTT → IoT Core → Kinesis → Lambda → DynamoDB
- X.509 certificate authentication (mTLS)
- 5,247 messages with 100% success rate
- 115ms average end-to-end latency

**Tech:** Python • AWS IoT Core • Kinesis • DynamoDB • LocalStack

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=DanielAraqueStudios&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=DanielAraqueStudios&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=DanielAraqueStudios&theme=tokyonight&hide_border=true)

</div>

---

## 📈 Contribution Activity

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=DanielAraqueStudios&theme=tokyo-night&hide_border=true&area=true)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

![trophy](https://github-profile-trophy.vercel.app/?username=DanielAraqueStudios&theme=tokyonight&no-frame=true&no-bg=false&margin-w=4&column=7)

</div>

---

## 🏆 Technical Metrics

<div align="center">

| Metric | Value |
|--------|-------|
| 💼 Professional Experience | **6+ years** |
| 📊 GitHub Contributions (Last Year) | ![GitHub Contributions](https://img.shields.io/badge/dynamic/json?color=00B2FF&label=Contributions&query=$.contributions&url=https://github-contributions-api.jogruber.de/v4/DanielAraqueStudios?y=last) |
| 📦 Public Repositories | ![Repos](https://img.shields.io/badge/dynamic/json?color=00B2FF&label=Repos&query=$.public_repos&url=https://api.github.com/users/DanielAraqueStudios) |
| 🚀 Production Systems Delivered | **10+** |
| 👥 Client Projects Completed | **20+** |
| ✅ Test Coverage (Key Projects) | **90%+** |
| 💻 Desktop Apps Deployed | **10+** |
| ⭐ Total Stars | ![Stars](https://img.shields.io/github/stars/DanielAraqueStudios?style=flat&color=00B2FF) |
| 🍴 Total Forks | ![Forks](https://img.shields.io/badge/dynamic/json?color=00B2FF&label=Forks&query=$.forks&url=https://api.github.com/users/DanielAraqueStudios/repos) |

</div>

---

## 💼 Professional Experience

### Senior Software Lead Architect @ Reserve Study Institute
*March 2026 – Present | Florida, USA (Remote)*

- Lead and manage the engineering team; direct architecture, code reviews, and technical decisions
- CAMVendors: vendor dedup engine, transactional email system, Stripe race-condition fix
- Analytics data warehouse (FIPS + UNIFORMAT II) exposed via REST APIs
- Own architecture and security review; led remediation of IDOR, unthrottled paid APIs, concurrency bugs

### Full Stack Developer @ Unión Agencia de Seguros
*January 2025 – March 2026 | Medellín, Colombia*

- Insurance Document Automation System (PyQt6 + PDF generation)
- Conciliator Softseguros Celer (50,000+ records processed)
- Insurance Production Dashboard for business intelligence
- Data Migration Platform with DIAN API integration

### Web Developer @ Quantum Software and Marketing
*February 2020 – January 2025 (5 years) | Bogota, Colombia*

- 20+ production websites and applications delivered
- React frontends + Node.js/JavaScript backends
- Full project lifecycle: client to deployment
- Long-term client relationships (repeat engagements)

---

## 🎓 Education & Certifications

**Mechatronics Engineering** | Universidad Militar Nueva Granada  
*Expected Graduation: 2027*

**🏆 Misión TIC 2022 — Web Applications Development**  
MinTIC & Universidad Pontificia Bolivariana | 800 hours | December 2021

---

## 📫 Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/-Portfolio-FF5E00?style=for-the-badge&logo=google-chrome&logoColor=white)](https://danielaraquestudios.github.io/my_CV/)
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:est.daniel.garciaa@unimilitar.edu.co)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DanielAraqueStudios)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/danielaraque)

</div>

---

<div align="center">

### 💡 Open to

**Remote Work** | **B2B Platform Projects** | **Technical Consulting** | **Software Architecture** | **Engineering Leadership**

*Building scalable systems with sustainable architecture*

---

**📅 Last Updated:** ![Last Commit](https://img.shields.io/github/last-commit/DanielAraqueStudios/my_CV?style=flat&color=00B2FF)

</div>
