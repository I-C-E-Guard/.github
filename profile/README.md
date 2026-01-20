![govactapp-banner](./images/govactapp-banner-dark.png#gh-dark-mode-only)
![govactapp-banner](./images/govactapp-banner-light.png#gh-light-mode-only)
**Open infrastructure for documenting government activity**

GovAct is a community-driven, fully open-source platform for documenting and visualizing publicly observable government activity and its real-world impacts — both positive and negative.

The project currently focuses on **U.S. immigration enforcement activity**, particularly actions carried out by **ICE** and related agencies within **DHS**, **DOJ**, **DOD**, and cooperating entities. Its purpose is to make fragmented events observable, archivable, and reviewable over time through a public, neutral record.

GovAct is **documentation and situational-awareness infrastructure** — not a news organization, not an advocacy platform, and not an authority on the accuracy of any individual report.

---

## What GovAct Does

- Collects **user-submitted community reports** for situational awareness  
- Displays aggregated activity on a **public interactive map**  
- Maintains a separate timeline of **verified public events**  
- Applies **privacy-preserving location handling** by default  
- Enforces safety and neutrality through **technical controls**  
- Remains fully **open source, auditable, and redeployable**  

---

## Current Focus

GovAct’s current operational focus is immigration enforcement activity involving ICE and other federal agencies.

This focus reflects urgency rather than exclusivity.  
The underlying platform is intentionally designed to be **agency-agnostic**, allowing expansion to other forms of government activity without re-architecting the system or changing its core principles.

---

## Why This Project Exists

Government actions with material real-world consequences are often:

- reported inconsistently  
- dispersed across local outlets and public records  
- forgotten over time  

When events are fragmented, patterns are difficult to see and historical memory degrades.

GovAct exists to ensure that documented events are **not lost to omission, fragmentation, or selective memory**, and that public understanding can emerge from durable, aggregated record-keeping rather than isolated accounts.

---

## Information Model

GovAct separates information into two layers, each with a clear trust model.

### Community Reports
- User-submitted and **unverified**  
- Intended for situational awareness  
- Clearly labeled and contextualized  
- Moderated only for policy violations  

### Verified Public Events
- Curated historical records  
- Based on independent journalism, investigations, or official inquiries  
- Strict sourcing and review standards  
- Factual summaries with external references  

This separation allows visibility without overstating certainty.

---

## Safety & Harm Reduction

GovAct is designed to preserve visibility **without enabling harm**:

- No doxxing or publication of precise residential addresses  
- No real-time tracking or coordination features  
- No calls for confrontation, evasion, or interference  
- Location data is normalized to a bounded accuracy range  
- Uploaded media is scrubbed of embedded location metadata (EXIF)  

These constraints are enforced by **code and system design**, not discretionary moderation.

---

## Built for Developers

GovAct is engineered as public infrastructure, not a closed platform.

- Fully open source under **AGPL-3.0**  
- Modular, auditable architecture  
- Infrastructure-as-code and reproducible deployments  
- Clear separation between ingestion, storage, and presentation  
- Designed for independent deployment and long-term survivability  

If this project disappears, the intent is explicit:  
**anyone should be able to clone this repository and bring a functional instance online.**

---

## Get Involved

GovAct is an open-source project and welcomes contributions in many forms, including code, documentation, review, and deployment.

If you’re interested in helping build or maintain the platform, start here:

- **Contributing** → [`CONTRIBUTING.md`](./docs/CONTRIBUTING.md)
- **Content Policy** → [`CONTENT_POLICY.md`](./docs/CONTENT_POLICY.md)
- **Privacy & data handling** → [`PRIVACY.md`](./docs/PRIVACY.md)  
- **Security reporting** → [`SECURITY.md`](./docs/SECURITY.md)  
- **Code of conduct** → [`CODE_OF_CONDUCT.md`](./docs/CODE_OF_CONDUCT.md)  
- **Project overview** → [`OVERVIEW.md`](./docs/OVERVIEW.md)  
- **Architecture & deployment** → [`ARCHITECTURE.md`](./docs/ARCHITECTURE.md)

---

## Open Source & Project Resilience

All code in this repository is licensed under the  
**GNU Affero General Public License v3.0 (AGPL-3.0)**.

This ensures that:

- Source code remains publicly available  
- Network-hosted deployments must publish modifications  
- Improvements cannot be quietly privatized  
- The platform cannot be captured, closed, or made opaque  

Open source is not branding — it is a safeguard.

---

## Disclaimer

GovAct does not verify, endorse, or guarantee the accuracy of user-submitted community reports.

Information provided through the platform should be independently verified before being relied upon.

Use of GovAct is at your own discretion.

---

## Closing Note

GovAct exists because information that is difficult to see is difficult to evaluate.

By making government activity observable, locations meaningful, records durable, and systems reproducible, GovAct aims to support informed public understanding — without editorial direction, without imposed conclusions, and without reliance on any single organization to keep it alive.
