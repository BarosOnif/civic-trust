# CivicTrust — Evidence Before Confidence

**CivicTrust** is an AI-assisted civic information and action platform that helps people:

**FIND → UNDERSTAND → VERIFY → ACT**

It is designed to help citizens find reliable civic information, understand policies and public documents, verify civic claims against available evidence, and identify appropriate next steps.

## Live Proof of Concept

**https://civic-trust.base44.app/**

The CivicTrust proof of concept is publicly accessible and does not require a user account to explore the core experience.

---

## The Problem

Civic information is available across government websites, public documents, PDFs, news organisations, social media, messaging platforms and community channels.

However, citizens may still struggle to:

* find the right information;
* understand complex policies or public documents;
* determine whether a civic claim is accurate or outdated;
* identify which source to trust;
* know which institution is responsible for an issue;
* know what to do next;
* report civic, public-service or safety concerns through an appropriate channel.

This can create:

**Fragmented information → uncertainty → misunderstanding → misinformation → frustration → inaction**

CivicTrust aims to bridge that gap:

**Information → Evidence → Understanding → Action**

---

## What CivicTrust Does

CivicTrust brings several civic-information tasks into one experience.

### Ask CivicTrust

Users can ask civic questions in natural language and receive an understandable response supported by available civic information.

### Verify a Claim

Users can submit a civic claim and receive a verification assessment based on available evidence.

### Evidence & Sources

CivicTrust makes source information visible so users can understand where an answer came from and inspect the available evidence.

### Document Explainer

Users can use AI-assisted explanations to understand complex civic documents, policies and notices.

### Civic Explore

Users can explore civic information across areas such as:

* Government Services
* Laws & Policies
* Elections & Voting
* Public Institutions
* Your Rights
* Public Spending
* Education
* Transport
* Environment
* Business & Regulation
* Local Government
* Public Safety
* Civic Participation
* Community & Social Cohesion

### Report an Issue

Users can record civic, public-service, community and relevant safety concerns through a structured reporting flow.

### Safety & Protection

CivicTrust supports safety-related reporting and information pathways while clearly distinguishing CivicTrust from an emergency-response service.

### Community & Social Cohesion

The platform helps users navigate community concerns, civic information and appropriate institutional pathways.

### Civic Action

Where sufficient information is available, CivicTrust helps users identify an appropriate institution, reporting channel or next step.

### Admin Dashboard

The proof of concept includes administrative functionality for reviewing reports, managing sources/content and monitoring feedback.

---

## Intended Users

### Primary Users

**Ordinary citizens** who:

* need reliable civic information;
* want to understand public services or policies;
* encounter civic claims online;
* want to verify information before acting on it;
* need to identify the right institution;
* want to report civic or public-service concerns.

### Secondary Users

CivicTrust could also support:

* journalists;
* researchers;
* civil-society organisations;
* community organisations;
* accountability organisations;
* public-interest groups.

---

## Challenge Alignment

### Transparency & Accountability — Primary

CivicTrust helps citizens:

* understand policies and public information;
* verify civic claims;
* inspect evidence and sources;
* identify public institutions;
* find reporting pathways;
* report civic/public-service issues.

### Safety, Reporting & Protection

CivicTrust provides safety-related reporting and information pathways, including privacy-conscious reporting where appropriate.

### Stability & Social Cohesion

CivicTrust supports trusted civic information, claim verification, community concerns and legitimate action pathways that can help reduce misunderstanding and civic friction.

---

## Trust & Accuracy

The core principle is:

> **“We don't ask you to trust the AI. We show you the evidence.”**

CivicTrust is designed to:

* prioritise authoritative sources where available;
* make supporting evidence visible;
* show source and freshness information where available;
* communicate uncertainty;
* identify conflicting information;
* distinguish user-submitted information from verified sources;
* avoid fabricating sources, laws, institutions, statistics, quotations or actions.

Claim verification can use nuanced statuses including:

* Supported
* Contradicted
* Partially Supported
* Not Supported
* Outdated
* Unverified
* Needs Context

CivicTrust should never claim that a report was submitted to an external government agency unless a real integration exists and the submission was actually completed.

---

## Privacy

The product follows a data-minimisation approach.

The application should not unnecessarily request sensitive information such as:

* NIN;
* BVN;
* bank details;
* passwords;
* other unnecessary personal information.

Anonymous reporting can be supported where appropriate.

---

## How to Run / Use the Project

### Option 1 — Use the Live Proof of Concept

The easiest way to run CivicTrust is through the publicly deployed application.

Open:

**https://civic-trust.base44.app/**

No local installation is required to explore the public proof of concept.

From the homepage, you can explore the available CivicTrust workflows, including:

1. Ask CivicTrust
2. Verify a Claim
3. Explore Civic Information
4. View Evidence and Sources
5. Report an Issue
6. Explore Safety/Community functionality where available

### Option 2 — Run Locally

The current repository does **not** contain the Base44-generated application source code.

As a result, there is currently no local `npm install`, build or deployment command provided by this repository.

The application is hosted through Base44 and is accessed through the live URL above.

If the underlying application source code becomes available in future, local installation and development instructions can be added to this README.

---

## Repository Contents

This repository contains the project documentation and development record for CivicTrust.

```text
civictrust/
│
├── README.md
│
├── docs/
│   ├── product-overview.md
│   ├── problem-statement.md
│   ├── intended-users.md
│   ├── challenge-track-alignment.md
│   ├── design-principles.md
│   ├── ai-and-trust-principles.md
│   ├── future-development.md
│   └── submission-assets.md
│
├── architecture/
│   ├── system-architecture.md
│   ├── user-flow.md
│   └── architecture-diagram.png
│
├── database/
│   └── data-model.md
│
├── design/
│   └── screenshots/
│
├── demo/
│   ├── demo-script.md
│   ├── demo-scenarios.md
│   └── demo-video-link.md
│
└── prompts/
    ├── master-build-prompt.md
    ├── enhancement-prompt.md
    └── ai-behaviour-guardrails.md
```

---

## How AI Was Used

CivicTrust was developed with AI-assisted tools.

**Base44** was used to build and deploy the working proof of concept.

**ChatGPT** was used to support product development, including:

* product and user-flow definition;
* application-building prompts;
* AI behaviour and trust guardrails;
* architecture and data-model planning;
* documentation;
* demonstration and submission materials.

AI was used as a development and productivity tool. It was not treated as the authority for civic information.

---

## Implementation Note

CivicTrust was developed as a working proof of concept using **Base44, an AI-assisted application development platform**.

The underlying Base44-generated application source code is not included in this repository.

This repository therefore serves as the project's **public documentation and project record**, containing the product concept, problem statement, intended users, challenge-track alignment, architecture, data model, design references, AI-development prompts, trust principles and demonstration materials.

The live application is available at:

**https://civic-trust.base44.app/**

This repository does not claim to contain the underlying Base44-generated application source code.

---

## Project Status

**Status:** Working Proof of Concept

**Primary Challenge Track:** Transparency & Accountability

**Secondary/Cross-Tracks:**

* Safety, Reporting & Protection
* Stability & Social Cohesion

**Initial Geography:** Nigeria

**Core Principle:** Evidence Before Confidence

---

## Submission Materials

* **Working POC:** https://civic-trust.base44.app/
* **GitHub Repository:** This repository
* **Demo Video:** [Insert final demo link]
* **Pitch Deck:** [Insert final PDF/link]
* **Written Summary:** [Insert final PDF/link]

---

## CivicTrust

### Evidence Before Confidence

**Find. Understand. Verify. Act.**
