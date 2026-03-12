# WebAlive QA & Functional Evaluation Reports

This repository consolidates a collection of quality assurance reports, functional testing documentation, feature validations and competitor comparisons produced during my tenure as a **Software Tester** at **WebAlive**.  The documents showcase my ability to evaluate platform readiness, identify feature gaps, design reproducible test cases, and benchmark competing solutions.

## Repository structure

```
webalive-evaluation/
├── Operon/
│   ├── Operon‑Evaluation.pdf
│   └── Operon‑Functional‑Testing‑Validation‑Report.pdf
├── Exsited/
│   └── Exsited‑Feature‑Validation‑and‑Competitor‑Comparison.pdf
├── Budget‑Module/
│   ├── Test‑Cases‑Budget‑Module.pdf
│   └── Issue‑Report‑Budget‑Module.pdf
├── Labour‑Hire‑Center/
│   ├── Test‑Cases‑Labour‑Hire‑Center.pdf
│   └── Issue‑Report‑Labour‑Hire‑Center.pdf
├── QA‑Issue‑Report‑Template.pdf
└── README.md (this file)
```

## Overview of contents

### Operon documents

- **Operon Enterprise Readiness & Competitor Positioning Report (PDF)** – Evaluates the **Operon** field‑service management platform for enterprise readiness.  It assesses workflow maturity, automation depth, financial integrity, scalability and compliance, validates marketed feature claims, compares Operon with competitors like ServiceM8, Simpro, Tradify and Jobber, and outlines improvement recommendations【491928845124822†L0-L24】.
- **Operon Functional Testing & Validation Report (PDF)** – A structured functional validation and quality assessment of the Operon Stage environment.  It simulates real‑world user interactions across roles to verify system reliability, workflow accuracy, data visibility and usability【528864310642030†L0-L26】.  The report documents observed behaviour, identifies inconsistencies (e.g., invitation links that require a password and result in token errors), and recommends improvements such as proper token validation and onboarding flows【528864310642030†L40-L169】.

### Exsited documents

- **Exsited Feature Validation and Competitor Comparison (PDF)** – Validates features promised on the StockWise marketing page against the live **Exsited** platform.  The evaluation highlights risks such as overselling due to missing available‑to‑promise (ATP) logic, incomplete multi‑warehouse support and lack of sync dashboards【965811898188725†L17-L24】.  It compares Exsited with competitors like StockWise, Cin7 Core and Unleashed, and suggests improvements (e.g., real‑time sync dashboards, stock transfer lifecycle, two‑way update options)【965811898188725†L39-L116】.

### Budget module documents

- **Test Cases for Budget Module (PDF)** – A suite of test cases verifying the core functionality of the **Exsited Budget** module.  The tests cover navigation to the budget list, verifying UI components (search fields, currency/fiscal year/status filters), table columns and headers, refresh behaviour, and search functionality【899230297456277†L15-L101】.  These test cases provide evidence of systematic test coverage and adherence to expected results.
- **Issue Report for Budget Module (PDF)** – Detailed bug reports for the Budget module.  Issues include CSV imports accepting negative numeric values without validation, and incorrect handling of multiple “Additional Code” options during imports.  Each issue contains preparation steps, reproduction steps, actual vs expected results and recommended validations【928593727716360†L0-L96】.

### Labour Hire Center documents

- **Test Cases for Labour Hire Center (PDF)** – Test scenarios for the **Labour Hire Center** module of Exsited.  Cases include accessing the module, searching labour profiles by exact/partial names, handling invalid search terms, filtering by labour profile and combining filters with search.  Results indicate whether each scenario passes and provide remarks for any deviations【23223216210706†L19-L65】.
- **Issue Report for Labour Hire Center (PDF)** – Highlights issues encountered while testing the Labour Hire Center.  Examples include allowing past dates when setting a session start date, and address auto‑complete fields not populating the road or unit number correctly【596959990293255†L0-L99】.  Each issue records steps to reproduce, actual and expected behaviour, and recommendations for fixes.

### QA template

- **QA Issue Report Template (PDF)** – A reusable template for documenting issues found during testing.  It defines fields for a concise issue summary, description, steps to reproduce, actual vs expected results, attachments, environment, and remarks【989868938933897†L5-L41】.  The template illustrates the structured approach used for defect reporting.

## Key takeaways

- **Comprehensive validation and benchmarking** – The Operon and Exsited evaluations assess platform readiness against enterprise requirements and compare features with leading competitors.  These documents demonstrate the ability to perform end‑to‑end testing, identify functional gaps and propose actionable improvements.
- **Systematic test case design** – The test case suites for Budget and Labour Hire Center modules show a methodical approach to verifying UI components, search and filter logic, and overall workflow behaviour.
- **Clear issue reporting** – Issue reports provide detailed reproduction steps, actual vs expected outcomes, and recommended fixes.  The inclusion of a standard template ensures consistency across all defect reports.

These artefacts together reflect my experience in **software testing**, quality assurance, and competitor analysis.  By sharing this repository, recruiters can see tangible evidence of my analytical skills, attention to detail, and ability to communicate findings effectively.
