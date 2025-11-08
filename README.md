# Zarish Sphere
>*A Unified Digital Heartbeat for Humanitarian Impact*
---
The Zarish Sphere Platform is an enterprise-grade, open-source, distributed system designed to manage the full spectrum of operations for global non-profit development organizations. It serves as a unified digital ecosystem, replacing fragmented monolithic systems (like traditional ERP and EHR platforms) with a modern, modular, and flexible architecture. Built for maximum reusability, zero-touch provisioning, and robust offline capability, it ensures seamless utility from central HQ to remote field units.

---
## Developer Overview
Platform Name: Zarish Sphere\
Platform Tagline: "A Unified Digital Heartbeat for Humanitarian Impact"\
Developed By: Arwa Zariah Technologies\
Developer Theme Tagline: "The Code and The Brain"\
Website: https://www.zarishsphere.com \
Emails: zarishsphere@gmail.com, ZarishSphere@tutamail.com, Zarish-Sphere@protonmail.com\
Cell, WhatsApp & Telegram: +880 1684364243

---
## Vision
To be the global standard for modular, open-source, data-driven humanitarian operations management—empowering low-resource environments with high-reliability, offline-first technology, and fostering evidence-based research for maximum impact.

---
## Mission
To provide a secure, scalable, and customizable digital platform that unifies global administrative (ERP) and clinical (EHR) operations, enabling real-time data synchronization across all organizational tiers—from remote field execution to headquarters.

---
## Core Principles
* Code Reuse & Reduced Duplication: Reusable components, APIs, and templates to eliminate redundant effort.
* Modular Architecture (Lego Block Principle): Easy addition, removal, or updating of modules to extend functionality or tailor to specific needs via microfrontends and microservices.
* Configuration-First (Settings Menu Principle): Each frontend module specifies its config properties; non-developers can customize via simple, click-based selections. Supports hierarchical layers (Organization > Country > Project > Department > Site) with overrides for adaptability.
* Offline-First Capability: Robust functionality in low-connectivity environments, with seamless auto-sync upon reconnection.
* Enhanced Usability & UI: Intuitive, responsive UI optimized for point-of-service, supporting complex records, mobile devices, and multi-language translation (English primary; configurable secondary languages per country).
* Modern Technologies: Appeals to global developers with contemporary stacks, ensuring stability, security, scalability, and sustainability (4S: redundancy, failover, monitoring).
* Improved Interoperability (Universal Adapter Principle): Native support for FHIR, HL7, and other standards; API-first design for loose coupling.
* Template-Driven: Every module, service, and application as pre-configured, ready-to-use templates with minimal modifications via click-based selection.
* Privileges & User Management: Role-based access control (RBAC) with granular permissions by location, module, layer, or data type.
* Backup & Recovery: Automated backups, offsite storage, and recovery procedures for reliability.
* Integrated & Innovative: Seamless ecosystem connectivity, leveraging state-of-the-art open-source tools.
* Sustainable & Open Source: MIT-licensed; portable (agnostic architecture, containerization); adaptable (easy updates); recoverable (4S redundancy); testable (automated testing); secure (GDPR/HIPAA-compliant); reliable (redundancy); interoperable (HIE standards); collaborative (community sharing); achievable (roadmap-focused); data-driven (timely insights).
---
## Key Technology Stack
* Architecture: Microfrontend, Modular, Microservices, Single Page Application (SPA).
* Backend: Go (Golang) language; Gin framework; GORM for DB communication.
* Frontend: React + TypeScript; Module Federation for microfrontends; Bootstrap & Material Design for styling.
* Database: PostgreSQL primary; additional open-source DBs for offline sync and geospatial data.
* Security: Keycloak for IAM, SSO, OAuth2.
* Deployment: Docker containerization; Kubernetes orchestration; Terraform for IaC; Traefik API gateway.
* CI/CD: GitHub Actions.
* Monitoring: Prometheus + Grafana.
---
## The Zarish Sphere Ecosystem
* zarish-sphere: Core platform foundation for module orchestration.
* zarish-access: Central user management (Keycloak) with RBAC and activity-level access.
* zarish-terms: Foundational tools for data standards (concepts directory, terminology, attributes, user roles, address hierarchy).
* zarish-forms: GUI-based form builder for non-developers to create/edit/render forms interactively.
* zarish-connect: Integration hub for external systems (FHIR, HL7, EWARS, DHIS2, ODK, HXL, Google Drive, OneDrive).
* zarish-insight: Advanced analytics (ad-hoc queries, cohort builder, integration with Looker Studio/Apache Superset).
* zarish-management: High-level management, reporting, and dashboards.
* zarish-wiki: Knowledge base and documentation module.
* zarish-his: Health Information System for clinical activities (patient charts, diagnoses, prescriptions).
* zarish-fin: Financial module for billing, accounting, and budgeting.
* zarish-log: Logistics and inventory for supply chain management.
* zarish-hra: Human Resources and Administration for staff/payroll.
* zarish-geo: Geospatial tools for mapping and location-based ops.
* zarish-support: Program support (training, field coordination, research, M&E).
