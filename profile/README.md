# Nutri Guardian -  Menu and Food Suggestion Application for People with Food Allergies
<div align="center">
    <img src="./readme/images/logo.png" alt="Nutri Guardian" height='80px'/>
    <p>Nutri Guardian is a mobile application that provides menu and food suggestion application for people with food allergies.</p>
</div>
<div align='center'>
<img src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=fff"> 
<img src="https://custom-icon-badges.demolab.com/badge/Microsoft%20SQL%20Server-CC2927?logo=mssqlserver-white&logoColor=white"> 
<img src="https://img.shields.io/badge/Redis-%23DD0031.svg?logo=redis&logoColor=white"> 
<img src="https://img.shields.io/badge/Docker-Yes-green"> 
<img src="https://img.shields.io/badge/Server-Yes-green"> 
<img src="https://img.shields.io/badge/API-Yes-green">
<br>
</div>

## Table of Contents
<ol start="0"> 
    <li><a href="#intro">Introduction</a></li>
    <li><a href="#tech">Tech Stacks</a></li>
    <li><a href="#uc-diagram">Use Case Diagram</a></li>
    <li><a href="#uc-diagram">Architecture Diagram</a></li>
    <li><a href="#db-design">Database Design</a></li>
    <li><a href="#screen-flow"> Screen Flow</a></li>
    <li><a href="#team-members">Team Members</a></li>
</ol>


<a id="intro"></a>
## 0. Introduction
Nutri Guardian Project was conceived to provide everyone, especially those who have difficulty choosing food due to allergies, a convenient application to help and suggest daily and weekly menus. Realizing that the technology era has developed as it is now, Nutri Guardian will bring a better experience by providing information as well as a platform to help users easily control their daily diet, to minimize risks as well as unwanted symptoms of food allergies anytime, anywhere. Minimize the disadvantages of having to receive direct advice from medical professionals and doctors.


## Core Features

- **Food Scanning and Recognition**: Users can take a picture of their food (or scan barcode) to check for any allergens.
- **Food Discovery & Recommendations**: Personalized Food Search Engine and AI-Powered Alternative Recommendations.
- **Meal Planning & Management**: Family Meal Planning System and Recipe Management with Allergen Analysis.
- **Family & Caregiver Features**: Family Management Dashboard and Caregiver Communication System.
- **Allergy Health Resources**: A curated library of materials, articles, and exercises for users about allergys.
- **AI Chatbot**: Users can chat with an AI chatbot to find out more about allergy.
- **Restaurant & Dining Out**: Allergy-Friendly Restaurant Finder and Restaurant Menu Scanner.

## Target Users

- **Primary Users**:
  - Caregiver
  - User with allergy
- **Secondary Users**:
  - Food reviewer
    
<a id="tech"></a>
## 1. Tech Stacks

## Client & Server Technologies  

| Client | Description | Server | Description |
|--------|------------|--------|------------|
| ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) | Strongly typed JavaScript | ![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?logo=dotnet&logoColor=white) | Backend framework for building APIs |
| ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) | React framework with server-side rendering | ![Entity Framework](https://img.shields.io/badge/Entity%20Framework-512BD4?logo=dotnet&logoColor=white) | ORM for database interactions |
| ![React Native](https://img.shields.io/badge/React%20Native-61DAFB?logo=react&logoColor=white) | Mobile app development | ![ASP.NET Identity](https://img.shields.io/badge/ASP.NET%20Identity-512BD4?logo=dotnet&logoColor=white) | Authentication and authorization |
| ![Hero UI](https://img.shields.io/badge/Hero%20UI-38B2AC?logo=heroicons&logoColor=white) | UI component library | ![Serilog](https://img.shields.io/badge/Serilog-4B8BBE?logo=serilog&logoColor=white) | Structured logging framework |
| ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=white) | Utility-first CSS framework | ![Quartz.NET](https://img.shields.io/badge/Quartz.NET-004080?logo=clockify&logoColor=white) | Job scheduling library |
| ![Axios](https://img.shields.io/badge/Axios-5A29E4?logo=axios&logoColor=white) | HTTP client for API requests | ![JWT](https://img.shields.io/badge/JWT%20Auth-000000?logo=jsonwebtokens&logoColor=white) | Token-based authentication |
| | | ![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white) | API testing tool |
| | | ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?logo=swagger&logoColor=white) | API documentation generator |
| | | ![SignalR](https://img.shields.io/badge/SignalR-0088CC?logo=microsoft&logoColor=white) | Real-time communication |
| | | ![Mediator](https://img.shields.io/badge/Mediator-0078D4?logo=microsoft&logoColor=white) | Decouples communication between components |
| | | ![CQRS](https://img.shields.io/badge/CQRS-0078D4?logo=microsoft&logoColor=white) | Separates read/write operations |
| | | ![Excel API](https://img.shields.io/badge/Excel%20API-217346?logo=microsoft-excel&logoColor=white) | Microsoft Excel data processing |
| | | ![Gmail API](https://img.shields.io/badge/Gmail%20API-D14836?logo=gmail&logoColor=white) | Email automation and integration |

---

## Database & API Deployment  

The **Database** stack includes data storage solutions, while **API Deployment** contains tools for containerization, automation, and cloud services.  

| Database | Description | API Deployment | Description |
|----------|------------|---------------|------------|
| ![SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=white) | Cloud-based relational database | ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) | Containerization platform |
| ![Redis](https://img.shields.io/badge/Redis-DD0031?logo=redis&logoColor=white) | In-memory caching database | ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white) | CI/CD automation |
| | | ![Azure](https://img.shields.io/badge/Azure%20Cloud-0078D4?logo=microsoftazure&logoColor=white) | Backend deployment |
| | | ![ngrok](https://img.shields.io/badge/ngrok-1F1F1F?logo=ngrok&logoColor=white) | Local development tunneling |

---

## Others  

Additional services and third-party APIs that enhance functionality, such as AI, payments, video streaming, and file storage.  

| Service | Description |
|---------|------------|
| ![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?logo=google&logoColor=white) | AI-powered chatbot service |
| ![PayOs](https://img.shields.io/badge/Stripe-008CDD?logo=stripe&logoColor=white) | Online payment processing |
| ![OpenFoodFact API](https://img.shields.io/badge/WebRTC-333333?logo=webrtc&logoColor=white) | Food infomation and meal planner |
| ![Azure Storage](https://custom-icon-badges.demolab.com/badge/Microsoft%20Azure-0089D6?logo=msazure&logoColor=white) | Image and video storage |


<a id="uc-diagram"></a>
## 2. Use Case Diagram
<img src="./readme/images/NutriGuard-UsecaseDiagram.png" alt="NutriGuard-UsecaseDiagram" />

<a id="db-design"></a>
## 3. Database Design
<img src="./readme/images/NutriGuard-ERD.PNG" alt="NutriGuard-ERD" />

<a id="architecture"></a>
## 4. Architecture Diagram
<img src="./readme/images/NutriGuard-ArchitectureDiagram.png" alt="NutriGuard-ArchitectureDiagram" />

<a id="screen-flow"></a>
## 5. Screen Flow

<a id="team-members"></a>
## 6. Team members
- [Nguyen Cao Tri](https://github.com/canxi4589): Back-End Developer, Probationary Front-End
- [Nguyen Tran Hong Phuc](https://github.com/PhucHong-6113): Back-End Developer
- [Huynh Minh Long](https://github.com/Dematto04): Web Front-End, Mobile Developer

<a id="app-a"></a>

# Appendix A
