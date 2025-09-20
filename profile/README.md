Hi there, dotnetmicroservices001 is a home for my dotnet projects. 

# GamePlay Economy

**A cloud-native, event-driven marketplace built with .NET 8 microservices and a React SPA**

GamePlay Economy is a study/practice on how to design, ship, and operate a **secure, resilient, and observable distributed application**.
Players browse items, make purchases, and see live order status updates.

---

## 🔴 Live Demo

- **Website:** [GamePlayEconomy LIVE](https:gameplayeconomy.com)  


---

## 🧩 System Overview

- [**Identity Service**](https://github.com/dotnetmicroservice001/Play.Identity) - OAuth 2.0 (PKCE), role-aware JWTs  
- [**Catalog Service**](https://github.com/dotnetmicroservice001/Play.Catalog) — Item definitions, prices 
- [**Inventory Service**](https://github.com/dotnetmicroservice001/Play.Inventory) — Stock management, grants, availability events  
- [**Trading Service**](https://github.com/dotnetmicroservice001/Play.Trading) — Saga-based orchestration of reservations and wallet debits  
- [**Frontend (React SPA)**](https://github.com/dotnetmicroservice001/Play.Frontend) — Live status updates via SignalR
- [**Common Library**](https://github.com/dotnet-microservices/Play.Common) — Shared contracts, logging, telemetry, and DI setup across services  
- [**Infra**](https://github.com/dotnet-microservices/Play.Infra) — Certificates, Kubernetes manifests, Helm charts
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
