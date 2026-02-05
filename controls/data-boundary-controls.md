# Data Boundary Controls

## 1. Data Classification

All data used in AI systems must be labeled:
- Public
- Internal
- Confidential
- Restricted

## 2. Prohibited Inputs

- PII to public LLMs
- Production secrets
- Security credentials
- Unredacted customer data

## 3. Redaction Layer

Before AI processing:
- Token masking
- Field stripping
- Data minimization

## 4. API Governance

- Centralized API key management
- Environment-based restrictions
- Usage logging
