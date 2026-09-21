# CivicTrust — System Architecture

## Overview

CivicTrust is an AI-assisted civic information and action platform built around the journey:

**FIND → UNDERSTAND → VERIFY → ACT**

The architecture places evidence and source transparency between AI-assisted processing and the citizen-facing answer.

## Major Components

### 1. Citizen Interface
- Ask CivicTrust
- Verify a Claim
- Explore Civic Information
- Evidence & Sources
- Document Explainer
- Report an Issue
- Safety & Protection
- Community & Social Cohesion
- Civic Action / Next Step

### 2. AI / Intent / Search Layer
AI assists with:
- natural-language understanding;
- intent classification;
- query interpretation;
- search and retrieval;
- summarisation;
- document explanation;
- claim extraction;
- evidence comparison;
- next-step identification.

AI output should remain grounded in available evidence.

### 3. Civic Information Layer
The platform can work with:
- official/public sources;
- public institutions;
- public records and legal materials;
- research/civil-society sources;
- reputable media;
- clearly labelled user-submitted information;
- demonstration data for the POC.

### 4. Evidence & Trust Layer
This layer supports:
- source classification;
- source freshness;
- supporting evidence;
- source relevance;
- conflicting-source visibility;
- uncertainty handling.

### 5. Action Layer
The platform can move users towards:
- an explanation;
- a verification result;
- a responsible institution;
- a reporting pathway;
- a support/resource pathway;
- a CivicTrust report.

It must never claim an external action was completed unless a real integration exists.


## Security and Privacy Boundary

The public interface should minimise data collection. Administrative functions should be protected by role-based access.

Sensitive information such as NIN, BVN, financial information and passwords should not be collected unnecessarily.

## Architecture Status

This is a **conceptual architecture for the POC**. It documents product behaviour and data relationships rather than exposing proprietary implementation details of the Base44-generated application.
