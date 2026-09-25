# Information Security Policy Suite

Five board-ready information security policies, each mapped to specific ISO/IEC 27001:2022 Annex A controls, with a policy tracker maintaining version, ownership, and review status.

This is a non-technical GRC deliverable — no code, no infrastructure — modelling the actual policy documents a GRC analyst drafts and maintains as part of an organisation's ISMS documentation.

## Scenario

**Meridian Analytics Ltd** (fictional), full policy suite effective 1 October 2026, approved by the Audit Committee, reviewed annually.

This project connects to the rest of this portfolio: the policies reference and are consistent with findings from companion projects for the same fictional company - the [ISO 27001 gap assessment](https://github.com/SanikaMahamulkar/iso27001-gap-assessment) (control mappings), the [ITGC audit](https://github.com/SanikaMahamulkar/itgc-audit-testing) (access removal SLA, contractor offboarding gap), and the [enterprise risk register](https://github.com/SanikaMahamulkar/enterprise-risk-register) (referenced risk areas) - so the policies reflect the same organisation's actual documented gaps and controls rather than being written in isolation.

## Deliverables

| Policy | Owner | ISO 27001:2022 Controls |
|---|---|---|
| POL-001 Acceptable Use Policy | Head of GRC | A.5.10 |
| POL-002 Access Control Policy | IT Security Manager | A.5.15, A.5.16, A.5.17, A.5.18, A.8.2, A.8.5 |
| POL-003 Incident Response Policy | IT Security Manager | A.5.24, A.5.25, A.5.26, A.5.27, A.5.28 |
| POL-004 Data Classification Policy | Data Protection Officer | A.5.12, A.5.13 |
| POL-005 Remote Working Policy | HR Director | A.6.7, A.7.9, A.8.1 |

- **`deliverables/Policy_Suite_Tracker.xlsx`** — version, owner, approver, effective/review dates, and a formula-driven status flag (Active / Under Review / Overdue) per policy.

## Structure

Each policy follows a consistent format: Purpose, Scope, Policy Statements (with numbered subsections), Roles & Responsibilities, Enforcement, and Related Documents - cross-referencing the other policies in the suite by Policy ID, as a real, internally consistent document set would.

## Note

This is a self-directed portfolio project modelling a real information security policy suite against a fictional company. All policy content is illustrative.

## Author

Sanika Mahamulkar - MSc Cybersecurity, University of Bristol
