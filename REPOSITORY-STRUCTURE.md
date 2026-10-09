# Style 615 — GitHub Organization Structure

**Private Development · Proprietary Software · Public Product Information**

This document proposes a private-first GitHub organization for Style 615 (S615). Repository names below are recommendations, not a claim that these repositories already exist.

## Public — documentation only

| Repository | Purpose |
| --- | --- |
| `.github` | Organization profile |
| `s615-ecosystem` | Product catalog and descriptions |
| `s615-docs` | Approved public guides and FAQs |
| `s615-portfolio` | Approved client case studies (not the Portfolio plugin source) |

Public repositories contain **no source code, plugin ZIPs, credentials, customer data, internal network diagrams, or deployment secrets**.

## Private — WordPress plugins

`s615-hub`, `s615-booking`, `s615-mail`, `s615-menu`, `s615-analytics`, `s615-translator`, `s615-shield`, `s615-seo`, `s615-reviews`, `s615-consent`, `s615-fonts`, `s615-cache`, `s615-users`, `s615-portfolio-plugin`, `s615-import-export`.

## Private — cloud and operations

`s615-sentinel`, `s615-storage`, `s615-cloud`, `s615-vault`, `s615-backup`, `s615-hosting`, `s615-infrastructure`.

Although Sentinel has been described on the website as open-source, keep its source private unless and until publication is explicitly approved. If an existing public repository already exists, changing it to private does **not** revoke previous clones or copies.

## Private repository README checklist

1. Product purpose and capabilities
2. Requirements and supported versions
3. Internal setup and configuration
4. Architecture and dependencies
5. Security, privacy and data handling
6. Testing and release procedure
7. Changelog and ownership
8. Distribution and licensing status

Suggested heading: **Internal software — not for public distribution**. This is an internal policy statement, not a substitute for legal licensing terms.

## Development workflow

Use a private GitHub Project named **S615 Development** with `Backlog → Planned → In Progress → Testing → Completed`. Use Issues, protected branches, pull requests, and private CI workflows. Keep secrets in a dedicated secrets manager or GitHub encrypted secrets, never in Git history.

## Organization security

- Website: https://615.eu · Contact: info@615.eu
- Default new code repositories to **Private**
- Limit who can create public repositories or change visibility
- Enable 2FA, least-privilege roles, branch protection and secret scanning where available
- Review access and public repository contents before each release
- Do not add GPL, MIT, or another license by default without reviewing applicable obligations, including those arising from WordPress/GPL components

## Distribution decision

No public source releases, free downloads, or blanket open-source commitments are planned at present. Decisions about selling, licensing, publishing, or distributing each product will be made separately.

© 2026 Style 615 · https://615.eu
