# FQHC Wrap Payment Reconciliation

Recover state wrap payments by reconciling managed-care revenue to the applicable PPS or alternative payment entitlement.

**Primary buyer:** Federally qualified health centers. **Evidence:** PPS rates, APM rates, managed-care encounters, paid claims, qualifying visits, same-day services, supplemental payments, remittances, and state submissions.

Full local application built with React, Vite, Express, PostgreSQL, and OpenRouter. Includes 15 domain-specific capabilities, 105 custom AI workbench fields, three scenario-fill controls per feature, operational registers, workflow transitions, analytics, professional AI decision briefs, audit history, and at least 15 PostgreSQL records per capability.

## Domain capabilities

- Site rate registry
- Managed-care contract mapping
- Encounter ingestion
- Qualifying visit validation
- Same-day visit rules
- PPS rate calculation
- APM rate calculation
- MCO payment allocation
- Wrap amount calculation
- Duplicate encounter control
- State submission file
- Error response remediation
- Payment receipt matching
- Aging and appeal workflow
- Site plan analytics

Run `./start.sh`, then open <http://127.0.0.1:4653>. API: `5653`.

Administrator: `runtime-admin@example.com` / `LocalDemo!2026`. Operator and reviewer credential buttons are available on the login page.
