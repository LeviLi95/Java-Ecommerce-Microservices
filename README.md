# Full-Stack Architecture Evolution Lab (Monolith to Microservices)

This project is a full-stack e-commerce application built with **Spring Boot 3.2.3** and **React**. It serves as a laboratory for practicing architecture decomposition and system governance.

## 🎯 Project Goal
The primary objective of this repository is to demonstrate the evolution from a **Monolithic** architecture to a **Distributed Microservices** architecture, following a production-grade roadmap.

## 🚀 Roadmap
- [x] **Phase 1: Monolithic Baseline** (Current)
    - Establish a stable monolithic functional baseline (based on Module 15).
    - Containerize infrastructure (MySQL) using Docker Compose.
- [ ] **Phase 2: API Gateway & Traffic Governance**
    - Integrate **Apache APISIX** as the unified entry point.
    - Implement dynamic routing, rate limiting, and authentication at the gateway level.
- [ ] **Phase 3: Microservices Decomposition**
    - Decouple core domains (e.g., User/Auth Service, Product Service).
    - Implement inter-service communication using OpenFeign or gRPC.
- [ ] **Phase 4: Observability & Distributed Tracing**
    - Integrate **Apache SkyWalking** for non-intrusive monitoring.
    - Analyze performance bottlenecks and service dependencies via trace IDs.

## 🛠️ Tech Stack
- **Backend:** Spring Boot 3.2.3, Spring Data JPA, MySQL
- **Frontend:** React (TypeScript), Axios
- **Infrastructure:** Docker, Apache APISIX, Apache SkyWalking

## ⚙️ Getting Started
1. **Infrastructure Setup:**
   ```bash
   docker-compose up -d