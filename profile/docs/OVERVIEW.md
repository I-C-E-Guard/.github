![govactapp-banner](../images/govactapp-banner-dark.png#gh-dark-mode-only)
![govactapp-banner](../images/govactapp-banner-light.png#gh-light-mode-only)

Back to [README.md > Get Involved](../README.md#get-involved)

# GovAct — Project Overview

GovAct is a community-driven, fully open-source platform for documenting and visualizing publicly observable government activity and its real-world impacts — both positive and negative.

It exists to preserve **visibility, historical continuity, and public understanding** in domains where information is often fragmented, ephemeral, or selectively remembered.

GovAct is not a news organization.  
It is not an advocacy platform.  
It is not an authority on truth, intent, or moral judgment.

GovAct is **documentation infrastructure**.

---

## Why GovAct Exists

Across jurisdictions and agencies, government actions with material consequences frequently occur with:

- limited transparency
- inconsistent reporting
- short-lived media attention
- fragmented public records

Individually, these events may appear isolated.  
Collectively, they form patterns that are difficult to observe without aggregation.

When records fragment, public understanding degrades.  
When memory fades, accountability weakens.

GovAct exists to ensure that **documented events are not lost to omission, fragmentation, or time**, and that meaningful patterns can be observed without relying on any single organization, outlet, or narrative to preserve them.

---

## Current Focus and Scope

GovAct’s current operational focus is **U.S. immigration enforcement activity**, particularly actions carried out by:

- Immigration and Customs Enforcement (ICE)
- Agencies within the Department of Homeland Security (DHS)
- The Department of Justice (DOJ)
- The Department of Defense (DOD), where applicable
- Cooperating federal, state, or local entities

This focus reflects urgency rather than exclusivity.

Immigration enforcement actions occur at scale and often have immediate, irreversible impacts on individuals, families, and communities. Despite this, comprehensive and centralized public records of such activity remain limited.

GovAct provides a **public portal** where these actions can be observed collectively, preserved over time, and examined in context.

The platform itself is intentionally designed to be **agency-agnostic**, allowing future expansion to other forms of government activity without re-architecting or altering core principles.

---

## Impartial Documentation

GovAct is committed to **completeness over narrative**.

Many documented events involve allegations or findings of misconduct, abuse, or inhumane treatment. These events deserve to be recorded and remembered.

At the same time, impartial documentation requires that **all materially relevant outcomes** are preserved — including cases that complicate, challenge, or contradict prevailing narratives.

Individuals harmed or killed during enforcement actions deserve their stories documented.  
Individuals harmed or killed by others in contexts related to enforcement also deserve accurate and durable record-keeping.

GovAct does not curate outrage.  
It does not suppress inconvenient facts.  
It does not select stories based on ideological alignment.

It preserves record.

The platform documents **what was reported**, **where**, **when**, and **how**, without imposing conclusions about intent, justification, or moral weight.

---

## Neutrality by Design

GovAct’s neutrality is not rhetorical — it is structural.

The system is designed so that:

- events can exist without endorsement
- documentation does not imply advocacy
- visibility does not become targeting
- interpretation is left to the public

GovAct provides infrastructure for information to exist.  
It does not tell users what to think about that information.

Patterns are allowed to emerge **through aggregation**, not assertion.

---

## Information Layers and Trust Model

GovAct intentionally separates information into distinct layers, each with a different trust model.

### Community Reports

Community Reports are:

- user-submitted
- unverified
- intended for situational awareness

They may be incomplete, inaccurate, delayed, or subjective.

Community Reports:
- appear on the public map
- are clearly labeled as unverified
- are moderated for safety and policy compliance
- are not treated as factual determinations

Their value lies in aggregation, not individual certainty.

---

### Verified Public Events

GovAct also maintains a **Verified Public Events** timeline.

This layer contains curated historical records of significant incidents that have been independently reported, investigated, or formally documented by:

- established journalists
- watchdog organizations
- court proceedings
- official inquiries

These entries are not user submissions.

Each Verified Public Event includes:
- date of occurrence
- general location
- a factual summary
- links to independent sources
- notes on verification criteria

This separation preserves visibility without overstating certainty.

---

## Safety and Harm Reduction

GovAct is designed to preserve visibility **without enabling harm**.

Safety constraints are enforced by **technical design**, not discretionary moderation alone.

Non-negotiable safeguards include:

- No doxxing or publication of precise residential addresses
- No identification or targeting of private individuals
- No real-time tracking or coordination features
- No calls for confrontation, evasion, or interference
- Location data normalized to a bounded accuracy range
- Uploaded media scrubbed of embedded location metadata (EXIF)

These constraints exist to prevent the platform itself from becoming a source of risk.

---

## Location Data Handling

Location is central to GovAct’s purpose, but **precision is intentionally limited**.

GovAct applies the following safeguards:

- User-submitted locations are stored and displayed with bounded accuracy
- Exact coordinates are not publicly exposed
- Precision normalization is applied consistently across reports
- Household-level identification is intentionally prevented

This approach preserves the ability to observe **where activity occurs**, while reducing the risk of identifying specific residences or individuals.

---

## Privacy by Design

GovAct intentionally minimizes data collection.

The platform does **not** require:
- real names
- home addresses
- government-issued identification
- biometric data
- continuous location tracking

Reporter identities are not displayed publicly.

Where authentication is used, it exists solely to:
- associate submissions
- prevent abuse
- enforce rate limits and policy constraints

GovAct is designed to observe **patterns**, not people.

---

## Moderation Philosophy

Moderation exists to protect safety, privacy, and platform integrity — not to shape narratives or silence disagreement.

Moderation decisions are guided by:

- safety over completeness
- consistency over discretion
- documentation over judgment
- transparency over opacity

Content may be redacted, hidden, or removed when it introduces unacceptable risk, regardless of intent.

GovAct is not obligated to host content that creates ongoing safety concerns.

---

## Open Source as a Safeguard

GovAct is fully open source by design.

All code is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.

This licensing model ensures that:

- source code remains publicly available
- network-hosted deployments must publish modifications
- improvements cannot be quietly privatized
- the platform cannot be captured or made opaque

Open sourcing everything is a deliberate choice — even when it increases operational difficulty.

Transparency, auditability, and redeployability are core design goals.

---

## Resilience and Survivability

GovAct is built with the assumption that it **may be disrupted, defunded, or shut down**.

The project is intentionally designed so that:

- no single organization is required to keep it alive
- no proprietary component is essential to its operation
- anyone can clone the repository and deploy a functional instance

If this project disappears tomorrow, the intent is explicit:  
**the system itself should survive elsewhere**.

Resilience through reproducibility is not a side effect — it is a goal.

---

## Who GovAct Is For

GovAct is built for:

- developers who value careful, public-interest infrastructure
- researchers and journalists seeking durable records
- communities seeking visibility without escalation
- donors who want to support neutral, long-term civic tooling
- future maintainers who may inherit the project years from now

GovAct is not optimized for virality, engagement metrics, or monetization.

It is optimized for **durability, auditability, and public utility**.

---

## Limitations and Non-Goals

GovAct intentionally does **not** aim to:

- verify or adjudicate truth in real time
- replace journalism or investigative reporting
- coordinate responses or actions
- provide warnings or alerts
- function as a social network

These are not failures of ambition — they are boundaries.

---

## Closing Note

GovAct exists because information that is difficult to see is difficult to evaluate.

By making government activity observable, locations meaningful, records durable, and systems reproducible, GovAct aims to support informed public understanding — without directives, without imposed conclusions, and without reliance on any single organization to keep it alive.

This project is not about telling people what to think.  
It is about ensuring that what happened is not forgotten.