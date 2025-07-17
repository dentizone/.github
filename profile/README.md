<p align="center">
  <img src="https://dentizone.store/assets/logo/logoWithoutBackground.png" alt="Dentizone Logo" width="400">
</p>

<h1 align="center">Welcome to the Dentizone Organization!</h1>

<p align="center">
  The official GitHub organization for <strong>Dentizone</strong>, a modern, secure, and full-featured e-commerce ecosystem designed specifically for dental students in Egypt.
  <br />
  <a href="https://dentizone.store/"><strong>Explore the Live Demo »</strong></a>
</p>

## ✨ What is Dentizone?

Dentizone is a comprehensive platform built to address the unique needs of the dental student community. Our mission is to provide a trusted, secure, and user-friendly marketplace where students can buy and sell new or used dental supplies and equipment. The entire ecosystem is built on a foundation of trust, with features like mandatory KYC (Know Your Customer) verification to ensure a safe environment for all users.

The Dentizone platform is composed of several interconnected projects, each housed in its own repository. Together, they form a robust, scalable, and feature-rich application suite.

---

## 🏛️ Our Repositories

Our platform is built on a microservices-oriented architecture, with each repository representing a key component of the ecosystem.

### Frontend Applications

| Repository                                                     | Description                                                                                                                                                                                                 | Tech Stack                                     |
| -------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| 🛍️ [**dentizone/user-frontend**](https://github.com/dentizone/user-frontend) | The official user-facing storefront. This is where students browse listings, manage their profiles, make purchases, and list items for sale. It's a feature-rich SPA designed for a seamless user experience. | `Angular`, `TypeScript`, `Tailwind CSS`, `PrimeNG`   |
| ⚙️ [**dentizone/admin**](https://github.com/dentizone/admin)         | The central control panel for platform administrators. This powerful dashboard is used for analytics, user management, post moderation, catalog control, and financial oversight (e.g., withdrawal approvals). | `Angular`, `TypeScript`, `Tailwind CSS`, `Chart.js` |

### Backend Services

| Repository                                             | Description                                                                                                                                                                                                                                      | Tech Stack                                                              |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| 🚀 [**dentizone/api**](https://github.com/dentizone/api) | The core backend API built on .NET and Clean Architecture principles. It handles all business logic, including authentication, user management, order processing, and financials. It serves as the backbone for all frontend applications. | `.NET 9`, `ASP.NET Core`, `EF Core`, `SQL Server`, `Redis`, `Hangfire` |
| 🤖 [**dentizone/ai**](https://github.com/dentizone/ai)   | A specialized microservice for AI-powered content moderation. It provides endpoints for sentiment analysis, toxicity detection, and PII (contact information) extraction to ensure platform safety and user privacy.             | `Python`, `FastAPI`, `Hugging Face`, `Google Gemini`                      |

---

## 🛠️ Technology at a Glance

The Dentizone platform leverages a modern and diverse technology stack to deliver a robust and scalable solution:

-   **Frontend:** `Angular`, `TypeScript`, `RxJS`, `Tailwind CSS`
-   **Backend:** `.NET 9`, `ASP.NET Core`, `C#`, `Clean Architecture`, `Entity Framework Core`
-   **AI & Machine Learning:** `Python`, `FastAPI`, `Hugging Face Transformers`, `Google Gemini API`
-   **Database & Caching:** `SQL Server`, `Redis`
-   **Infrastructure & DevOps:** `Docker`, `Docker Compose`, `GitHub Actions` for CI/CD, `Hangfire` for background jobs.
-   **Security:** `JWT Authentication`, `Role-Based Access Control`, `Infisical` for secret management, and external KYC integration.

---

## 🚀 Getting Started

Each repository contains a detailed `README.md` with specific instructions for setup, installation, and local development. To get the entire ecosystem running, you will generally need:

1.  A running instance of the **Backend API** ([dentizone/api](https://github.com/dentizone/api)).
2.  A running instance of the **AI Service** ([dentizone/ai](https://github.com/dentizone/ai)).
3.  The **User Frontend** ([dentizone/user-frontend](https://github.com/dentizone/user-frontend)) configured to point to the API.
4.  The **Admin Dashboard** ([dentizone/admin](https://github.com/dentizone/admin)) configured to point to the API.

Docker is used across the projects to simplify setup and ensure consistency between development and production environments.

## 👥 Our Team

Dentizone was conceived, designed, and developed by a dedicated team of passionate engineers.

*   **Yara Nagy**
*   **Nouran Ahmed**
*   **Nouran Yasser**
*   **Mariam Alaa**
*   **Nourhane Amir**

We welcome you to explore our projects, dive into the code, and see how it all works together
