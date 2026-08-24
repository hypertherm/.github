# Security Policy
Hypertherm Associates, Inc. ("Hypertherm") is committed to the security of its products, software, and connected systems. This document describes how to report vulnerabilities and severe cybersecurity incidents to Hypertherm's Product Security Incident Response Team (PSIRT), and how Hypertherm handles those reports.

This policy applies to all Hypertherm software products and repositories unless a repository contains its own SECURITY.md with product-specific instructions.

# Reporting a Vulnerability [GM1.1][MM1.2]or Severe Cybersecurity Incident

If you have discovered a security vulnerability or are aware of a severe cybersecurity incident affecting a Hypertherm product, please report it through our PSIRT portal:

**Primary reporting channel:**

🔗 https://psirt.hypertherm.com

**Email (fallback):**

📧 psirt@hypertherm.com

## Important: Do not use public GitHub channels

> [!important]
> Please do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.

Do not disclose incident details until Hypertherm has investigated and resolved the issue.

Keeping reports private protects all customers until they can deploy patches or mitigations.

## What to Include in Your Report

To help us investigate and respond effectively, please provide as much of the following as possible:

*	Affected product name and version
*	Repository or component (if known)
*	Description of the vulnerability or incident
*	Steps to reproduce the issue
*	Whether the vulnerability is being actively exploited
*	Any supporting evidence (logs, screenshots, proof-of-concept)
*	Your contact information for follow-up

# Severity Classification

Hypertherm PSIRT classifies reported issues using a risk-based approach informed by the Common Vulnerability Scoring System (CVSS). Reports are triaged based on:

*	Severity and exploitability of the vulnerability
*	Whether the vulnerability is actively exploited
*	Customer and product impact
*	Regulatory and compliance obligations

## Definitions

| Term | Definition |
|---|---|
|Vulnerability| A weakness in a product that could be exploited to compromise security, integrity, or availability.|
|Actively exploited vulnerability| A vulnerability for which reliable evidence exists that it has been exploited by a malicious actor in the wild.|
|Severe cybersecurity incident| An incident that compromises the availability, integrity, or confidentiality of a product with digital elements, or of the data the product processes, in a manner that has significant impact on users or other persons.|

## Response Timelines

Hypertherm PSIRT follows these response expectations:

| Stage | Timeline |
|---|---|
| Acknowledgement of report | Within 5 business days |
| Final report (remediation details, root cause, corrective measures) | As required by regulation and complexity |

Actual timelines may vary depending on validation, technical investigation, remediation complexity, and coordination with affected parties. Hypertherm will keep reporters informed of progress where appropriate.

## Coordinated Vulnerability Disclosure

Hypertherm follows a coordinated vulnerability disclosure process:

*	**Disclosure window**: Hypertherm requests a coordinated disclosure period of up to 90 days from the date a valid vulnerability is confirmed, to allow time for investigation, remediation, and customer notification.
*	**Collaboration**: Hypertherm PSIRT will work with reporters in good faith throughout the disclosure process.
*	**Security advisories**: Hypertherm publishes security advisories when patches, mitigations, or risk information are available for customers.
*	**Researcher acknowledgement**: With the reporter's consent, Hypertherm will credit security researchers who responsibly disclose vulnerabilities.

## Security Updates and Advisories

Hypertherm communicates security updates, patches, and mitigations through:

*	Product-specific security advisories
*	Direct customer notifications where applicable
*	Product release notes and documentation

Customers and users should apply security updates promptly and follow any mitigation guidance provided by Hypertherm.

For information about product support timelines, including end-of-support and end-of-life dates, refer to Hypertherm's product lifecycle documentation.

## Contact

| Channel | Details |
| --- | --- |
| PSIRT Portal | https://psirt.hypertherm.com |
| Email | psirt@hypertherm.com |
| Preferred language | English |
| Response hours | Monday–Friday, business hours (Eastern Time) |

For severe cybersecurity incidents, please submit your report through the PSIRT portal as soon as possible, regardless of business hours.

---

Thank you for helping protect Hypertherm customers and products. Responsible security research makes our products safer for everyone.
