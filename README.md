# Sean Rowe
**Senior Full Stack Developer / Software Architect**

Email: sean@seanrowe.com  
Phone: (501) 316-6521  
LinkedIn: https://linkedin.com/in/hireseanrowe  
GitHub: https://github.com/sean-rowe

---

## Professional Summary

Senior Full Stack Architect with over 25 years of hands-on experience designing and delivering enterprise-scale applications across regulated industries. Deep expertise in React, TypeScript, GraphQL, and Node.js with PostgreSQL persistence. Proven track record building cloud-native solutions on Azure and AWS, architecting secure authentication flows (OIDC, OAuth 2.0, JWT), and leading complex modernization initiatives in healthcare, insurance, and logistics domains. Strong background in API architecture including both RESTful and GraphQL patterns, with extensive testing discipline using Jasmine, Karma, and Cypress.

---

## Core Technical Skills

**Frontend:** React, Next.js, Angular, TypeScript, RxJS, Redux, Angular Material, SASS/CSS3, D3.js, Chart.js, Storybook

**Backend / API Development:** Node.js, Express.js, GraphQL, Apollo Server, Apollo Client, NestJS, TypeScript, Prisma, Java, Spring Boot, C#, .NET Core, Python, FastAPI, PHP, Laravel

**Databases:** PostgreSQL, SQL Server, MongoDB, MySQL, Redis

**Cloud & DevOps:** Azure, App Service, Functions, SQL Database, Blob Storage, AWS, API Management, ECS, Lambda, RDS, S3, Docker, Kubernetes, Terraform, CI/CD

**Identity & Security:** OIDC, OAuth 2.0, JWT, SAML2, Okta, AWS Cognito, Azure AD

**Testing:** Jasmine, Karma, Jest, Cypress, Supertest, Mocha, Selenium, BDD, Gherkin, Cucumber

**Analytics / Platforms:** MicroStrategy, EDP

**Leadership & Delivery:** Architecture Design, Agile, Code Reviews, Mentoring, Production Support

## Professional Experience

### Southwest Power Pool — Solutions Architect
**Feb 2025 – Jun 2025**

- Designed the integration architecture for MicroStrategy embedded analytics within engineering simulation workflows, defining component boundaries, data flow patterns, and drill-down navigation strategies.
- Architected React-based dashboard interfaces for simulation monitoring, establishing component composition patterns, Redux state management, and TypeScript conventions for type-safe development.
- Designed GraphQL API layer using Node.js and Apollo Server to unify disparate simulation data sources, defining schema design patterns, resolver architecture, and query optimization strategies including DataLoader for N+1 prevention.
- Built reference implementation of the Node.js/Apollo Server GraphQL gateway to validate architecture decisions before handoff to development teams; included DataLoader patterns and subscription infrastructure for real-time updates.
- Architected the data publishing pipeline from simulation engines to the Enterprise Data Platform (EDP), establishing API contract standards, batching strategies, pagination schemes, and payload optimization guidelines.
- Defined the data persistence architecture using PostgreSQL for reporting datasets and introduced Redis caching patterns for high-frequency endpoints to reduce backend load and improve response times.
- Established authentication and authorization architecture using OIDC (OAuth 2.0) with JWT validation, defining token lifecycle management, claims/roles enforcement, and credential rotation strategies to eliminate hardcoded secrets.
- Built Docker images and Kubernetes deployment manifests for reference services; established baseline configurations for ingress, config maps, secrets management, health probes, and horizontal pod autoscaling used as templates across development teams.
- Architected CI/CD pipeline standards incorporating Jasmine/Karma unit testing gates, container build workflows, and promotion strategies across Azure environments.
- Designed Python-based automation services and FastAPI endpoint patterns for simulation pipeline orchestration, establishing conventions for job management and status reporting to downstream consumers.
- Provided architectural guidance for React UI modernization efforts, ensuring integration compatibility with GraphQL and REST backend services and alignment with platform standards.
- Led architectural reviews, established coding standards, conducted design sessions with development teams, and mentored engineers within Agile/Scrum delivery.

---

### Aflac — Senior Developer
**Nov 2023 – May 2024**

