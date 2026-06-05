<div align="center">

# 👟 Apex Footwear & Lifestyle E-Commerce

### High-Traffic Retail Platform · 100K+ Weekly Visitors

[![Status](https://img.shields.io/badge/Status-In_Production-10B981?style=flat-square&logo=checkmarx&logoColor=white)](https://www.apex4u.com/)
[![Live](https://img.shields.io/badge/Live-apex4u.com-10B981?style=flat-square&logo=safari&logoColor=white)](https://www.apex4u.com/)
[![Company](https://img.shields.io/badge/Brain_Station_23-6366F1?style=flat-square)]()
[![Client](https://img.shields.io/badge/Client-Apex_Footwear_Limited-F59E0B?style=flat-square)]()
[![Duration](https://img.shields.io/badge/Nov_2021–Jul_2022-F59E0B?style=flat-square)]()
[![Traffic](https://img.shields.io/badge/Traffic-100K%2B_Weekly_Visitors-10B981?style=flat-square)]()
[![Certified](https://img.shields.io/badge/nopCommerce_Certified-98%25-F59E0B?style=flat-square)]()

[← Back to Profile](../GITHUB_PROFILE.md) · [← All Projects](../PROJECTS_INDEX.md)

</div>

---

## 📋 TL;DR

> Full-featured e-commerce platform for **Apex Footwear Limited** — one of Bangladesh's leading footwear and lifestyle brands — serving **100,000+ weekly visitors** reliably. Built on nopCommerce + .NET Core + Angular, with AWS Auto Scaling, Redis caching, Facebook Shop and Knawat API integrations. Contributed custom plugins back to the nopCommerce open-source project.

| | |
|---|---|
| **Company** | Brain Station 23 |
| **Client** | Apex Footwear Limited |
| **Role** | Associate Software Engineer |
| **Period** | Nov 2021 – Jul 2022 |
| **Domain** | Fashion & Footwear E-Commerce |
| **Traffic** | 100,000+ weekly visitors |
| **Concurrency** | 10,000+ concurrent users at peak |

---

## 🎯 Key Contributions

- Built and deployed custom **nopCommerce Plugins** and **Themes** tailored to Apex's brand identity, serving **100,000+ weekly visitors**
- Engineered robust **RESTful APIs** with **.NET Core** supporting up to **10,000 concurrent visitors**
- Integrated **Facebook Shop APIs** — opened social commerce as a new digital sales channel
- Integrated **Knawat Dropshipping APIs** — expanded product catalogue without inventory overhead
- Implemented **Redis caching** for session management and frequently accessed product data
- Leveraged **AWS Auto Scaling** (EC2, RDS, S3) to handle traffic spikes during sales events
- Deployed via **Azure DevOps CI/CD** with GitLab-based branching workflows
- Contributed custom Plugins back to the **nopCommerce open-source framework** — adopted across multiple client storefronts
- Achieved **98% score** on the nopCommerce Certified Developer exam (Feb 2022)

---

## 🏗️ Architecture

```mermaid
graph TB
    subgraph Customer["📱 Customer Channels"]
        A["🌐 Web Browser"]
        B["📘 Facebook Shop"]
    end

    subgraph Frontend["🖥️ Frontend Layer"]
        C["⚡ Angular SPA\nProduct Listings · Cart · Checkout"]
        D["📄 Razor Views\nnopCommerce Engine"]
        E["🎨 Custom Theme & Plugins\nApex Brand Identity"]
        C & D --> E
    end

    subgraph Backend["⚙️ Backend — .NET Core + nopCommerce"]
        F["🏪 nopCommerce Core\nProduct · Cart · Order · Inventory"]
        G["🔌 Custom Plugins\nBusiness Logic & Integrations"]
        H["🌐 RESTful API Layer\n10K+ Concurrent Users"]
        F --> G --> H
    end

    subgraph Integrations["🔗 Third-Party Integrations"]
        I["🛒 Knawat Dropshipping API\nProduct Catalogue Expansion"]
        J["📘 Facebook Shop API\nSocial Commerce"]
        K["💳 Payment Gateway\nSecure Checkout"]
    end

    subgraph Data["🗄️ Data Layer"]
        L[("🗄️ SQL Server\nProduct & Order Data")]
        M["⚡ Redis Cache\nSessions & Product Listings\n(Reduced DB Load Significantly)"]
    end

    subgraph Infra["☁️ AWS Infrastructure"]
        N["🖥️ AWS EC2\nAuto Scaling Groups\n(Handles Traffic Spikes)"]
        O["🗄️ AWS RDS\nManaged SQL Server"]
        P["📦 AWS S3\nProduct Images & Media"]
        Q["🔄 Azure DevOps\nCI/CD Pipelines + GitLab"]
        Q --> N --> O & P
    end

    Customer --> Frontend --> Backend
    Backend --> Integrations
    Backend --> L & M
    Backend --> N
```

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **E-Commerce Platform** | nopCommerce |
| **Backend** | .NET Core, C#, ASP.NET Core, Entity Framework |
| **Frontend** | Angular, TypeScript, HTML5, CSS3, Razor Views |
| **Database** | Microsoft SQL Server |
| **Caching** | Redis — sessions + product listings |
| **Third-Party** | Knawat Dropshipping API, Facebook Shop API |
| **Cloud** | AWS (EC2, RDS, S3), Auto Scaling |
| **DevOps** | Azure DevOps, GitLab CI/CD |

---

## 📊 Impact

| Metric | Result |
|--------|--------|
| **Weekly Traffic** | **100,000+ visitors** served reliably |
| **Concurrency** | APIs supporting up to **10,000 concurrent users** |
| **Sales Channels** | Facebook Shop integration expanded digital reach |
| **Certification** | **98% score** — nopCommerce Certified Developer (Feb 2022) |
| **Open Source** | Custom plugins contributed back to nopCommerce framework |

---

## 🏷️ Skills Demonstrated

`nopCommerce` `.NET Core` `ASP.NET Core` `C#` `Angular` `TypeScript` `SQL Server` `Entity Framework` `Redis` `Knawat API` `Facebook Shop API` `AWS EC2` `AWS RDS` `AWS S3` `Auto Scaling` `Azure DevOps` `GitLab CI/CD` `REST API`

---

<div align="center">

[← Back to Profile](../GITHUB_PROFILE.md) · [📁 All Projects](../PROJECTS_INDEX.md) · [💼 LinkedIn](https://linkedin.com/in/sarkeranik) · [📧 Contact](mailto:ach6266@gmail.com)

</div>
