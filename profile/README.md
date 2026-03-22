# Goalixa

**Goalixa** is an open-source, DevOps-driven productivity platform designed to help individuals plan, execute, and measure their work — while also serving as a real-world playground for modern infrastructure, SRE practices, and AI-assisted operations.

🌐 Website: https://goalixa.com  
📝 Blog: https://blog.goalixa.com  

---

## 🚀 Overview

Goalixa is more than a productivity app — it's a full-stack, microservices-based system built to explore:

- Scalable backend architecture  
- DevOps and GitOps workflows  
- Observability and reliability (SRE)  
- AI-assisted automation (via Syntra)  

It is actively developed as a personal platform to experiment, learn, and apply production-grade engineering practices.

---

## ✨ Features

- 🎯 Goal management (goals, subgoals, weekly planning)
- 📋 Projects and task management
- ⏱️ Time tracking per task
- 📅 Calendar view and weekly reports
- 🔁 Habit tracking with streaks and summaries
- 🧠 Daily planning, todos, and reminders

---

## 🏗️ Architecture

Goalixa is built using a microservices architecture:

### Core Services

- **Core API**  
  Main backend service (Flask + PostgreSQL) following a clean 3-layer architecture.

- **Auth Service** (`goalixa-auth`)  
  Independent authentication service with:
  - JWT-based authentication  
  - Google OAuth integration  
  - Prometheus metrics for monitoring  

- **BFF / API Gateway**  
  Backend-for-Frontend layer that:
  - Aggregates data from multiple services  
  - Simplifies client communication  
  - Acts as an entry point for frontend apps  

- **PWA Client** (`goalixa-pwa`)  
  Installable Progressive Web App (vanilla JS) that unifies:
  - Landing page  
  - Authentication  
  - Main application  

- **Landing Page** (`goalixa-landing`)  
  Static website for product presentation  

---

## ⚙️ Infrastructure & DevOps

Goalixa is designed and deployed using modern DevOps practices:

- 🐳 Docker for containerization  
- ☸️ Kubernetes (k3s) for orchestration  
- 🔄 GitOps workflows using ArgoCD  
- 📦 Container registry with Harbor  
- 📊 Observability stack (Prometheus + Grafana)  
- 🧪 Chaos engineering with Litmus  

---

## 🤖 AI Orchestration (Syntra)

Goalixa includes an experimental AI orchestration layer called **Syntra**:

- Multi-agent system (Planner, DevOps, Reviewer)
- Built using CrewAI and FastAPI
- Enables natural language-driven infrastructure operations
- Integrates with Kubernetes, Git, and logs
- Designed to act as an AI DevOps teammate

---

## 🧰 Tech Stack

- **Backend**: Python, Flask, PostgreSQL  
- **Auth**: JWT, OAuth (Google)  
- **Frontend**: Vanilla JS, PWA  
- **Infrastructure**: Docker, Kubernetes (k3s), Nginx  
- **DevOps**: ArgoCD, Harbor  
- **Observability**: Prometheus, Grafana  
- **AI Layer**: CrewAI, LangChain, Claude  

---

## 📖 Philosophy

Goalixa is built with a strong focus on:

- Learning by building real systems  
- Applying DevOps and SRE concepts in practice  
- Leveraging AI to reduce manual operational work  
- Designing systems that scale both technically and operationally  

---

## 🌍 Open Source

Goalixa is fully open-source and actively evolving.

Contributions, issues, and feedback are always welcome.

---

## 📌 Note

This project is continuously evolving as part of an ongoing effort to explore:
- Platform engineering  
- AI-assisted development  
- Infrastructure automation  

---
