# Privacy Policy

Ice Guard is designed with **privacy-by-design** principles.  
This document explains what data is collected, how it is processed, and the steps taken to reduce risk to individuals while preserving the platform’s core purpose: public visibility into enforcement activity patterns.

Ice Guard intentionally minimizes data collection and avoids retaining information that is not strictly necessary for functionality.

---

## Guiding Principles

Ice Guard’s privacy decisions are guided by the following principles:

- **Data minimization**: collect only what is needed
- **Purpose limitation**: data is used only for stated functionality
- **Safety over precision**: visibility is balanced with harm reduction
- **Transparency**: data handling logic is open source and auditable
- **No surveillance**: Ice Guard does not track individuals

---

## Data We Collect

### Community Report Data

When a user submits a report, the following information may be collected:

- Approximate location of the reported event
- Date and time (or approximate time window)
- Free-text description provided by the user
- Optional uploaded media (images or files)

Community reports are **user-generated** and **unverified**.

---

### Location Data Handling

Location is a core part of Ice Guard’s purpose, but **exact precision is intentionally limited**.

Ice Guard applies the following safeguards:

- Submitted locations are **normalized to a bounded accuracy range** (typically on the order of hundreds of meters)
- Exact coordinates are **not publicly exposed**
- Precision bounding is applied consistently across all reports
- The platform does not display exact household-level locations

This approach preserves the ability to observe **where enforcement activity is occurring**, while reducing the risk of identifying specific residences or individuals.

---

### Media Uploads

If media is uploaded:

- Embedded metadata (including EXIF location data) is removed where feasible
- Media is associated only with the corresponding report
- Media is not analyzed for facial recognition or identity inference

---

## Data We Do Not Collect

Ice Guard explicitly does **not** collect or require:

- Real names
- Government-issued identification
- Home addresses
- Phone numbers
- Social security numbers
- Biometric data
- Continuous location tracking

Ice Guard does not attempt to identify reporters.

---

## Authentication & Accounts

If authentication is used:

- Authentication is handled by a third-party identity provider
- Ice Guard does not store user passwords
- Account identifiers are used only to associate submissions and prevent abuse
- Public-facing content does not display user identities

---

## IP Addresses & Logs

Ice Guard may temporarily process IP addresses and request metadata for:

- abuse prevention
- rate limiting
- security monitoring

IP addresses are **not displayed publicly** and are not retained longer than necessary for operational security.

---

## Verified Public Events

The **Verified Public Events** timeline contains:

- Factual summaries of documented incidents
- General locations
- Dates and descriptions
- Links to independent reporting or investigations

This data is sourced from publicly available journalism, investigations, or records and does not originate from user submissions.

---

## Data Sharing

Ice Guard does **not** sell user data.

Data may be shared only in the following circumstances:

- When required to operate the platform (e.g., hosting, storage providers)
- When legally required by a valid legal process
- When responding to security incidents or abuse

Any such sharing is limited to the minimum necessary scope.

---

## Data Retention

- Community reports may be retained to preserve historical patterns
- Reports that violate policy may be removed from public view
- Removal from public view does not necessarily imply deletion from internal records
- Retention policies may evolve as the project matures

---

## Open Source Transparency

Ice Guard is fully open source.

This includes:
- data handling logic
- location normalization logic
- moderation workflows
- security-related design decisions

Anyone may audit how data is processed by reviewing the source code.

---

## Forks and Independent Deployments

Ice Guard is open source and may be deployed independently by third parties.

This privacy policy applies only to deployments operated by the Ice Guard maintainers.  
Forks or derivative deployments may have different privacy practices.

---

## Changes to This Policy

This privacy policy may be updated as the project evolves.

Material changes will be documented in version control and reflected in the repository history.

---

## Contact

For questions or concerns regarding privacy or data handling, please refer to the project repository or open a discussion or issue where appropriate.

---

## Closing Note

Ice Guard exists to make patterns visible without turning individuals into targets.

Privacy is not an afterthought — it is a core design constraint.
