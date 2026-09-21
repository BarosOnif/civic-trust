# CivicTrust — Conceptual Data Model

## Purpose

The data model supports civic questions, source-backed answers, claim verification, civic reporting, documents, feedback and administrative oversight.

## USERS
- id
- name
- email
- location_preferences
- language
- created_at

Core public use does not need to require registration.

## SOURCES
- id
- organisation
- organisation_type
- government_level
- country
- website
- url
- verification_status
- reliability_level
- publication_date
- last_checked
- active

## DOCUMENTS
- id
- title
- source_id
- document_type
- publication_date
- extracted_text
- status
- uploaded_at

## CIVIC_CONTENT
- id
- title
- body
- category
- source_id
- publication_date
- status

## QUESTIONS
- id
- user_id
- question
- category
- created_at

## ANSWERS
- id
- question_id
- answer
- verification_status
- created_at

## ANSWER_SOURCES
- id
- answer_id
- source_id
- relevance
- supporting_text

## CLAIMS
- id
- user_id
- claim
- verification_status
- explanation
- created_at

## CLAIM_EVIDENCE
- id
- claim_id
- source_id
- evidence
- relationship

Possible relationships: supporting, contradicting, contextual, insufficient.

## REPORTS
- id
- user_id
- category
- title
- description
- location
- anonymous
- contact
- status
- created_at

Possible CivicTrust statuses:
- Received
- Under Review
- Referred
- Resolved
- Closed

These are internal POC statuses and must not be represented as official government case statuses.

## FEEDBACK
- id
- user_id
- answer_id
- rating
- issue_type
- comment
- created_at

## AUDIT_LOG
- id
- administrator
- action
- entity
- previous_state
- new_state
- created_at

## Core Relationships

```text
USER
 ├── QUESTIONS ──> ANSWERS ──> ANSWER_SOURCES ──> SOURCES
 │
 ├── CLAIMS ──────> CLAIM_EVIDENCE ─────────────> SOURCES
 │
 └── REPORTS

SOURCE ──> DOCUMENTS
SOURCE ──> CIVIC_CONTENT
ANSWER ──> FEEDBACK

ADMINISTRATOR ──> AUDIT_LOG
```
