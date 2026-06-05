<div align="center">

# 🏧 IPDC Finance PLC — eKYC Platform

### AI-Powered Digital Customer Onboarding for Non-Bank Finance

[![Status](https://img.shields.io/badge/Status-In_Production-10B981?style=flat-square&logo=checkmarx&logoColor=white)](https://ipdc.com/)
[![Live](https://img.shields.io/badge/Live-ipdc.com-10B981?style=flat-square&logo=safari&logoColor=white)](https://ipdc.com/)
[![Company](https://img.shields.io/badge/LEADS_Corporation-6366F1?style=flat-square)]()
[![Client](https://img.shields.io/badge/Client-IPDC_Finance_PLC-F59E0B?style=flat-square)]()
[![Duration](https://img.shields.io/badge/Jan_2020–Oct_2021-F59E0B?style=flat-square)]()
[![Speed](https://img.shields.io/badge/Onboarding-Days_→_5_Minutes-10B981?style=flat-square)]()

[← Back to Profile](../GITHUB_PROFILE.md) · [← All Projects](../PROJECTS_INDEX.md)

</div>

---

## 📋 TL;DR

> A state-of-the-art digital onboarding solution for **IPDC Finance PLC** — one of Bangladesh's leading non-bank financial institutions. Built with Vue.js + .NET Core microservices, integrating **Google Vision AI** for OCR, NLP, biometric face matching, and liveness detection, with secure AWS S3 document storage.

| | |
|---|---|
| **Company** | LEADS Corporation Limited |
| **Client** | IPDC Finance PLC |
| **Role** | Associate Software Engineer |
| **Period** | Jan 2020 – Oct 2021 |
| **Domain** | Non-bank Financial Services · Digital Identity |
| **AI Stack** | Google Vision AI · OCR · NLP · Biometric Matching · Liveness Detection |

---

## 🎯 Key Features

| Feature | Description |
|---------|-------------|
| **Document OCR** | Automatically extracts customer information from NID documents via Google Vision API |
| **AI Image Matching** | Matches live camera capture against NID photo for identity confirmation |
| **NLP Extraction** | Extracts and validates structured data from unstructured document text |
| **Liveness Detection** | Prevents spoofing — verifies live capture is from a real person |
| **Dual Onboarding Mode** | Customer self-service or IPDC agent-assisted flow |
| **Real-time Status Updates** | Applicants and staff receive instant notifications throughout verification |
| **Secure Document Storage** | Captured identity documents stored securely on **AWS S3** |

---

## 🏗️ Architecture

```mermaid
graph TB
    subgraph Channels["📱 Onboarding Channels"]
        A["👤 Customer\nSelf-Service App"]
        B["🏦 IPDC Agent\nPortal"]
    end

    subgraph Frontend["🖥️ Frontend — Vue.js"]
        C["⚡ Vue.js SPA"]
        D["🔄 Vuex"]
        C --> D
    end

    subgraph Gateway["🔀 API Gateway"]
        E["🔀 Ocelot Gateway"]
    end

    subgraph Services["⚙️ Backend Services — .NET Core"]
        F["🎯 eKYC Orchestration"]
        G["🔍 Identity Verification"]
        H["📄 Document Extraction"]
        I["🔔 Notification Service"]
    end

    subgraph AI["🤖 AI & Vision Layer"]
        J["👁️ Google Vision API\nOCR"]
        K["😊 Face Matching Engine\nBiometric Verification"]
        L["🧠 NLP Processor\nData Extraction"]
        M["🎭 Liveness Detection\nAnti-spoofing"]
    end

    subgraph Messaging["📨 Messaging"]
        N["🐰 RabbitMQ\nAsync Verification Events"]
    end

    subgraph Data["🗄️ Data"]
        O[("🗄️ Oracle DB")]
        P["☁️ AWS S3\nDocument Storage"]
    end

    Channels --> C --> E
    E --> F --> G & H & I
    H --> J & L
    G --> K & M
    F --> N --> O
    H --> P
```

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Frontend** | Vue.js, Vuex, HTML5, CSS3 |
| **Backend** | .NET Core, ASP.NET Core Web API, EF Core, Dapper |
| **Auth** | JWT, OAuth2 |
| **AI / Vision** | Google Vision API, OCR, NLP, Face Matching, Liveness Detection |
| **API Gateway** | Ocelot — centralized routing and auth enforcement |
| **Messaging** | RabbitMQ — async event-driven verification processing |
| **Database** | Oracle DB |
| **Document Storage** | AWS S3 — secure encrypted storage |
| **Architecture** | Microservices, RESTful APIs |

---

## 📊 Impact

| Metric | Result |
|--------|--------|
| **Onboarding Speed** | Reduced from **several days** to **under 5 minutes** |
| **Manual Bottlenecks** | AI-driven verification eliminated manual document review |
| **Accessibility** | Dual-mode onboarding served tech-savvy and assisted customer segments |
| **Regulatory Compliance** | Aligned with Bangladesh Bank digital KYC requirements |

---

## 🏷️ Skills Demonstrated

`.NET Core` `ASP.NET Core` `Vue.js` `Vuex` `Google Vision API` `OCR` `NLP` `Face Matching` `Liveness Detection` `Ocelot` `RabbitMQ` `Oracle DB` `AWS S3` `JWT` `OAuth2` `Dapper` `Microservices` `eKYC`

---

<div align="center">

[← Back to Profile](../GITHUB_PROFILE.md) · [📁 All Projects](../PROJECTS_INDEX.md) · [💼 LinkedIn](https://linkedin.com/in/sarkeranik) · [📧 Contact](mailto:ach6266@gmail.com)

</div>
