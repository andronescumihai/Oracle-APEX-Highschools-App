# 🏫 Highschools NYC — Oracle APEX Web Application

> **Built during Oracle Tech Bootcamp Romania** | Oracle Pipera HQ, Bucharest — May 21, 2026

---

## 📌 Project Overview

**Highschools NYC** is a full-stack web application developed on **Oracle APEX** that enables students and parents to **search, filter, and apply to high schools** in New York City. The app integrates an **OCI GenAI assistant** that provides contextual school information on demand.

This project was built as part of an intensive one-day bootcamp at Oracle Romania, covering enterprise-grade cloud architecture, relational database modeling, and low-code development on Oracle APEX 24.2.

---

## ⚙️ Core Features

| Feature | Description |
|---|---|
| 🔍 **Smart Search & Filtering** | Filter schools by borough, interest area, attendance rate, safety score, and travel distance |
| 📄 **School Detail Pages** | Full profile per school with structured data and "Learn More" AI assistant |
| 📝 **Online Application Form** | Students can apply directly — captures student info, parent contact, and application letter |
| 🤖 **OCI GenAI Integration** | AI-powered assistant that answers questions about each school using Oracle Cloud's GenAI service |
| 🔐 **Authentication System** | Secure login with Oracle APEX Accounts + role-based authorization (Administration Rights) |
| 🔔 **Push Notifications** | Configured push notification credentials for real-time user updates |
| ⚙️ **User Settings** | Personalized settings panel including push notification preferences |

---

## 🛠️ Tech Stack

- **Platform:** Oracle APEX 24.2 (Release 24.2.15)
- **Database:** Oracle DB — relational schema with normalized tables for schools, boroughs, applications
- **AI Layer:** Oracle Cloud Infrastructure (OCI) GenAI — integrated via remote server credentials
- **Authentication:** Oracle APEX Accounts with custom authorization scheme
- **Frontend:** APEX Redwood Light theme (Oracle's enterprise UI framework)
- **Export Format:** Full Application Export (.sql) — importable into any Oracle APEX workspace

---

## 📁 Repository Structure

```
├── f1125.sql       # APEX Application Export — v1 (Application ID 1125)
├── f1130.sql       # APEX Application Export — v2 (Application ID 1130, final)
└── README.md
```

> `f1130.sql` is the final version. `f1125.sql` is an earlier iteration kept for version comparison.

---

## 🚀 How to Import & Run

1. Log in to your **Oracle APEX workspace** (requires Oracle APEX 24.x)
2. Go to **App Builder → Import**
3. Upload `f1130.sql` and follow the import wizard
4. Configure OCI GenAI credentials in **Workspace Utilities → Credentials** (required for AI features)
5. Run the application — default login via Oracle APEX Accounts

---

## 🧠 What I Learned

- Designing **relational database schemas** for real-world datasets (NYC school system)
- Building **multi-page APEX applications** with dynamic filters, forms, and navigation
- Integrating **Oracle Cloud AI services (OCI GenAI)** into a low-code environment
- Implementing **authentication and role-based authorization** in enterprise applications
- Understanding **secure cloud architecture patterns** used in production Oracle environments

---

## 📜 Context

This project was developed at the **Oracle Tech Bootcamp Romania** held at Oracle's Pipera headquarters in Bucharest on May 21, 2026. The bootcamp covered Oracle APEX, SQL, relational database modeling, and enterprise cloud architectures.

---

## 👤 Author

**Mihai-Alexandru Andronescu**
Student — Computer Science & Economics, ASE Bucharest

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/mihai-alexandru-andronescu-58792b33b/)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/andronescumihai)
