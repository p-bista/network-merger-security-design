## Overview
Secure network design and risk assessment for a fictional company merger — one financial services company, one healthcare-adjacent SaaS company — designing a zero trust network that passes PCI-DSS and GLBA requirements on a fixed $50,000 first-year budget.

**📖 Read the full case study:** https://p-bista.github.io/network-merger-security-design/

## Scenario
Company A (financial services, GLBA) and Company B (healthcare-adjacent SaaS, PCI-DSS) have merged and need a single secure network. Company A has redundancy and remote-access exposure problems; Company B has no MFA and several unpatched critical vulnerabilities. The combined executives want cloud scalability, zero trust, and a fixed $50,000 first-year budget.

## What's in this repo
- Risk analysis & vulnerability assessment (Parts A–B)
- Merged network topology diagram (Part C)
- OSI/TCP-IP layer mapping (Part D)
- Design rationale & budget justification (Part E)
- Zero trust & defense-in-depth principles applied (Part F)
- Regulatory compliance mapping — PCI-DSS, GLBA (Part G)
- Emerging threat analysis (Part H)
- Final recommendation & cost-benefit summary (Part I)

## Skills demonstrated
Risk assessment · network segmentation · zero trust architecture · regulatory compliance mapping · budget-constrained security design

## Files
- `Portfolio_Secure_Network_Design(1).html` — standalone single-file version of the case study
- `docs-site/` — Docusaurus source for the published case study site (deployed via GitHub Actions to GitHub Pages)
- `diagrams/` — network topology and supporting diagrams (also embedded in the docs site)

## Developing the docs site locally
```bash
cd docs-site
npm install
npm start
```
Pushing to `main` (with changes under `docs-site/`) automatically rebuilds and redeploys the site via `.github/workflows/deploy-docs.yml`.
