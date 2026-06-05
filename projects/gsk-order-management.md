<div align="center">

# 📦 GSK Order Management System

### Enterprise Order Orchestration Platform for GlaxoSmithKline

[![Status](https://img.shields.io/badge/Status-In_Production-10B981?style=flat-square&logo=checkmarx&logoColor=white)](https://sweya.ai/products/regulatory-ai)
[![Live](https://img.shields.io/badge/Live-sweya.ai-10B981?style=flat-square&logo=safari&logoColor=white)](https://sweya.ai/products/regulatory-ai)
[![Company](https://img.shields.io/badge/Sweya_AI_(Client:_GSK)-8B5CF6?style=flat-square)]()
[![Role](https://img.shields.io/badge/Role-Sr._SE_→_Technical_Lead-EC4899?style=flat-square)]()
[![Duration](https://img.shields.io/badge/Apr_2023–Jan_2025-F59E0B?style=flat-square)]()
[![Pattern](https://img.shields.io/badge/Pattern-Event--Driven_Microservices-6366F1?style=flat-square)]()

[← Back to Profile](../GITHUB_PROFILE.md) · [← All Projects](../PROJECTS_INDEX.md)

</div>

---

## 📋 TL;DR

> An enterprise-scale **Order Management System** for GSK — orchestrating complex order workflows across procurement, fulfilment, and approval chains at a global pharmaceutical organization. Built on **Kafka event-driven microservices** with DDD, CQRS, Casbin RBAC, and ArgoCD GitOps.

| | |
|---|---|
| **Company** | Sweya AI |
| **Client** | GlaxoSmithKline (GSK) |
| **Role** | Senior Software Engineer → Technical Lead |
| **Period** | Apr 2023 – Jan 2025 |
| **Domain** | Pharmaceutical · Supply Chain · Enterprise Finance |
| **Architecture** | Event-driven Microservices · DDD · CQRS |

---

## 🎯 Core Capabilities

- **Kafka-powered order event pipeline** — decoupled, high-throughput state transitions across bounded contexts
- **Multi-team authorization** — Casbin RBAC scoped per team: procurement, approvers, fulfilment
- **Real-time order tracking** — SignalR WebSocket hub giving stakeholders live visibility into order progression
- **ArgoCD GitOps** — self-healing Kubernetes deployments with automated rollback on failures
- **Full audit trail** — every order action tracked with timestamp, user, and reason

---

## 👨‍💼 My Role

- Designed the **DDD layered architecture** — bounded contexts, aggregate roots, value objects, and domain events
- Implemented the **Kafka event-driven order pipeline** for decoupled, asynchronous state transitions
- Engineered **Casbin RBAC** with role-specific order action authorization across procurement, approval, and fulfilment teams
- Built the **Angular NgRx frontend** with real-time order tracking via SignalR
- Managed **Docker + Kubernetes + ArgoCD** containerized infrastructure and GitOps pipelines

---

## 🏗️ Architecture

```mermaid
graph LR
    subgraph Frontend["🖥️ Angular Frontend"]
        A["📋 Order Dashboard\nList, Filter, Search"]
        B["✅ Approval Workflow UI\nMulti-step Review"]
        C["🔄 NgRx State\nOrder Lifecycle"]
        D["📡 SignalR Client\nLive Updates"]
        A & B --> C --> D
    end

    subgraph API["⚙️ Order Service — .NET"]
        E["🌐 REST API\nVersioned + Swagger"]
        F["⚙️ CQRS Layer\nMediatR — Commands & Queries"]
        G["🏛️ Domain Layer\nOrders · LineItems · Policies\nApprovals · Bounded Contexts"]
        H["🗄️ Infrastructure\nEF Core + Unit of Work"]
        E --> F --> G --> H
    end

    subgraph Auth["🔐 Auth & Authorization"]
        I["🏛️ Zitadel OAuth2/OIDC"]
        J["⚖️ Casbin RBAC\nProcurement · Approval · Fulfilment"]
    end

    subgraph Messaging["📨 Event Streaming"]
        K["🟠 Kafka\nOrder State Events"]
        L["🐰 RabbitMQ\nNotification Events"]
    end

    subgraph Background["⚡ Background"]
        M["⏰ Hangfire\nExpiry Checks · Scheduling"]
        N["📡 SignalR Hub\nReal-time Status Push"]
    end

    subgraph Infra["🚀 Infrastructure"]
        Q["🐳 Docker + Kubernetes\nContainer Orchestration"]
        R["♾️ ArgoCD GitOps\nSelf-healing · Auto-rollback"]
        Q --> R
    end

    Frontend --> I --> E
    E --> J
    H --> O[("🗄️ PostgreSQL")] & P["📋 Audit Trail"]
    API --> K & L
    API --> M & N
    D --> N
```

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Frontend** | Angular, NgRx, RxJS, TypeScript |
| **Real-time** | SignalR — live order status streaming |
| **Auth** | Zitadel, OAuth2/OIDC, JWT, Casbin RBAC |
| **Backend** | .NET, ASP.NET Core Web API, MediatR (CQRS) |
| **Architecture** | DDD, Event-Driven, Microservices, Clean Architecture |
| **Event Streaming** | Apache Kafka — order state events |
| **Messaging** | RabbitMQ — notification events |
| **Database** | PostgreSQL, EF Core, Unit of Work, Audit Trail |
| **Background Jobs** | Hangfire — order expiry checks, scheduled reports |
| **Observability** | OpenTelemetry, Serilog |
| **DevOps** | Docker, Kubernetes, ArgoCD GitOps |

---

## 📊 Impact

| Metric | Result |
|--------|--------|
| **Scalability** | Kafka-powered decoupled processing — independently scalable per bounded context |
| **Authorization** | Casbin RBAC scoped precisely per team role |
| **Operational Efficiency** | SignalR eliminated manual status-check overhead |
| **Reliability** | ArgoCD GitOps with automated rollback on deployment failures |

---

## 🏷️ Skills Demonstrated

`.NET` `ASP.NET Core` `C#` `DDD` `CQRS` `MediatR` `Kafka` `RabbitMQ` `SignalR` `Casbin RBAC` `Zitadel` `OAuth2/OIDC` `JWT` `EF Core` `PostgreSQL` `Hangfire` `OpenTelemetry` `Serilog` `Angular` `NgRx` `Docker` `Kubernetes` `ArgoCD`

---

<div align="center">

[← Back to Profile](../GITHUB_PROFILE.md) · [📁 All Projects](../PROJECTS_INDEX.md) · [💼 LinkedIn](https://linkedin.com/in/sarkeranik) · [📧 Contact](mailto:ach6266@gmail.com)

</div>
