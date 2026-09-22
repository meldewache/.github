# meldewache

CRA reporting duty, watched daily.

The EU Cyber Resilience Act (Regulation (EU) 2024/2847) applies to anyone who commercially offers a product with digital elements in the EU. There is no company size exemption. Since 11 September 2026 manufacturers have to report actively exploited vulnerabilities within 24 hours (Art. 14). From 11 December 2027 the full obligations apply: SBOM, vulnerability handling, security updates, conformity declaration, CE marking (Art. 13, Annex I).

Most one to twenty person software and hardware vendors have no process for this. meldewache is being built to give them one.

## What we are building

| | |
|---|---|
| **SBOM** | CycloneDX or SPDX generated from your GitHub or GitLab repository, aligned with BSI TR-03183-2. |
| **Watch** | Daily comparison against CISA KEV, NVD, OSV and GitHub Advisories. Alerts only on active exploitation, not on CVE noise. |
| **Report** | Pre-filled drafts for the 24h early warning and the 72h notification, routed to the CSIRT of your country, with a deadline timer. |
| **Evidence** | Audit trail plus templates for technical documentation and the EU declaration of conformity (Annex VII, V) as PDF. |

Setting up a reporting process once is the first step. meldewache is what runs every day after that.

## Who it is for

Solo and small vendors: app developers, plugin authors (WordPress, Shopify, Atlassian, JetBrains), indie desktop tools, small IoT manufacturers, machine builders shipping control software, commercial open source maintainers.

The reason to care is rarely the fine. It is staying in the store, staying supplyable for business customers, and knowing within 24 hours when one of your dependencies is under active attack.

## Status

Early. There is a free two minute scope check that tells you whether your product is in scope, and a waiting list.

- Scope check and waiting list: https://meldewache.pages.dev
- Contact: mail@software-mit-pascal.de
- Security contact: security@software-mit-pascal.de

## Sources

- [Regulation (EU) 2024/2847 on EUR-Lex](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
- [European Commission: Cyber Resilience Act](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)

This is not legal advice. Edge cases belong with a lawyer or your national market surveillance authority.

meldewache is an offering of Software mit Pascal, owner Pascal Nehlsen, Remscheid, Germany.
