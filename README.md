# 🌦️ Smart Weather — Agile Scrum Project

> **An enterprise-grade weather intelligence platform** built using the Scrum framework — tracking epics, user stories, sprint planning, and delivery through Jira.

---

## 📖 Project Overview

| Field | Details |
|-------|---------|
| **Project Name** | Smart Weather |
| **Methodology** | Agile Scrum |
| **Tool** | Jira (Scrum Board) |
| **Client** | GTM (Global Technology & Meteorology) |
| **Sprints** | 3 Sprints (2-week cadence) |
| **Team Size** | 6 members |

### 🎯 Problem Statement

With climate change increasing the unpredictability of local weather conditions, businesses across agriculture, hospitality, travel, tourism, and healthcare need reliable, analytics-driven weather intelligence. **Smart Weather** aggregates data from multiple providers and uses analytics to deliver meaningful business insights.

### 💡 Example Use Cases

- ☕ **Beverage Forecasting** — Cold vs hot drink demand based on temperature/rainfall
- 🎪 **Event Management** — Visitor count predictions for outdoor events
- 🤧 **Health Alerts** — Seasonal illness likelihood in specific locations

---

## 🏛️ Epic Structure

The product backlog is organized into **5 core epics**:

| Epic # | Epic Name | Description | Priority |
|--------|-----------|-------------|----------|
| **EP-01** | 🔐 User Management & Access Control | Registration, login, roles, paid/free tiers | High |
| **EP-02** | 🌐 Weather Data Integration | API integrations, GPS/IP detection, data schema | High |
| **EP-03** | 🌤️ Core Weather Features | Current weather, forecasts, satellite imagery | High |
| **EP-04** | 📊 Analytics & Business Insights | Seasonal forecasts, custom business analytics | Medium |
| **EP-05** | 🖥️ Platform & Infrastructure | Responsive design, API publishing, advertisements | Medium |

---

## 📋 User Stories (15 Stories)

### EP-01 — User Management & Access Control

| Story ID | User Story | Story Points | Priority |
|----------|------------|--------------|----------|
| US-01 | As a **new visitor**, I want to register for a free account so that I can access basic weather features | 5 | High |
| US-02 | As a **business client**, I want to subscribe to paid plans so that I can access advanced analytics and forecasts | 8 | High |
| US-03 | As an **admin**, I want to manage access control for paid services so that unauthorized users cannot access premium features | 8 | High |

### EP-02 — Weather Data Integration

| Story ID | User Story | Story Points | Priority |
|----------|------------|--------------|----------|
| US-04 | As a **developer**, I want to integrate with multiple public weather APIs so that the platform can aggregate diverse data sources | 13 | High |
| US-05 | As a **user**, I want the system to auto-detect my location via GPS or IP so that I see relevant local weather without manual input | 8 | High |
| US-06 | As a **data engineer**, I want a structured schema and database to store location-based weather data so that queries are efficient | 8 | High |
| US-07 | As a **data scientist**, I want logic to reconcile and aggregate data from multiple providers so that conflicting data is resolved intelligently | 13 | Medium |

### EP-03 — Core Weather Features

| Story ID | User Story | Story Points | Priority |
|----------|------------|--------------|----------|
| US-08 | As a **user**, I want to see the current weather at my location so that I can plan my immediate activities | 5 | High |
| US-09 | As a **user**, I want to view 5, 10, and 15-day forecasts so that I can plan for the week and beyond | 8 | High |
| US-10 | As a **registered user**, I want to receive severe weather advisories so that I am alerted to dangerous conditions | 5 | High |

### EP-04 — Analytics & Business Insights

| Story ID | User Story | Story Points | Priority |
|----------|------------|--------------|----------|
| US-11 | As a **business client**, I want seasonal forecasts including precipitation and temperature trends so that I can plan seasonal operations | 8 | Medium |
| US-12 | As a **marketing manager**, I want to see satellite images and time-lapse videos so that I can visualize weather patterns visually | 8 | Medium |
| US-13 | As a **business analyst**, I want AI-driven recommendations (e.g., beverage consumption forecasts) so that I can make data-driven decisions | 13 | Medium |

### EP-05 — Platform & Infrastructure

| Story ID | User Story | Story Points | Priority |
|----------|------------|--------------|----------|
| US-14 | As a **developer**, I want to publish REST APIs for client apps so that third-party teams can build integrations | 8 | Medium |
| US-15 | As a **product owner**, I want a responsive portal design so that users on all devices (mobile, tablet, desktop) have a seamless experience | 8 | Medium |

---

## 🗓️ Sprint Planning — Release Plan

### Sprint 1 — Foundation (Weeks 1–2)
> *Goal: Set up the core infrastructure, user management, and basic weather display*

| Story ID | Story | Points |
|----------|-------|--------|
| US-01 | Free/paid user registration | 5 |
| US-02 | Subscription & payment plans | 8 |
| US-05 | GPS/IP-based location detection | 8 |
| US-06 | Weather data schema & database | 8 |
| US-08 | Show current weather | 5 |
| **Total** | | **34 pts** |

### Sprint 2 — Data & Features (Weeks 3–4)
> *Goal: Integrate weather APIs, build forecast features, and access control*

| Story ID | Story | Points |
|----------|-------|--------|
| US-03 | Access control for paid services | 8 |
| US-04 | Public weather API integrations | 13 |
| US-07 | Data reconciliation & aggregation | 13 |
| US-09 | 5/10/15-day forecasts | 8 |
| US-10 | Severe weather advisories | 5 |
| **Total** | | **47 pts** |

