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

| Field | Details |
| :-- | :-- |
| **Team Name** | `CSE4104-7B-T07` |
| **Section** | 7B |
| **Course** | CSE 4104: Software Development III |
| **Team Leader** | Alex Alin Gomes |

| # | Member | Student ID | Role |
| :-: | :-- | :-: | :-: |
| 1 | Sabbir Hossain | `11230321293` | Member |
| 2 | Ahte Shamul Hoque Nadim Biswas | `11230321297` | Member |
| 3 | Alex Alin Gomes | `11230321307` | 👑 Team Leader |
| 4 | Md Hamim Reza | `11230321311` | Member |

</div>

---

## ✨ Proposed Features

| Module | Key features | Role of AI |
| :-- | :-- | :-- |
| 🌧️ **Waterlogging Information** | Collect news from permitted RSS feeds; community reports with location, photo and severity; interactive map with verified and unverified markers; admin approve, reject or resolve | NLP classifies news (Waterlogging, Flood, Heavy Rainfall, Road Problem, Irrelevant) and extracts Khulna locations |
| 🎒 **Lost and Found** | Post lost or found items with photo, category, date and location; search and filter; secure claim requests; status Open, Claimed or Returned; no public phone numbers or addresses | Optional text matching of similar listings |
| ⚡ **Electricity Problem Reporting** | Report outages, low voltage, damaged poles and exposed wires; map view; duplicate-report control; status flow Submitted → Under Review → Acknowledged → In Progress → Resolved | None in MVP |
| 🗑️ **Garbage Collection** | Report garbage and request collection by waste category; map view; admin assigns collection teams; status flow Submitted → Approved → Assigned → Collection in Progress → Completed; basic statistics | None in MVP |


---

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

## 🗂️ Repository Structure

```text
cse4104-7b-t07-AI-Powered-City-Welfare-System/
├── frontend/          # React application
├── backend/           # Node.js and Express REST API
├── nlp-service/       # Python FastAPI NLP service
├── documentation/     # Proposal, SRS, diagrams, reports
└── README.md
```

> The folders above are the planned structure and will be filled in as development progresses.

---

## 🗓️ Roadmap

| Weeks | Milestone | Status |
| :-: | :-- | :-: |
| 1-2 | Proposal, SRS, architecture, ER diagram, wireframes, GitHub setup | 🟡 In progress |
| 3-4 | Project setup, database, authentication, basic dashboard | ⚪ Planned |
| 5-6 | Waterlogging, lost and found, electricity and garbage modules | ⚪ Planned |
| 7-8 | News dataset, NLP model, NLP API and integration | ⚪ Planned |
| 9-10 | Map integration and location filtering | ⚪ Planned |
| 11-12 | Admin dashboard, verification, cross-module integration | ⚪ Planned |
| 13 | Testing, security checks, bug fixing | ⚪ Planned |
| 14 | Deployment, documentation, final presentation | ⚪ Planned |

---


## 🚀 Getting Started

Setup and run instructions will be added as the project is built.

```bash
# Clone the repository
git clone https://github.com/hamimreza19/cse4104-7b-t07-AI-Powered-City-Welfare-System.git
cd cse4104-7b-t07-AI-Powered-City-Welfare-System
```

---

<div align="center">

**Team CSE4104-7B-T07** · CSE 4104 Software Development III
Northern University of Business and Technology, Khulna

Made with ❤️ for the people of Khulna

</div>
