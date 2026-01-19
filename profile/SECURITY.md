# Security Policy

Ice Guard takes security seriously.

Because this project deals with real-world events that affect real people, security issues can have **safety and privacy implications**, not just technical ones. Responsible disclosure is essential.

---

## Supported Versions

Ice Guard is an actively developed project.

Security fixes are applied to the latest version of the codebase.  
Older forks or deployments may not receive updates.

---

## Reporting a Vulnerability

**Please do not report security vulnerabilities via public GitHub issues, pull requests, or discussions.**

If you discover a security issue, including but not limited to:

- authentication or authorization bypass
- data exposure or leakage
- abuse or spam amplification vectors
- denial-of-service vulnerabilities
- privilege escalation
- moderation or policy bypass
- unsafe handling of location or media data

please report it **privately**.

### How to Report

Use one of the following methods (preferred in order):

1. Open a private security advisory via GitHub (if enabled), or  
2. Contact the project maintainers through the repository’s designated private contact method

When reporting, please include:
- a clear description of the issue
- steps to reproduce (if applicable)
- potential impact
- any suggested mitigations (optional)

---

## What to Expect

- Reports will be reviewed in good faith
- You will receive acknowledgment when feasible
- Fixes will be prioritized based on severity and risk
- Public disclosure will occur **only after** a fix or mitigation is available

Timelines are best-effort and depend on contributor availability.

---

## Responsible Disclosure Expectations

We ask that reporters:

- Give the maintainers reasonable time to investigate and respond
- Avoid public disclosure until a fix is released or mitigation is in place
- Avoid exploiting vulnerabilities beyond what is necessary to demonstrate impact
- Avoid accessing or modifying data beyond what is required for proof of concept

These expectations exist to protect users and contributors, not to limit good-faith research.

---

## Out of Scope

The following are generally considered out of scope:

- Issues in third-party services or dependencies not controlled by Ice Guard
- Social engineering attacks against contributors
- Denial-of-service attacks that rely solely on traffic volume
- Reports without sufficient detail to reproduce or assess impact

That said, if you are unsure whether something is in scope, **report it privately** and let maintainers decide.

---

## Security Philosophy

Ice Guard follows a **defense-in-depth** approach:

- Edge protection and rate limiting
- Strong authentication and authorization
- Least-privilege access to data
- Separation between public and administrative services
- Auditable, open-source security logic

Security through obscurity is explicitly avoided.

Because the project is fully open source, security depends on:
- careful design
- code review
- clear boundaries
- responsible behavior from contributors

---

## Forks and Independent Deployments

Ice Guard is open source and may be deployed independently by third parties.

This security policy applies only to deployments operated by the Ice Guard maintainers.  
Forks or derivative deployments are responsible for their own security practices.

---

## Final Note

Security issues in Ice Guard are not just bugs — they can affect people’s safety.

We appreciate responsible reporting and collaboration in keeping the project safe, trustworthy, and durable.
