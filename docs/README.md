# OctoAcme Project Management Documentation

Welcome to OctoAcme's central hub for project management documentation. This README serves as the primary entry point for all project management processes, guidelines, and resources.

## Project Management Processes Overview

OctoAcme employs a structured, iterative project management framework built on five core principles: customer-first prioritization, iterative delivery, clear ownership, data-informed decisions, and psychological safety. The project lifecycle follows a well-defined five-phase approach: Initiation, Planning, Execution, Release, and Close & Retrospective. Each project begins with a lightweight Project One-pager that establishes the problem statement, SMART objectives, success metrics, and stakeholder alignment before moving into detailed planning. This ensures business need validation and resource commitment before significant effort is invested. The framework applies to all cross-functional projects delivering product features, services, or integrations, with clear decision gates between phases to maintain focus and alignment.

OctoAcme defines three primary roles with distinct responsibilities: Project Managers coordinate delivery, schedules, risks, and communications; Product Managers define outcomes, prioritize backlogs, and measure success; and Developers implement features while collaborating on design and testability, with QA/Testing validating acceptance criteria. The execution workflow centers on GitHub Projects boards with six standard columns (Backlog, Ready, In Progress, In Review, QA, Done) and emphasizes small pull requests (≤400 lines) that include issue links, acceptance criteria, and automated testing before review.

Communication follows a structured cadence: daily 15-minute standups, weekly delivery syncs, bi-weekly team standups, monthly stakeholder updates, and sprint-end demos. Quality assurance is embedded throughout with unit tests, integration tests, end-to-end smoke tests, security scanning in CI pipelines, and manual QA when needed. All code requires at least one approval before merging, and releases cannot proceed without passing CI, security scans, drafted release notes, documented rollback plans, and successful staging smoke tests.

OctoAcme institutionalizes learning through mandatory retrospectives with structured formats capturing what went well, what could improve, and 2-3 prioritized action items with clear owners. The release process is standardized across three types (patch, minor, major) with comprehensive checklists covering deployment windows, backups, staging validation, post-deploy verification, and stakeholder announcements.

## Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## Purpose

This README improves discoverability, serves as an onboarding accelerator, and reinforces process standards by providing a single entry point for all project management documentation.