### Sprint 3 — Analytics & Platform (Weeks 5–6)
> *Goal: Analytics, satellite, responsive design, and API publishing*

| Story ID | Story | Points |
|----------|-------|--------|
| US-11 | Seasonal forecasts | 8 |
| US-12 | Satellite images & time-lapse video | 8 |
| US-13 | AI-driven business analytics | 13 |
| US-14 | REST API publishing | 8 |
| US-15 | Responsive design | 8 |
| **Total** | | **45 pts** |

---

## 🏃 Sprint 1 — Completed

Sprint 1 has been **started and completed** with the following task states:

| Task | Assigned To | Status |
|------|-------------|--------|
| Design registration UI | Alice | ✅ Done |
| Build registration API | Bob | ✅ Done |
| Payment gateway integration | Charlie | ✅ Done |
| GPS/IP detection module | Dave | ✅ Done |
| Design DB schema for weather data | Eve | ✅ Done |
| Implement DB migrations | Bob | ✅ Done |
| Build "current weather" widget | Alice | ✅ Done |
| QA & bug fixes — Sprint 1 | Frank | ✅ Done |

**Sprint Velocity**: 34 story points delivered ✅  
**Sprint Retrospective**: Team identified that API integration estimates needed buffer — adjusted in Sprint 2.

---

## 📸 Jira Screenshots

> All screenshots are included in the `/screenshots` folder of this repository.

| Screenshot | Description |
|------------|-------------|
| `01-epics.png` | Epics view in Jira showing all 5 epics with colors and linked stories |
| `02-backlog.png` | Full product backlog with all 15 user stories, story points, and epic links |
| `03-release-plan.png` | Release plan showing stories distributed across 3 sprints |
| `04-sprint1-board-in-progress.png` | Scrum board during Sprint 1 with tasks in To Do, In Progress, In Review |
| `05-sprint1-board-done.png` | Scrum board at Sprint 1 completion — all tasks in Done column |
| `06-sprint2-board.png` | Sprint 2 board showing active stories |
| `07-burndown.png` | Sprint 1 burndown chart |

---

## 🗂️ Subtask Breakdown (Example — US-04)

**US-04: Integrate with multiple public weather APIs**

| Subtask | Assignee | Estimate | Status |
|---------|----------|----------|--------|
| Research & shortlist weather API providers | Dave | 2h | Done |
| Set up API keys and authentication | Bob | 1h | Done |
| Build WeatherAPI.com connector | Dave | 4h | Done |
| Build OpenWeatherMap connector | Bob | 4h | Done |
| Build National Weather Service connector | Dave | 4h | Done |
| Write integration tests | Frank | 3h | Done |
| Document API connectors | Alice | 2h | Done |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React.js, Tailwind CSS |
| **Backend** | Node.js + Express |
| **Database** | PostgreSQL (weather data), Redis (caching) |
| **APIs** | OpenWeatherMap, WeatherAPI, National Weather Service |
| **Mobile** | React Native (iOS + Android) |
| **Infrastructure** | AWS (EC2, S3, CloudFront) |
| **Project Management** | Jira (Scrum) |
| **CI/CD** | GitHub Actions |

---

## 👥 Team

| Name | Role |
|------|------|
| Alice | Frontend Developer |
| Bob | Backend Developer |
| Charlie | Full Stack Developer |
| Dave | Data Engineer |
| Eve | Database Architect |
| Frank | QA Engineer |
| **Sarah** | Scrum Master |
| **Michael** | Product Owner |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-org/smart-weather.git
cd smart-weather

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your weather API keys to .env

# Run database migrations
npm run db:migrate

# Start development server
npm run dev
```

---

## 📁 Project Structure

```
smart-weather/
├── client/              # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── hooks/
├── server/              # Node.js backend
│   ├── routes/
│   ├── services/
│   │   └── weather-providers/
│   ├── models/
│   └── middleware/
├── mobile/              # React Native app
├── docs/                # Project documentation
├── screenshots/         # Jira screenshots
└── README.md
```

---

## 📊 Jira Project Setup Steps

1. **Create Jira Account** — Sign up at [jira.atlassian.com](https://jira.atlassian.com) (free tier available)
2. **New Project** → Select **Scrum** template → Name: `Smart Weather`
3. **Create Epics** — Add 5 epics with unique colors in the Roadmap view
4. **Add User Stories** — In the Backlog, create all 15 stories, link to epics, assign story points
5. **Create Sprints** — Create 3 sprints from the Backlog view
6. **Assign Stories to Sprints** — Drag stories into Sprint 1, 2, 3 accordingly
7. **Start Sprint 1** — Click "Start Sprint", set dates
8. **Move Tasks** — Move tasks across columns: To Do → In Progress → In Review → Done
9. **Complete Sprint** — Click "Complete Sprint" after all tasks are Done

---

## 🔗 Links

- 📋 [Jira Project Board](#) *(add your Jira link here)*
- 📖 [API Documentation](#)
- 🎨 [Figma Designs](#)

---

## 📜 License

This project is for academic/assignment purposes as part of Agile Scrum methodology coursework.

---

<p align="center">
  Made with ☁️ by the Smart Weather Team | Agile Scrum Project 2024
</p>
