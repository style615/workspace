# Suggested GitHub organization structure

GitHub organization profile: `.github/profile/README.md` in a public repository named `.github`.

## Public repositories (only when source publication is approved)
- `s615-sentinel` — Server monitoring and alerting
- `s615-hub` — WordPress ecosystem control center
- `s615-booking` — WordPress appointment and reservation management
- `s615-mail` — WordPress email and forms platform
- `s615-menu` — Restaurant menu management for WordPress
- `s615-analytics` — Privacy-focused analytics for WordPress
- `s615-translator` — WordPress multilingual content management
- `s615-shield` — WordPress security toolkit
- `s615-seo` — WordPress SEO toolkit
- `s615-reviews` — Reviews integration and display
- `s615-consent` — Consent management for WordPress
- `s615-fonts` — Local font and typography management
- `s615-cache` — WordPress performance toolkit
- `s615-users` — WordPress user management
- `s615-portfolio` — WordPress portfolio and gallery tools
- `s615-import-export` — WordPress content migration

## Internal or optional repositories
- `s615-storage`, `s615-cloud`, `s615-vault`, `s615-backup`, `s615-hosting` — publish only if suitable for open source
- `s615-docs` — product documentation
- `s615-infrastructure` — PRIVATE infrastructure-as-code (never publish secrets)
- `s615-brand` — brand assets with explicit reuse terms

## Repository README pattern
1. Product name and one-line value proposition
2. What it does / key features
3. Requirements and compatibility
4. Installation and configuration
5. Security and privacy considerations
6. Screenshots or usage examples
7. Documentation and support links
8. License and contribution rules

## Organization settings
- Add website `https://615.eu` and contact `info@615.eu`.
- Use clear topics: `wordpress`, `self-hosted`, `privacy`, `monitoring`, `cloud`, `web-development`.
- Pin only repositories that exist and are ready for visitors.
- Publish licenses only after choosing the actual terms; do not assume all S615 products are open source.