- Developed and maintained enterprise Angular applications using TypeScript, RxJS, Angular Material, and SASS/CSS3 for consistent UI patterns.
- Implemented RESTful integrations between Angular UI and Spring Boot APIs supporting authentication and business workflows; standardized validation and error handling.
- Developed Node.js/Express.js BFF (Backend-for-Frontend) service to aggregate and reshape Spring Boot API responses for Angular consumption, avoiding pollution of domain APIs with frontend-specific endpoints.
- Integrated Okta-based SSO using OIDC (OAuth 2.0) and SAML2; enforced JWT-based API authorization/validation across frontend-to-backend flows.
- Supported production issues involving backend API failures and identity-related defects; improved diagnostics and remediation playbooks.
- Built and optimized PostgreSQL and SQL Server-backed workflows (search/pagination/filtering) and introduced Redis caching for high-read data where appropriate.
- Implemented comprehensive test automation using Jasmine unit tests, Karma test runner, and Cypress E2E; aligned critical workflows to BDD-style scenarios (Gherkin/Cucumber).
- Built and maintained CI/CD in Azure DevOps Services, including automated Jasmine/Karma test gates and environment promotions.
- Participated in architectural discussions around service scalability and secure backend communication; mentored junior developers.

---

### J.B. Hunt Transport Services, Inc. — Software Engineer III
**Jan 2019 – Nov 2023**

- Embedded MicroStrategy analytics into Angular and React pricing applications using backend Java Spring Boot APIs, including parameterized drill-downs and authorization alignment.
- Architected GraphQL API gateway using Node.js and Apollo Server to aggregate pricing, rating, and customer data from multiple microservices, reducing frontend round-trips and improving developer experience.
- Designed GraphQL schema patterns for complex pricing domain models, implementing custom scalars, union types, and interface inheritance for type-safe query resolution.
- Integrated Enterprise Data Platform (EDP) services through Java-based microservices to source governed datasets and expose both REST and GraphQL APIs for downstream consumers.
- Built reusable React component libraries for pricing dashboards using TypeScript and Redux, implementing custom hooks for GraphQL subscription handling and real-time rate updates.
- Implemented D3.js and Chart.js visualizations for pricing distribution analysis and shipment volume trends within React dashboards.
- Built reusable backend service components supporting pricing, reporting, and authorization logic; implemented PostgreSQL and SQL Server persistence and Redis caching for high-traffic endpoints.
- Built Docker images and Kubernetes deployments for Node.js GraphQL services with ingress configuration, config maps, and secrets management.
- Implemented OIDC (OAuth 2.0) authentication and federated identity flows across UI and backend services; administered Okta and supported SAML-based integrations with Azure AD.
- Implemented JWT validation patterns across services and integrated enterprise identity requirements (including Microsoft Entra ID / Azure AD federation where required).
- Implemented Cypress testing focused on frontend-to-backend authentication flows; expanded coverage with Jasmine/Karma unit tests and BDD scenarios (Gherkin/Cucumber).
- Developed Python and Java automation scripts for CI/CD and workflow orchestration; delivered builds/releases through Azure DevOps Services pipelines.
- Participated in on-call rotations supporting production Java services and frontend applications; addressed security vulnerabilities related to authentication, authorization, and session handling.
- Contributed to code reviews, mentoring, and architectural design initiatives across multi-team delivery.

---

### Sean Rowe Consulting, LLC — Owner
**Jan 2018 – Jan 2019**

**Humana**
- Built a React-based component design system using TypeScript and Redux, shipping reusable UI components with Storybook documentation across multiple applications.
- **Implemented GraphQL BFF (Backend-for-Frontend) layer using Node.js and Apollo Server to aggregate healthcare data APIs, defining schema stitching patterns and federated graph architecture.**
- Expanded automated test coverage with Jest, Jasmine, and Cypress; added BDD acceptance coverage using Cucumber/Gherkin for critical UI behaviors.
- Integrated secure authentication flows using OIDC (OAuth 2.0) and JWT-based authorization for GraphQL and REST backend service calls.

**ArcBest**
- Modernized backend services to NestJS with TypeScript during platform migration; implemented Prisma ORM for PostgreSQL data access with type-safe query builders.
- Architected GraphQL API using NestJS GraphQL module with code-first schema generation, implementing resolver patterns, guards, and interceptors for cross-cutting concerns.
- Deployed services to Azure using App Service and Azure SQL Database; implemented OAuth 2.0/OIDC patterns with JWT validation across service boundaries.
- Containerized services with Docker and delivered changes via Azure DevOps CI/CD pipelines with automated Jasmine/Karma test gates.

**GRANITE — MuleSoft / Guardian / GUCAAS**
- Developed NestJS microservices with Prisma ORM connecting to PostgreSQL; implemented both REST and GraphQL API integrations with secure OAuth 2.0/JWT authentication.
- Designed GraphQL subscription architecture for real-time policy status updates using WebSocket transport and Redis pub/sub for horizontal scaling.
- Built regression automation using Cypress and BDD suites (Cucumber/Gherkin), running in CI/CD for release confidence.
- Standardized API contracts and error handling patterns across Java/Spring Boot, C#/.NET Core, and Node.js services.

