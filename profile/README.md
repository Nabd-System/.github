<div align="center">

# 🩺 Nabd — نبض
###  Smart Healthcare Management Platform

> A comprehensive healthcare platform designed to digitalize and integrate clinical, administrative, and analytical operations within healthcare institutions.

[![Backend](https://img.shields.io/badge/Backend-ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet)](https://github.com/Nabd-System/Backend-API)
[![Frontend](https://img.shields.io/badge/Frontend-React.js-61DAFB?style=for-the-badge&logo=react)](https://github.com/Nabd-System/Frontend)
[![Mobile](https://img.shields.io/badge/Mobile-Flutter-02569B?style=for-the-badge&logo=flutter)](https://github.com/Nabd-System/Mobile)
[![License](https://img.shields.io/badge/License-Academic-green?style=for-the-badge)]()

---

**South Valley National University** · Faculty of Computer and Artificial Intelligence · Graduation Project · June 2026

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [System Architecture](#-system-architecture)
- [Modules](#-modules)
- [User Roles](#-user-roles)
- [Repositories](#-repositories)
- [Team](#-team)

---

## 🔍 About

**Nabd (نبض)** is a comprehensive healthcare management platform that centralizes and digitalizes hospital operations. It connects administrative, clinical, laboratory, radiology, and patient-related services through a unified ecosystem accessible via both **web dashboard** and **mobile application**.

Nabd addresses the growing challenges faced by healthcare institutions:
- Fragmented and paper-based workflows
- Delayed communication between departments
- Inefficient patient record management
- Lack of intelligent clinical decision support

---

## ✨ Features

### 🏥 Core Healthcare Features
- **Unified Patient Record** — Complete longitudinal medical history across all departments
- **Appointment Scheduling** — Intelligent booking with conflict prevention and attendance tracking
- **Clinic Visit Management** — End-to-end doctor/nurse workflow tracking
- **Laboratory Integration** — Test ordering, result management, and report delivery
- **Radiology Integration** — Imaging procedure scheduling and report storage
- **Prescription Management** — Digital prescription creation and tracking
- **Medical History** — Full access to visits, diagnoses, and treatment history

### 🤖 AI-Powered Features
- AI summarization of **laboratory reports**
- AI summarization of **radiology reports**
- **AI chatbot** assistance for patients
- Automatic **medical history summarization** for doctors
- Intelligent **diagnosis suggestions** and recommended tests

### 🔐 Security & Compliance
- JWT-based secure authentication
- Role-Based Access Control (RBAC)
- Encrypted communication and data storage
- Immutable audit logs for all sensitive operations
- Full activity tracking across all modules

### 📊 Administration & Analytics
- Admin dashboards with real-time insights
- Reporting and analytics tools
- Audit log management
- Multi-department oversight

---

## 🛠 Tech Stack

### Backend
| Technology | Purpose |
|---|---|
| **ASP.NET Core (.NET)** | Backend framework |
| **RESTful API** | API architecture |
| **Microsoft SQL Server** | Primary database |
| **JWT** | Authentication & authorization |
| **Hugging Face API** | AI / ML services |

### Frontend (Web)
| Technology | Purpose |
|---|---|
| **React.js + TypeScript** | UI framework |
| **Tailwind CSS** | Styling |
| **Redux Toolkit + RTK Query** | State management & data fetching |

### Mobile
| Technology | Purpose |
|---|---|
| **Flutter (Dart)** | Cross-platform mobile app |

---

## 🏗 System Architecture

```
┌─────────────────────────────────────────────────┐
│                   Nabd Platform                  │
│                                                  │
│   ┌─────────────┐        ┌──────────────────┐   │
│   │  React.js   │        │  Flutter Mobile  │   │
│   │ Web Dashboard│        │   Application    │   │
│   └──────┬──────┘        └────────┬─────────┘   │
│          │                        │              │
│          └──────────┬─────────────┘              │
│                     │                            │
│           ┌─────────▼──────────┐                 │
│           │  ASP.NET Core API  │                 │
│           │   (RESTful API)    │                 │
│           └─────────┬──────────┘                 │
│                     │                            │
│        ┌────────────┼────────────┐               │
│        │            │            │               │
│   ┌────▼────┐  ┌────▼────┐ ┌────▼────┐          │
│   │  MSSQL  │  │   AI    │ │  Audit  │          │
│   │   DB    │  │Services │ │  Logs   │          │
│   └─────────┘  └─────────┘ └─────────┘          │
└─────────────────────────────────────────────────┘
```

---

## 📦 Modules

| Module | Description |
|--------|-------------|
| 🔐 **Authentication & Authorization** | Login, role-based access, session management |
| 👤 **Patient Management** | Registration, profile, medical history |
| 📅 **Appointment Scheduling** | Booking, rescheduling, cancellation, reminders |
| 🏥 **Clinic Visits** | Doctor/nurse visit tracking, diagnoses, prescriptions |
| 🧪 **Laboratory** | Test ordering, result entry, AI report summarization |
| 🩻 **Radiology** | Imaging scheduling, report storage, AI summarization |
| 🤖 **AI Assistant** | Chatbot, clinical suggestions, auto-summarization |
| 📱 **Mobile Application** | Patient-facing Flutter app |
| 🔧 **Administration** | Dashboards, reports, audit logs, user management |

---

## 👥 User Roles

| Role | Access |
|------|--------|
| 🛡️ **Administrator** | Full system access, user management, reports |
| 👨‍⚕️ **Doctor** | Patient records, clinic visits, prescriptions, AI suggestions |
| 👩‍⚕️ **Nurse** | Clinic assistance, vital signs, patient notes |
| 🧑‍💼 **Receptionist** | Appointment management, patient registration |
| 🔬 **Lab Technician** | Laboratory orders, result entry |
| 📡 **Radiology Staff** | Imaging procedures, report management |
| 🙋 **Patient** | Mobile app — appointments, results, medical history, AI chat |

---

## 📁 Repositories

| Project | Tech | Repository |
|---------|------|------------|
| 🔧 **Backend API** | ASP.NET Core · MSSQL | [Nabd-System/Backend-API](https://github.com/Mootaaz-aly/Nabd) | 
| 🌐 **Frontend** | React.js · TypeScript · Tailwind | [Nabd-System/Frontend](https://github.com/AmnaZaher/Login-page-Hospital) | 
| 📱 **Mobile App** | Flutter · Dart | [Nabd-System/Mobile](https://github.com/ahmed24E/nabd) | 

---

## 👨‍💻 Team
 
| Name | Team |
|------|------|
| Mootaaz Mohamed | 🔧 BackEnd |
| Mohamed Hesham | 🔧 BackEnd |
| Mohamed Ali | 🔧 BackEnd |
| Ahmed Eid | 📱 Flutter |
| Areej Shawky | 🔧 BackEnd |
| Amna Zaher | 🌐 FrontEnd |
| Hana Serag | 🔧 BackEnd |
| Mai Assad | 🌐 FrontEnd |
| Sara Magdy | 🎨 UI/UX |
| Tasneem Nehad | 🌐 FrontEnd |
 
---



<div align="center">

**South Valley National University — Faculty of Computer and Artificial Intelligence**

Built with ❤️ by the Nabd Team · June 2026

</div>
