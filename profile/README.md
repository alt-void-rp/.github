<h1 align="center">🚀 void:RP</h1>
<p align="center">
  <b>Open-source GTA V roleplay server built on <a href="https://altv.mp/">alt:V</a> with a modern microservice backend</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/alt:V-Framework-blue?style=for-the-badge&logo=rockstargames" />
  <img src="https://img.shields.io/badge/Docker-Ready-blue?style=for-the-badge&logo=docker" />
  <img src="https://img.shields.io/badge/PostgreSQL-DB-336791?style=for-the-badge&logo=postgresql" />
  <img src="https://img.shields.io/badge/Redis-Cache-red?style=for-the-badge&logo=redis" />
  <img src="https://img.shields.io/badge/Kafka-Events-black?style=for-the-badge&logo=apachekafka" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

---

## 🎮 What is void:RP?
void:RP combines the **real-time power of alt:V** for in-game logic with a **scalable, event-driven backend** running in **Docker microservices**.  
It’s not just a GTA V server — it’s a **framework** for building scalable multiplayer worlds.

---

## 🧩 Core Components
- **⚡ Alt:V Core** → pure real-time game logic (jobs, banking, vehicles, missions) with **zero lag**.  
- **🛠️ Docker Microservices** → independent services for auth, banking, taxi, donations, stats, notifications.  
- **🌐 API Gateway** → single entrypoint for game, website, launcher, Discord bots (SSL, rate limiting, load balancing).  
- **🗄️ Centralized Data** → PostgreSQL (persistent storage) + Redis (cache, sessions, queues).  
- **🔐 Secure by design** → JWT-based authentication across all services.  
- **📊 Monitoring stack** → Prometheus + Grafana + Sentry out of the box.  

---

## ✅ Why this architecture?
- 🛡️ **Stable game logic** → Alt:V stays clean, minimal, and restart-safe.  
- 🔄 **Independent scaling** → add more donate workers without touching taxi.  
- 🌍 **Flexible integrations** → website, launcher, Discord — all via one API.  
- 📈 **Performance & reliability** → caching, queues, monitoring are built-in.  
