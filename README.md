# Awesome-Vendor-Risk-Management-VRM

## Top Vendor Risk Management (VRM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Third-Party Risk Assessment, Continuous Monitoring & Vendor Compliance*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Vendor Risk Management (VRM)**. These tools enable organizations to assess, monitor, and mitigate risks introduced by third-party vendors, suppliers, and service providers across the full vendor lifecycle—from onboarding and due diligence to continuous monitoring and offboarding.



**Examples** include ServiceNow Vendor Risk Management, OneTrust Third-Party Risk, Prevalent, BitSight, SecurityScorecard, Venminder, UpGuard, Panorays, Whistic, and ProcessUnity (the category leaders).



**Open-source emphasis**: This section is heavily expanded with active projects for self-hosted vendor risk assessment, questionnaire scoring, SBOM cross-referencing, and GRC automation — ideal for security teams, compliance officers, and organizations building sovereign third-party risk programs without per-vendor licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Vendor Risk Management](https://www.servicenow.com/)**  

  Enterprise VRM application integrated with the Now Platform, featuring vendor portfolio management with hierarchy support, automated assessment workflows, continuous monitoring, a self-service vendor portal, and dashboards for tiering and risk roll-up .



- **[OneTrust Third-Party Risk](https://www.onetrust.com/)**  

  TPRM platform with automated vendor onboarding, risk scoring, assessment libraries, continuous monitoring, and integration with privacy and security workflows; recognized as a Gartner Peer Insights Customers' Choice for IT VRM .



- **[Prevalent](https://www.prevalent.net/)**  

  TPRM platform (now part of Mitratech) with 200+ standardized risk assessment surveys, automated tiering, continuous dark web and cyber monitoring, built-in remediation guidance, and a Virtual Third-Party Risk Advisor trained on NIST, ISO, and SOC 2 frameworks .



- **[BitSight](https://www.bitsight.com/)**  

  Security ratings platform providing outside-in cyber risk intelligence for vendors and supply chains; ratings (250–900 scale) derived from 120+ external data sources covering compromised systems, diligence, user behavior, and breaches; used by 38% of Fortune 500 .



- **[SecurityScorecard](https://securityscorecard.com/)**  

  Security ratings and third-party risk platform with threat-informed findings presets, CVE-level targeted remediation requests, fourth-party concentration risk mapping, coordinated vendor response workflows, and auto-rescan verification of fixes .



- **[Venminder](https://www.venminder.com/)**  

  Third-party risk management platform combining software with expert-led assessments; features document storage, vendor onboarding, contract tracking, questionnaire management, and risk assessments performed by an in-house team of experts .



- **[UpGuard](https://www.upguard.com/)**  

  Vendor risk management platform with security ratings, questionnaire builder, risk and remediation workflows, vulnerability management, fourth-party visibility, and tiered pricing based on monitored vendor count (Standard: $1,750/mo for 50 vendors; Enterprise+: unlimited vendors) .



- **[Panorays](https://panorays.com/)**  

  Third-party security risk management platform with automated assessment, Business Snapshot supplier profiles, verified certification discovery, and AI-enhanced risk rating integration .



- **[Whistic](https://www.whistic.com/)**  

  Vendor security assessment platform with CrowdConfidence scoring, automated web source discovery for vendor trust centers, subprocessor tracking, and renewal cadence automation for periodic reassessments .



- **[ProcessUnity](https://www.processunity.com/)**  

  TPRM platform for large global enterprises featuring workflow automation, a Universal Data Core for TPRM data, Global Risk Exchange with 16,000+ completed assessments, and AI-powered teams for automated inherent risk calculations and policy reviews .



## Open-Source GitHub Projects



- **[Probo](https://github.com/getprobo/probo)**  

  Self-hostable GRC platform (ISC licensed) with full vendor/third-party risk coverage including vendor inventory, automated website risk assessment, DPA/BAA tracking, subprocessor discovery, and risk assessments; exposes 270+ MCP tools for AI agent automation, a `prb` CLI with 44+ command groups, and GraphQL API; Docker-deployable .



- **[VendorVet](https://github.com/cognis-digital/vendorvet)**  

  Self-hosted vendor risk questionnaire scorer and SBOM cross-referencer; scores completed security questionnaires on weighted controls, cross-references software bills-of-materials against a bundled 262k-record offline vulnerability database (OSV/GHSA), and outputs table/JSON/SARIF for CI gates; supports MCP for AI agent integration; available in Python, JavaScript, Go, and Rust ports .



- **[Vendor Risk Assessment Tool](https://github.com/chrisolowolafe-sys/vendor-risk-assessment-tool)**  

  Browser-based interactive vendor security risk assessment tool with 29 weighted questions across 6 domains (Data Security, Access Controls, Incident Response, Business Continuity, Compliance, Sub-processors); maps findings to ISO 27001:2022, NIST CSF 2.0, SOC 2, GDPR, and PIPEDA; generates risk-rated reports with recommended treatments; all data stays local in the browser .



### Additional Strong Open-Source Options



- **OpenGRC** — Community projects for self-hosted governance, risk, and compliance management that can be adapted for vendor risk workflows.

- **SBOM analysis tools** (e.g., Dependency-Track, OSV-Scanner) — For supply chain risk assessment when evaluating software vendors.

- **Questionnaire automation scripts** — Community pipelines combining YAML/JSON questionnaire definitions with scoring engines for repeatable vendor assessments.



**Frameworks for building custom systems**: Combine **Probo** for full GRC lifecycle management with vendor risk modules, **VendorVet** for questionnaire scoring and SBOM-based software supply chain risk, and **Vendor Risk Assessment Tool** for lightweight browser-based assessments in a fully self-hosted vendor risk management pipeline with CI/CD integration for procurement gates.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- VRM platforms handling vendor and contractual data must comply with applicable regulations (GDPR, SOC 2, industry-specific requirements).

- Self-hosted open-source solutions require proper security hardening, regular vulnerability database updates, and integration with existing procurement and GRC workflows.

- Verify license terms for commercial use; Probo uses ISC, VendorVet is source-available (not OSI-approved), and the Vendor Risk Assessment Tool is browser-based with no server component.



---



**Made for security teams, compliance officers, procurement managers, and third-party risk practitioners.**  

Let's make vendor risk management more open, verifiable, and automated.
