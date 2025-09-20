## Hi there 



# Play Economy

**A cloud-native, event-driven marketplace built with .NET 8 microservices and a React SPA**

Play Economy is a study/practice on how to design, ship, and operate a **secure, resilient, and observable distributed application**.
Players browse items, make purchases, and see live order status updates.

---

## 🔴 Live Demo

- **Website:** https:gameplayeconomy.com  


---

## 🧩 System Overview

- **Identity Service** — OAuth 2.0 (PKCE), role-aware JWTs  
- **Catalog Service** — Item definitions, prices 
- **Inventory Service** — Stock management, grants, availability events  
- **Orders Service** — Saga-based orchestration of reservations and wallet debits  
- **Frontend (React SPA)** — Live status updates via SignalR

---

## 🛠️ Tech Stack

- **Backend:** .NET 8, ASP.NET Core, MassTransit (RabbitMQ / Azure Service Bus), MongoDB  
- **Frontend:** React, SignalR  
- **Architecture:** Event-driven microservices, Saga orchestration, Domain-Driven Design  
- **DevOps:** Docker, Kubernetes (AKS), Helm, GitHub Actions  
- **Observability:** OpenTelemetry, Prometheus, Jaeger, Seq

---

## 🔑 Highlights

- **Saga orchestration:** Orders coordinates inventory reservations and wallet debits with compensation paths  
- **Owned data per service:** No shared DBs; clear service boundaries  
- **Real-time UX:** Purchase status streams to the SPA via SignalR  
- **Deep visibility:** Traces, metrics, and logs correlated across services

---

👉 **Focus:** Demonstrating real-world engineering practices—secure identity, reliable distributed workflows, and end-to-end observability—wrapped in a product-style experience.
