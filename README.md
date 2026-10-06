# Wirebench — landing site

Static landing site (plain HTML + CSS, no build step) for Wirebench workflow templates for n8n.
Served by GitHub Pages from `main` / root.

This repository contains **only** marketing pages and legal pages. No paid deliverables
(workflow files, setup guides) are stored here.

## Placeholders to replace before launch

- Support email: replace every `SUPPORT_EMAIL_PLACEHOLDER`
  `grep -rl SUPPORT_EMAIL_PLACEHOLDER --include=*.html . | xargs sed -i 's/SUPPORT_EMAIL_PLACEHOLDER/support@example.com/g'`
- Checkout links: replace `#buy-PLACEHOLDER-uk-tender-alerts`, `#buy-PLACEHOLDER-domain-lead-enrichment`,
  `#buy-PLACEHOLDER-bundle` in `index.html` with the Creem checkout URLs.
