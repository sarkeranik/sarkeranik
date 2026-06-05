<div align="center">

# 🏦 Southeast Bank PLC — eKYC Platform

### AI-Powered Digital KYC with Biometric Face Matching

[![Status](https://img.shields.io/badge/Status-In_Production-10B981?style=flat-square&logo=checkmarx&logoColor=white)](https://www.southeastbank.com.bd/?page=seb_mobile_app)
[![Live](https://img.shields.io/badge/Live-southeastbank.com.bd-10B981?style=flat-square&logo=safari&logoColor=white)](https://www.southeastbank.com.bd/?page=seb_mobile_app)
[![Company](https://img.shields.io/badge/LEADS_Corporation-6366F1?style=flat-square)]()
[![Client](https://img.shields.io/badge/Client-Southeast_Bank_PLC-F59E0B?style=flat-square)]()
[![Duration](https://img.shields.io/badge/Jan_2020–Oct_2021-F59E0B?style=flat-square)]()
[![Compliance](https://img.shields.io/badge/Bangladesh_Bank_Compliant-10B981?style=flat-square)]()

[← Back to Profile](../GITHUB_PROFILE.md) · [← All Projects](../PROJECTS_INDEX.md)

</div>

---

## 📋 TL;DR

> A digital onboarding solution that allows Southeast Bank PLC to onboard new customers **faster, safer, and more cost-effectively**. Built with Vue.js + .NET Core microservices, leveraging AI, OCR, NLP, and biometric verification — fully compliant with Bangladesh Bank's digital KYC guidelines.

| | |
|---|---|
| **Company** | LEADS Corporation Limited |
| **Client** | Southeast Bank PLC |
| **Role** | Associate Software Engineer |
| **Period** | Jan 2020 – Oct 2021 |
| **Domain** | Commercial Banking · Digital Identity |
| **Compliance** | Bangladesh Bank Digital KYC Guidelines |

---

## 🎯 Key Features

- **NID-based Identity Verification** — OCR reads and validates data from national identity documents automatically
- **Biometric Facial Matching** — Live photo matched against NID photo using AI-powered image comparison
- **NLP Data Extraction** — Extracts and structures relevant data points from identity documents
- **Liveness Detection** — Guards against fraudulent spoofing attempts during biometric capture
- **Self-Service & Agent-Assisted Modes** — Flexible onboarding paths for all customer segments
- **Regulatory Compliance** — Designed and validated against Bangladesh Bank's digital KYC guidelines

---

## 🏗️ Architecture

```mermaid
graph TB
    subgraph Channels["📱 Onboarding Channels"]
        A["👤 Customer App\nSelf-Service"]
        B["🏦 Bank Officer\nAgent Portal"]
    end

    subgraph Frontend["🖥️ Frontend — Vue.js"]
        C["⚡ Vue.js SPA"]
        D["🔄 Vuex State Management"]
        C --> D
    end

    subgraph Gateway["🔀 API Gateway"]
        E["🔀 Ocelot Gateway\nRouting + Auth Enforcement"]
    end

    subgraph Services["⚙️ Backend — .NET Core Microservices"]
        F["🎯 eKYC Orchestration Service"]
        G["📄 Document Processing Service\nOCR + NLP"]
        H["🔍 Identity Verification Service\nBiometric Matching"]
        I["📋 Account Onboarding Service\nAccount Creation"]
    end

    subgraph AI["🤖 AI & Vision Layer"]
        J["👁️ Google Vision API\nOCR Extraction"]
        K["😊 Face Match Engine\nBiometric Comparison"]
        L["🧠 NLP Parser\nData Structuring"]
        M["🎭 Liveness Check\nAnti-spoofing"]
    end

    subgraph Messaging["📨 Messaging"]
        N["🐰 RabbitMQ\nAsync Events"]
    end

    Channels --> C --> E
    E --> F --> G & H & I
    G --> J & L
    H --> K & M
    F --> N --> O[("🗄️ Oracle DB")]
```

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Frontend** | Vue.js, Vuex, HTML5, CSS3 |
| **Backend** | .NET Core, ASP.NET Core Web API, EF Core, Dapper |
| **Auth** | JWT, OAuth2 |
| **AI / Vision** | Google Vision API, OCR, NLP, Biometric Matching, Liveness Detection |
| **API Gateway** | Ocelot |
| **Messaging** | RabbitMQ |
| **Database** | Oracle DB |
| **Architecture** | Microservices, RESTful APIs |

---

## 📊 Impact

| Metric | Result |
|--------|--------|
| **Onboarding Speed** | Multi-day in-branch process → **minutes digitally** |
| **Accessibility** | Dual-mode support (self-service + agent) served all customer segments |
| **Compliance** | Validated against Bangladesh Bank digital KYC regulations |
| **Manual Workload** | AI verification pipeline reduced compliance team review load |

---

## 🏷️ Skills Demonstrated

`.NET Core` `ASP.NET Core` `Vue.js` `Vuex` `Google Vision API` `OCR` `NLP` `Biometric Matching` `Liveness Detection` `Ocelot` `RabbitMQ` `Oracle DB` `JWT` `Dapper` `Microservices` `eKYC`

---

<div align="center">

[← Back to Profile](../GITHUB_PROFILE.md) · [📁 All Projects](../PROJECTS_INDEX.md) · [💼 LinkedIn](https://linkedin.com/in/sarkeranik) · [📧 Contact](mailto:ach6266@gmail.com)

</div>
