![govactapp-banner](../images/govactapp-banner-dark.png#gh-dark-mode-only)
![govactapp-banner](../images/govactapp-banner-light.png#gh-light-mode-only)

Back to [README.md > Get Involved](../README.md#get-involved)

# Architecture & Deployment (High-Level)

This document describes GovAct’s architecture at a high level. It is intentionally implementation-agnostic where possible to preserve portability, independent deployment, and long-term resilience.

GovAct is designed as **documentation infrastructure**: separate concerns, enforce safety constraints by design, and keep the system deployable by third parties.

---

## Design Goals

- **Neutral infrastructure**: document events without editorial direction
- **Harm reduction**: enforce safety constraints via technical controls
- **Privacy by design**: minimize data collection and bound location precision
- **Reproducibility**: enable independent deployments
- **Auditability**: keep logic understandable and reviewable
- **Resilience**: avoid single points of organizational failure

---

## System Components (Conceptual)

GovAct is typically composed of:

- **Public Web App**  
  Map UI, report submission UI, and public browsing.

- **Public API**  
  Read endpoints for public map data and submit endpoints for new reports.

- **Moderation/Admin Services**  
  Tools and workflows to review, redact, hide, and remove content that violates policy.

- **Data Store**  
  Persistent storage for reports, moderation state, and system configuration.

- **Media Store (optional)**  
  Storage for uploaded media after metadata stripping and safety processing.

- **Background Workers (optional)**  
  Jobs for media processing, abuse detection, notifications, and periodic maintenance.

---

## Data Flow Overview

1. A user submits a report (text, time window, approximate location, optional media).
2. The API validates the submission against policy constraints.
3. Location is normalized to a bounded precision range.
4. Media (if present) is processed to remove embedded metadata (e.g., EXIF).
5. The report is stored with a moderation state (e.g., Visible or Flagged).
6. The public app fetches aggregated results for map display.
7. Moderation tools support review, redaction, hiding, or removal.

---

## Trust Model

GovAct separates information into layers:

- **Community Reports**  
  User-submitted and unverified. Intended for situational awareness and pattern observation.

- **Verified Public Events**  
  Curated entries backed by independent reporting, investigations, or official inquiries.

This separation is structural and should remain explicit in UI and API semantics.

---

## Safety Constraints (Non-Negotiables)

GovAct must not provide features that materially enable harm, including:

- Real-time tracking or coordination
- Exposure of precise residential locations
- Doxxing or identification of private individuals
- Calls to action that enable confrontation or evasion

These constraints should be enforced via validation, storage rules, and presentation logic.

---

## Deployment Notes

GovAct is intended to be deployable by third parties.

Recommended deployment properties:

- Infrastructure-as-code where feasible
- Clear environment separation (dev/staging/prod)
- Strong authentication and authorization boundaries
- Rate limiting and abuse controls at the edge
- Least-privilege data access for services
- Secure handling of secrets and tokens

---

## Where to Look Next

- Policy enforcement: `CONTENT_POLICY.md`
- Moderation workflows: `MODERATION.md`
- Data handling & privacy: `PRIVACY.md`
- Vulnerability reporting: `SECURITY.md`
- Contribution process: `CONTRIBUTING.md`