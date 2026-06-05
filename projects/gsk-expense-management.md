<div align="center">

# 💊 GSK Expense Management System

### Enterprise Expense Workflow Platform for GlaxoSmithKline

[![Status](https://img.shields.io/badge/Status-In_Production-10B981?style=flat-square&logo=checkmarx&logoColor=white)](https://sweya.ai/products/regulatory-ai)
[![Live](https://img.shields.io/badge/Live-sweya.ai-10B981?style=flat-square&logo=safari&logoColor=white)](https://sweya.ai/products/regulatory-ai)
[![Company](https://img.shields.io/badge/Sweya_AI_(Client:_GSK)-8B5CF6?style=flat-square)]()
[![Role](https://img.shields.io/badge/Role-Sr._SE_→_Technical_Lead-EC4899?style=flat-square)]()
[![Duration](https://img.shields.io/badge/Apr_2023–Jan_2025-F59E0B?style=flat-square)]()
[![Impact](https://img.shields.io/badge/Impact-500K%2B_Transactions/Month-10B981?style=flat-square)]()

[← Back to Profile](../GITHUB_PROFILE.md) · [← All Projects](../PROJECTS_INDEX.md)

</div>

---

## 📋 TL;DR

> A secure, enterprise-grade **Expense Management System** for GlaxoSmithKline (GSK). Features DDD .NET backend with Casbin RBAC, real-time SignalR notifications, and full audit trails — handling **500K+ monthly transactions** with zero compliance gaps.

| | |
|---|---|
| **Company** | Sweya AI |
| **Client** | GlaxoSmithKline (GSK) — global pharma leader |
| **Role** | Senior Software Engineer → Technical Lead |
| **Period** | Apr 2023 – Jan 2025 |
| **Domain** | Healthcare · Enterprise Finance · Compliance |
| **Scale** | 500K+ monthly transactions |

---

## 🎯 What It Solves

- **Complex approval hierarchies** — multi-level expense claim workflows with role-specific actions
- **Audit compliance** — immutable audit trails for every action (regulatory requirement for pharma)
- **Real-time visibility** — instant SignalR notifications on claim status changes (no more email chains)
- **Fine-grained authorization** — Casbin RBAC policies per feature, not just per role
- **Multi-role orchestration** — Employee → Manager → Finance → Administrator workflows with branching logic

---

## 👨‍💼 My Role

- Architected the **DDD backend** from scratch — domain models, repositories, CQRS pipeline, and infrastructure layer
- Engineered a **Casbin-powered RBAC system** with `CasbinAuthorizeAttribute` for feature-level authorization
- Built **SignalR real-time notification infrastructure** for instant approval/status updates across the organization
- Contributed to the **Angular 17 frontend** — OAuth2 integration, HTTP interceptors, and Swagger-generated API clients
- Implemented enterprise **audit logging, domain events, and Unit of Work** patterns
- Integrated **OpenTelemetry + Serilog** for full production observability

---

## 🏗️ Architecture

```mermaid
graph TB
    subgraph Frontend["🖥️ Angular 17 Frontend"]
        A["📊 Expense Dashboard\nClaim Overview & Analytics"]
        B["📝 Claim Submission\nExpense Forms & Receipts"]
        C["✅ Approval Workflow\nMulti-step Review UI"]
        D["👥 User Management\nRoles & Group Assignment"]
        E["🔔 Real-time Notifications\nSignalR + WebSocket"]
        A & B & C & D --> E
    end

    subgraph Auth["🔐 Auth & Authorization"]
        F["🏛️ Zitadel OAuth2/OIDC\nToken Management"]
        G["🔑 JWT Validation\n+ RBAC"]
        F --> G
        L["⚖️ Casbin RBAC Engine\nPolicy-based Authorization"]
        M["🎯 CasbinAuthorizeAttribute\nFeature-level Access Control"]
        L --> M
    end

    subgraph API["⚙️ Backend — DDD Architecture"]
        H["🌐 API Layer\nVersioned REST + Swagger"]
        I["⚙️ Application Layer\nCQRS + MediatR\nCommands & Queries"]
        J["🏛️ Domain Layer\nUsers · Claims · Expenses\nPolicies · Domain Events"]
        K["🗄️ Infrastructure Layer\nEF Core + Unit of Work\nGeneric Repositories"]
        H --> I --> J --> K
    end

    subgraph Background["⚡ Background & Messaging"]
        N["⏰ Hangfire Jobs\nAsync Claim Processing"]
        O["📣 Domain Events\nDecoupled Business Logic"]
        P["📡 SignalR Hub\nReal-time Push"]
    end

    subgraph Data["🗄️ Data Layer"]
        Q[("PostgreSQL\nTransactional Data")]
        R["📋 Audit Trail Log\nImmutable · Indexed"]
    end

    subgraph Observability["🔍 Observability"]
        S["📊 OpenTelemetry\nDistributed Tracing"]
        T["📝 Serilog\nStructured Logging"]
    end

    Frontend --> F
    Frontend --> P
    Frontend --> H
    H --> L
    H --> N & O & P
    K --> Q & R
    API --> S & T
```

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Frontend** | Angular 17, TypeScript, PrimeNG, RxJS |
| **Real-time** | SignalR, WebSockets |
| **Auth** | Zitadel, OAuth2/OIDC, JWT |
| **Authorization** | Casbin RBAC Engine, `CasbinAuthorizeAttribute` |
| **Backend** | .NET, ASP.NET Core Web API, MediatR (CQRS) |
| **Architecture** | Domain-Driven Design, Clean Architecture, Domain Events |
| **ORM & Data** | Entity Framework Core, Unit of Work, Generic Repositories, Soft-delete |
| **Database** | PostgreSQL |
| **Background Jobs** | Hangfire — async claim processing, notifications, reporting |
| **Observability** | OpenTelemetry, Serilog |
| **API Tooling** | Swagger/OpenAPI, API Versioning, Custom Exception Middleware |

---

## 📊 Impact

| Metric | Result |
|--------|--------|
| **Monthly Volume** | **500K+** expense transactions processed securely |
| **Auditability** | Fully auditable platform — immutable audit trails for every action |
| **Authorization Flexibility** | Casbin RBAC — permission changes without code deployments |
| **Real-time** | SignalR notifications eliminated approval email chains |
| **Client** | Global pharmaceutical enterprise (GSK) — production-grade compliance |

---

## 🏷️ Skills Demonstrated

`.NET` `ASP.NET Core` `C#` `DDD` `CQRS` `MediatR` `Casbin RBAC` `EF Core` `PostgreSQL` `Hangfire` `SignalR` `Zitadel` `OAuth2/OIDC` `JWT` `OpenTelemetry` `Serilog` `Swagger/OpenAPI` `REST API` `Angular 17` `PrimeNG` `RxJS`

---

<div align="center">

[← Back to Profile](../GITHUB_PROFILE.md) · [📁 All Projects](../PROJECTS_INDEX.md) · [💼 LinkedIn](https://linkedin.com/in/sarkeranik) · [📧 Contact](mailto:ach6266@gmail.com)

</div>
