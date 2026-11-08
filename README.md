<div align="center">

# 🏙️ AI-Powered City Welfare System

### One platform for Khulna City: report problems, track their resolution, and understand local news with AI.

![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)
![Course](https://img.shields.io/badge/CSE%204104-Software%20Development%20III-blue?style=for-the-badge)
![Team](https://img.shields.io/badge/Team-CSE4104--7B--T07-purple?style=for-the-badge)

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Northern University of Business and Technology, Khulna**  
Department of Computer Science and Engineering

[📖 Description](#-project-description) •
[👥 Team](#-team-information) •
[✨ Features](#-proposed-features) •
[🛠️ Tech Stack](#️-technology-stack) •
[🗂️ Structure](#️-repository-structure) •
[🗓️ Roadmap](#️-roadmap)

</div>

---

## 📌 Project Title

**AI-Powered City Welfare System**: a full-stack web platform for Khulna City, Bangladesh.

---

## 📖 Project Description

Residents of Khulna face recurring urban problems: waterlogging in the rainy season, electricity faults, uncollected garbage and lost belongings. Information about these problems is scattered across news sites, social media pages and word of mouth. Citizens cannot easily find reliable, location-specific information, and complaints have no verification or status tracking.

The **AI-Powered City Welfare System** brings four civic needs into one platform:

| | Need | What the system provides |
| :-: | --- | --- |
| 🌧️ | **Waterlogging** | Classified local news and citizen reports on an interactive map |
| 🎒 | **Lost and Found** | Searchable listings with secure claim requests |
| ⚡ | **Electricity problems** | Reports with location, photo and status tracking |
| 🗑️ | **Garbage collection** | Collection requests assigned to teams and tracked to completion |

Citizens submit reports and follow their progress. Administrators verify, assign and resolve them from a dashboard. An NLP service reads local English and Bangla news, classifies waterlogging articles and extracts the affected Khulna locations.

> **Design principle:** AI results are always kept separate from verified facts. An incident is never marked as verified from an NLP result alone, and administrators make the final decision.

### 🎯 Objectives

- Let citizens report and track waterlogging, electricity and garbage problems, and post lost or found items.
- Classify local news with NLP and extract Khulna location names in English and Bangla.
- Show incidents and reports on an interactive map, with verified and unverified items clearly separated.
- Provide secure login with role-based access for citizens, administrators and optional collection staff.
- Give administrators a dashboard to review, verify, assign and resolve reports.
- Protect personal information and state clearly what the AI can and cannot do.

---

## 👥 Team Information

<div align="center">

### 🏷️ Team: `CSE4104-7B-T07` &nbsp;|&nbsp; 👑 Team Leader: Alex Alin Gomes
#### 📚 Course: CSE 4104: Software Development III

| # | Member | Student ID | Section | Role |
| :-: | :-- | :-: | :-: | :-: |
| 1 | Sabbir Hossain | `11230321293` | 7B | Member |
| 2 | Ahte Shamul Hoque Nadim Biswas | `11230321297` | 7B | Member |
| 3 | Alex Alin Gomes | `11230321307` | 7B | 👑 Team Leader |
| 4 | Md Hamim Reza | `11230321311` | 7B | Member |

</div>


---
## Proposed Features

### 1. Waterlogging Information & Monitoring
- Collects updates from permitted sources (e.g. RSS feeds) and accepts citizen reports with location, time and photos
- NLP classifies content and extracts Khulna location names in English and Bangla
- Incidents shown on a map with area filtering, labelled **verified**, **unverified** or **pending**
- Uncertain locations are marked uncertain, never guessed

### 2. Smart Lost & Found
- Post lost or found items with photo, category, description, date and location
- Search and filter by category, date and location
- AI suggests possible matches using image and text comparison
- Controlled claim-request process; phone numbers and addresses are never shown publicly

### 3. Electricity Outage Scheduling
- Area-wise planned outage notices with date, start time, duration, reason and source
- Administrators create, edit or cancel notices from the electricity authority's announcements
- Search by area and date; email and in-app alerts for subscribed areas
- Official schedules are kept separate from unconfirmed citizen observations
- AI extracts notice details and finds recurring patterns, but never creates a schedule

### 4. City Problem Reporting & Monitoring
- Report garbage, potholes, damaged roads, broken streetlights and drainage faults with photo, description and map location
- Gemini AI suggests category, summary and severity, and flags possible duplicates
- Moderators review and forward reports to the City Corporation
- Status flow: `Submitted → Under Review → Forwarded to Authority → In Progress → Resolved`

## 🛠️ Technology Stack

| Layer | Technology | Purpose |
| :-- | :-- | :-- |
| 🎨 **Frontend** | React.js, Tailwind CSS, React Router, Axios | Responsive interface, forms, dashboards |
| ⚙️ **Backend** | Node.js, Express.js, REST API, JWT, bcrypt, Prisma ORM | Authentication, business logic, database access |
| 🗄️ **Database** | PostgreSQL with PostGIS | Relational data and location queries |
| 🤖 **AI Integration** | Python, FastAPI, scikit-learn, spaCy, Pandas, TF-IDF, Logistic Regression; Gemini API (optional) | News classification, location extraction, optional lost and found matching |
| 🗺️ **Maps** | Leaflet, OpenStreetMap | Interactive Khulna map |
| 🚀 **Deployment** | Vercel, Render or Railway, Supabase | Hosting for frontend, backend, NLP service and database |
| 🧰 **Tools** | Git, GitHub, Postman, Figma, VS Code | Version control, API testing, UI design |

---

## 🗂️ Initial Repository Structure

```text
cse4104-7b-t07-AI-Powered-City-Welfare-System/
├── .github/
│   └── workflows/          # CI/CD pipelines (GitHub Actions)
├── frontend/               # Managed primarily on 'frontend' branch
│   ├── src/
│   └── package.json
├── backend/                # Managed primarily on 'backend' branch
│   ├── src/
│   └── package.json
├── database/               # Managed primarily on 'database' branch
│   ├── migrations/
│   └── seeds/
├── ai/                     # Managed primarily on 'ai' branch
│   ├── models/
│   └── scripts/
└── README.md

