<div align="center">

# 🚗 BMW Financial Platform APIs

### High-Performance API Ecosystems for Global Automotive Finance

[![Status](https://img.shields.io/badge/Status-In_Production-10B981?style=flat-square&logo=checkmarx&logoColor=white)](https://bmwfinance.myaccount.co.za/login)
[![Live](https://img.shields.io/badge/Live_Platform-BMW_Finance-0066B2?style=flat-square&logo=bmw&logoColor=white)](https://bmwfinance.myaccount.co.za/login)
[![Company](https://img.shields.io/badge/BMW_Group_Malaysia-1C69D4?style=flat-square)](https://www.bmw-group.com/)
[![Role](https://img.shields.io/badge/Role-Senior_Software_Developer-6366F1?style=flat-square)]()
[![Since](https://img.shields.io/badge/Since-July_2025-F59E0B?style=flat-square)]()

[← Back to Profile](../GITHUB_PROFILE.md) · [← All Projects](../PROJECTS_INDEX.md)

</div>

---

## 📋 TL;DR

> Engineering **high-performance backend API ecosystems** for global automotive financial platforms at BMW Group Malaysia. Clean Architecture + CQRS + DDD with full Azure DevOps CI/CD, OAuth2/OIDC security, and event-driven RabbitMQ/Kafka pipelines.

| | |
|---|---|
| **Company** | BMW Group Malaysia |
| **Location** | Cyberjaya, Selangor · Hybrid |
| **Role** | Senior Software Developer |
| **Period** | Jul 2025 – Present |
| **Domain** | Automotive Financial Services |
| **Stack Core** | .NET 8 · Clean Architecture · CQRS · DDD · Azure DevOps |

---

## 🎯 What I'm Building

Engineering robust, high-performance backend APIs for **global automotive financial platforms** as part of a distributed Agile engineering team.

- Designing scalable **RESTful APIs** and microservices using **.NET 8** + ASP.NET Core adhering to **Clean Architecture** (API → Application → Domain → Infrastructure isolation)
- Implementing **CQRS with MediatR** + rich **Domain-Driven Design** domain models for complex financial transaction logic
- Securing enterprise-grade endpoints with **OAuth2 / OIDC**, JWT validation, and fine-grained **RBAC**
- Optimizing **EF Core** queries — LINQ optimization, Unit of Work, transaction safety, and index tuning for high throughput
- Orchestrating asynchronous pipelines with **RabbitMQ / Kafka** and **Hangfire** background jobs
- Driving zero-downtime **CI/CD** via **Azure DevOps** with complete **Swagger/OpenAPI** observability

---

## 🏗️ Architecture

```mermaid
graph TD
    Client["🖥️ Frontend Applications"] -->|OAuth2 / OIDC| APIGateway["🔀 API Gateway"]

    subgraph BMW["BMW Group — Microservices Architecture"]
        APIGateway --> API["🔷 .NET 8 Web API"]
        subgraph CA["Clean Architecture Layers"]
            API --> Application["🟢 Application Layer\nMediatR / CQRS\nCommands & Queries"]
            Application --> Domain["🟡 Domain Layer\nDDD — Entities, Aggregates,\nValue Objects, Domain Events"]
            Application --> Infrastructure["🟣 Infrastructure Layer\nRepositories, EF Core,\nExternal Services"]
        end
    end

    Infrastructure --> DB[("🗄️ SQL Server / PostgreSQL\nUnit of Work · Index Tuning")]
    Infrastructure --> MessageBroker{"📨 RabbitMQ / Kafka\nAsync Event Streaming"}
    Infrastructure --> Hangfire["⏰ Hangfire\nBackground Jobs & Scheduling"]
    MessageBroker --> Consumer["⚡ Event Consumers\nDecoupled Processing"]

    style Client fill:#1e293b,stroke:#6366f1,color:#e2e8f0
    style APIGateway fill:#3b82f6,stroke:#2563eb,color:#fff
    style API fill:#8b5cf6,stroke:#7c3aed,color:#fff
    style Application fill:#10b981,stroke:#059669,color:#fff
    style Domain fill:#f59e0b,stroke:#d97706,color:#1a1a1a
    style Infrastructure fill:#6366f1,stroke:#4f46e5,color:#fff
    style DB fill:#ef4444,stroke:#dc2626,color:#fff
    style MessageBroker fill:#ec4899,stroke:#db2777,color:#fff
    style Hangfire fill:#14b8a6,stroke:#0d9488,color:#fff
    style Consumer fill:#f97316,stroke:#ea580c,color:#fff
```

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Backend Framework** | .NET 8, ASP.NET Core Web API, C# |
| **Architecture Patterns** | Microservices, Clean Architecture, Domain-Driven Design (DDD), CQRS |
| **CQRS Implementation** | MediatR — Commands, Queries, Pipeline Behaviors |
| **Security & Auth** | OAuth2, OpenID Connect (OIDC), JWT Validation, RBAC |
| **Database & ORM** | SQL Server, PostgreSQL, Entity Framework Core, Unit of Work, Dapper |
| **Async / Messaging** | RabbitMQ, Apache Kafka, Hangfire Background Jobs |
| **DevOps & CI/CD** | Azure DevOps, Docker, Zero-downtime deployments |
| **Observability** | Serilog Structured Logging, Swagger/OpenAPI Documentation |

---

## 📊 Impact

| Metric | Detail |
|--------|--------|
| **Scale** | Supporting global automotive financial platforms |
| **Reliability** | Zero-downtime deployment pipelines via Azure DevOps |
| **Performance** | Optimized high-throughput EF Core queries + event-driven architecture |
| **Security** | Enterprise-grade OAuth2/OIDC + RBAC enforcement across all endpoints |

---

## 🏷️ Skills Demonstrated

`.NET 8` `.ASP.NET Core` `C#` `Microservices` `Clean Architecture` `Domain-Driven Design` `CQRS` `MediatR` `Azure DevOps` `OAuth2/OIDC` `JWT` `RBAC` `EF Core` `SQL Server` `PostgreSQL` `RabbitMQ` `Kafka` `Hangfire` `Enterprise Software`

---

<div align="center">

[← Back to Profile](../GITHUB_PROFILE.md) · [📁 All Projects](../PROJECTS_INDEX.md) · [💼 LinkedIn](https://linkedin.com/in/sarkeranik) · [📧 Contact](mailto:ach6266@gmail.com)

</div>