**DSE**
- Led delivery of React frontend with Next.js SSR/SSG and NestJS backend services supporting secure form-driven workflows.
- Implemented GraphQL API with Apollo Server for complex form submission workflows, using input validation directives and custom error formatting.
- Implemented Prisma ORM with PostgreSQL for data persistence; built type-safe API contracts between React frontend and GraphQL backend.
- Integrated OIDC SSO with JWT authorization and role-based access controls; added Jest/Jasmine unit tests and Cypress E2E coverage.

**COMPTIA / IQVIA / National Merchants Association**
- Developed NestJS backend services with Prisma and PostgreSQL for enterprise-scale applications, exposing both REST and GraphQL endpoints.
- Built React admin dashboards with Apollo Client for GraphQL data fetching, implementing optimistic updates and cache normalization strategies.
- Provisioned Azure infrastructure (App Service, Azure SQL, Blob Storage) with Terraform; deployed containerized services to Kubernetes with automated CI/CD pipelines.
- Supported MongoDB-backed applications with secure access models, data validation, and operational logging patterns.

---

### INSTEC (Insurity) — Senior Software Developer
**Oct 2016 – Jan 2018**

- Developed React and Angular-based UI components integrated with backend Java and C#/.NET Core services via REST APIs.
- Built Node.js/Express.js middleware layer for API response transformation and caching between frontend applications and legacy backend services.
- Authored backend logic supporting CRUD operations and access control; standardized request/response contracts.
- Implemented secure authentication mechanisms across application tiers and built shared libraries for authentication/session handling.
- Implemented Cypress E2E automation, Jasmine/Karma unit tests, and BDD-style acceptance coverage (Gherkin/Cucumber) for critical workflows.
- Collaborated through GitHub workflows with strong software design, peer review, and delivery discipline.

---

### adMixt — Senior Lead Developer
**Jul 2015 – Oct 2016**

- Led AngularJS and early React UI development and coordinated backend API integration using JavaScript/TypeScript with SASS/CSS styling.
- Developed backend endpoints using PHP/Laravel with secure authentication layers and backend validation services.
- Developed Node.js services for real-time ad performance event ingestion and webhook processing, complementing the primary PHP/Laravel backend.
- Integrated payment processing systems and implemented secure request validation and error-handling patterns across services.
- Implemented automated tests using Jasmine, Karma (AngularJS), and Mocha-based testing patterns for backend and integration logic.
- Guided developers on frontend-backend interaction patterns, security practices, and Agile/Scrum delivery.

---

### Afgusa LLC — Senior Developer
**Apr 2014 – Jul 2015**

- Refactored legacy ASP.NET MVC (.NET Framework/C#) applications to AngularJS with backend service integration.
- Developed RESTful services and implemented authorization logic; standardized access control and request validation.
- Worked with MySQL and PostgreSQL-backed persistence and improved performance and reliability of key workflows.
- Implemented Jasmine/Karma-driven AngularJS tests and improved regression coverage for critical UI flows.
- Guided Agile adoption and code review practices across the team.

---

### ATSG (ShoreGroup) — Senior Software Developer
**Mar 2012 – Apr 2014**

- Transitioned legacy systems to MVC architecture with improved backend security and maintainability.
- Developed backend services and data access layers; improved separation of concerns and service boundaries.
- Delivered UI enhancements using jQuery/CSS and maintained PHP-based backend services (including Laravel where used) backed by MySQL.
- Built Node.js utility scripts for log aggregation and deployment automation, supplementing existing shell-based tooling.
- Standardized development environments using Docker to reduce configuration drift and improve onboarding speed.

---

### Greystone — Senior Developer
**Jan 2009 – Jan 2012**

- Modernized PHP/MySQL applications and backend services; refactored backend logic using established design patterns.
- Built UI behavior using JavaScript and jQuery; improved responsiveness and maintainability.
- Implemented Selenium regression testing for critical workflows and improved release confidence.
- Improved cross-browser layout/styling using CSS3.

---

### ePublishing — Senior Developer
**Jan 2005 – Jun 2009**

- Developed Java-based applications using JSP and XSLT for publishing/content workflows.
- Implemented secure backend authentication and data access logic.
- Designed and optimized SQL interactions and data models (MySQL) supporting content and metadata management.
- Implemented XML/XSLT transformation pipelines and maintained styling/templates with CSS3.

---

### Arkansas Blue Cross and Blue Shield — Software Developer
**Jan 2002 – May 2005**

- Developed backend scripts and SQL routines for healthcare data systems.
- Implemented secure access controls for DB2-based applications.
- Built automation and integration utilities in Perl and C++ supporting operational workflows and data validation.
- Worked with XML payloads for data exchange and structured validation/transformation.

---

## Education

**Bachelor of Science in Computer Science** — University of Arkansas at Little Rock (May 2022)

---
