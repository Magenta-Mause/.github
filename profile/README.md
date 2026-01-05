# Hi there, we are Magenta-Mause! 👋

We are a group of students passionate about software engineering, building robust web platforms, and exploring modern DevOps architectures. This organization serves as the home for our collaborative projects.

---

## 🏆 Project 1: Medals
**Turning effort into excellence.**

**Status:** ✅ Active / Stable
### Deployed on [**medals.jannekeipert.de**](https://medals.jannekeipert.de)

"Medals" is a comprehensive web platform designed to revolutionize performance tracking for athletes and coaches. It provides a centralized, secure, and user-friendly solution to record, analyze, and visualize performance metrics.

### Key Features
* **For Athletes:** A personal digital trophy case to log achievements and track progress.
* **For Coaches:** A command center to monitor team performance and manage administrative overhead.
* **Tech Highlights:** Role-based security, data visualization, and CSV bulk imports.

### Architecture & Repositories
The system is built on a robust Java Spring Boot backend and a responsive React frontend, containerized with Docker.

| Component | Description | Repository |
| :--- | :--- | :--- |
| **Backend** | Java Spring Boot REST API handling auth, logic, and data structures. | [**medals-backend**](https://github.com/magenta-mause/medals-backend) |
| **Frontend** | React + TypeScript SPA providing the interactive dashboard. | [**medals-frontend**](https://github.com/magenta-mause/medals-frontend) |
| **Deployment** | Docker Compose & Nginx configuration for containerized deployment. | [**medals-deployment**](https://github.com/magenta-mause/medals-deployment) |

---

## 🏠 Project 2: Cosy (Cost Optimised Server Yard)
**The Digital Caretaker for Game Servers.**

**Status:** 🚧 In Development

**Cosy** is an open-source platform for the orchestration and management of game servers (like Minecraft, Valheim, or CS:GO). Unlike typical administrative dashboards, Cosy features a unique "village" aesthetic where servers are represented as buildings in a pixel-art world.

### Core Concept
* **Cost Efficiency:** Optimized for performance on single-host systems (Root servers/VPS) with optional Kubernetes scaling.
* **Isolation:** Every game server runs in its own Docker container.
* **Advanced Observability:** Uses **Loki** for log aggregation (allowing live console streaming via WebSockets) and **InfluxDB** for performance metrics.
* **Hybrid Runtime:** Runtime-agnostic design (Docker local or Kubernetes cluster).

### Architecture & Repositories
Cosy utilizes a microservices approach with a Java monolith for control and a high-performance Rust service for external APIs.

| Component | Description | Repository |
| :--- | :--- | :--- |
| **Backend** | Java Spring Boot application acting as the central control center and log router. | [**Cosy-Backend**](https://github.com/magenta-mause/cosy-backend) |
| **Frontend** | React + TypeScript (Bun) interface rendering the "Village" UI. | [**Cosy-Frontend**](https://github.com/magenta-mause/cosy-frontend) |
| **Game API** | **Rust** microservice for fetching game assets (icons/art) from external sources. | [**Cosy-Gameapi**](https://github.com/magenta-mause/cosy-gameapi) |
| **Release**| The official Cost Optimized Server Yard download repo. | [**Cosy**](https://github.com/Magenta-Mause/Cosy)
| **Deployment** | Kubernetes (K8s) configuration files for modern cloud deployment. | [**Cosy-Deployment**](https://github.com/magenta-mause/cosy-deployment) |
| **Landing** | Public-facing marketing and information page. | [**Cosy-Landing-Page**](https://github.com/magenta-mause/cosy-landing-page) |
| **Templates** | COSY Templates — Official and community-maintained JSON templates for Docker Compose and Kubernetes used by COSY. | [**Cosy-Templates**](https://github.com/Magenta-Mause/Cosy-Templates) |

---

## 🛠 Our Tech Stack

Across our projects, we utilize a modern and diverse technology stack:

**Languages**
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white) ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=flat&logo=rust&logoColor=white)

**Frameworks & Libraries**
![Spring Boot](https://img.shields.io/badge/spring-%236DB33F.svg?style=flat&logo=spring&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB)

**DevOps & Infrastructure**
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=flat&logo=kubernetes&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=flat&logo=nginx&logoColor=white)

**Data & Observability**
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white) ![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat&logo=InfluxDB&logoColor=white) ![Grafana Loki](https://img.shields.io/badge/Grafana_Loki-FD7A0C?style=flat&logo=grafana&logoColor=white)

---

### 📬 Contact
Feel free to explore our repositories. If you have questions or want to contribute, open an issue in the respective repository!
