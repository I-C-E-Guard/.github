# Ice Guard

**Ice Guard** is a community-driven, fully open-source platform for documenting and visualizing user-submitted reports of Immigration and Customs Enforcement (ICE) presence and related incidents, with the goal of improving public awareness and personal safety.

Ice Guard exists to address a growing **visibility gap**: many enforcement actions and their impacts occur quietly, are reported inconsistently, or are dispersed across local outlets, court filings, and congressional records. When events are fragmented, patterns are difficult for the public to see.

Ice Guard is designed as **situational awareness and documentation infrastructure** — not a news outlet, not an advocacy organization, and not an authority on the accuracy of any individual report.

---

## Why This Project Exists

Across the country, significant enforcement-related incidents often surface briefly — if at all — before fading from public awareness. Individually, these events may appear isolated. Collectively, they form patterns that are difficult to observe without aggregation.

Ice Guard exists to make that information:

- observable  
- archivable  
- referencable  
- contextualized over time  

The goal is not to persuade, editorialize, or provoke — but to ensure that documented events are not lost to fragmentation or obscurity.

---

## What Ice Guard Is

- A public, interactive map of user-submitted reports
- A tool for visibility and awareness, not enforcement
- A platform for documenting patterns over time
- Fully open-source software built for transparency and resilience

---

## What Ice Guard Is Not

- Not a real-time tracking or surveillance tool  
- Not a verification or fact-checking authority for community reports  
- Not a call to action, confrontation, or interference  
- Not affiliated with ICE or any government agency  

All community reports are **user-generated**, **unverified**, and should be interpreted accordingly.

---

## Core Principles

### Transparency
Ice Guard is fully open source.  
Policies are enforced by code, not discretion.

### Safety First
The platform is designed to reduce harm while preserving visibility:

- No doxxing
- No publication of precise residential addresses
- No calls for confrontation or evasion
- No real-time coordination features

### Neutral Infrastructure
Ice Guard provides a place for information to exist.  
Interpretation is left to the public.

### Accountability Through Documentation
Patterns emerge through aggregation, not assertions.

---

## How It Works (High-Level)

1. Users submit reports via the public web application
2. Reports include location, time, and a description
3. Uploaded media is scrubbed of embedded location metadata
4. Report locations are normalized to a bounded accuracy range
5. The map displays aggregated reports within a geographic area
6. Moderation workflows exist to address policy-violating content

---

## Location Data Handling

Location is a core part of Ice Guard’s purpose.

To balance **visibility** with **individual safety**, Ice Guard applies the following rules:

- User-submitted locations are stored and displayed with a **bounded accuracy range** (typically on the order of hundreds of meters)
- Exact coordinates are not publicly exposed
- Uploaded images and media have embedded location metadata (EXIF) removed
- Location normalization is applied consistently across all reports

This approach preserves the ability to observe **where enforcement activity is occurring**, while reducing the risk of identifying specific households or individuals.

---

## Information Layers

Ice Guard intentionally separates information into two distinct layers, each with a different trust model.

---

## Community Reports

Community Reports are **user-submitted and unverified**.

They are intended for situational awareness and may be:

- incomplete  
- inaccurate  
- delayed  
- subjective  

Community Reports:

- appear on the public map
- are clearly labeled as unverified
- may be moderated or removed if they violate policy

---

## Verified Public Events

In addition to community reports, Ice Guard maintains a **Verified Public Events** timeline.

This section serves as a curated historical record of significant ICE-related incidents that have been **independently reported and investigated** by established journalists, watchdog organizations, or official inquiries.

These entries are not opinions and are not user submissions.

Each Verified Public Event includes:

- Date of occurrence
- General location
- A factual summary of what occurred
- Links to independent reporting or investigations
- Notes on verification sources

Only events that meet strict sourcing and review standards are included.

---

## Project Structure

This repository contains the **entire Ice Guard platform**.

All components are open source and intended to be deployable by anyone.

- `iceguard.app` — public web application (map, submissions)
- `api.iceguard.app` — public API (read + submit reports)
- administrative and moderation services
- infrastructure and deployment tooling

If this project disappears tomorrow, the intent is that someone else can clone the repository, run the documented setup commands, and bring a functional instance online.

---

## Open Source & Licensing

Ice Guard is **fully open source by design**.

All code in this repository is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.

This licensing model ensures that:

- The source code remains publicly available
- Network-hosted deployments must publish their modifications
- Improvements remain accessible to the community
- The project cannot be quietly closed, captured, or made opaque

Open sourcing everything is a deliberate choice.  
Resilience, auditability, and redeployability are core goals — even when this increases operational difficulty.

---

## Privacy & Data Handling

Ice Guard is built with **privacy-by-design** principles:

- No requirement to submit real names
- No public display of reporter identities
- Uploaded media is scrubbed of embedded location data
- Location accuracy is intentionally bounded, not eliminated

See `PRIVACY.md` for details.

---

## Security Posture

Ice Guard follows a defense-in-depth approach:

- Edge protection and rate limiting
- Strong authentication and authorization
- Least-privilege database access
- Open, auditable security controls

Security through obscurity is explicitly avoided.

If you discover a security issue, please follow the guidance in `SECURITY.md`.

---

## Disclaimer

Ice Guard does not verify, endorse, or guarantee the accuracy of community-submitted reports.

Information provided through the platform should be independently verified before being relied upon.

Use of Ice Guard is at your own discretion.

---

## Closing Note

Ice Guard exists because information that is difficult to see is difficult to evaluate.

By making events observable, locations meaningful, records durable, and systems reproducible, Ice Guard aims to support informed public understanding — without commentary, without directives, and without conclusions imposed by the platform itself.
