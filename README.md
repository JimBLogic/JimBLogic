# JimBLogic | Cybersecurity Portfolio

This repository is intended for the **JimBLogic GitHub Pages portfolio** at [https://jimblogic.github.io/](https://jimblogic.github.io/).

> Maintenance note: this branch does not currently contain the full production site tree from `JimBLogic/jimblogic.github.io` (`assets/`, `.github/workflows/`, `certificates.json`, dynamic project scripts, and translation files). Do not replace the production site with a minimal rewrite. Future website changes should be made incrementally on top of the full GitHub Pages source.

## Preservation Checklist for Site Changes

Before changing the website implementation, preserve these production features:

- EN / ES / CA language support.
- Dynamic certificate loading and certificate filters.
- Dynamic GitHub repository/project fetching.
- Existing CV link, avatar, contact details, location, and social links.
- Existing Content Security Policy, Open Graph metadata, Twitter Card metadata, canonical URL, and JSON-LD structured data.
- Existing GitHub Actions deployment/build workflow.
- Valid existing asset paths under `assets/`.
- Real repositories, certificates, homelab work, and other proof of work instead of placeholder projects.
- Bitcoin-orange visual identity.

## Portfolio Focus

The portfolio should present Jaime Ramsden de Frutos as a junior cybersecurity candidate with factual, evidence-based wording. Prioritize:

- Blue Team learning and SOC analysis fundamentals.
- Defensive Raspberry Pi homelab work.
- Linux, Docker, networking, monitoring, and logs.
- Ethical hacking labs and vulnerability analysis.
- AWS cloud foundations or AWS Cloud Practitioner candidate status, unless a passed certification is present.
- Digital forensics, OSINT, and incident response practice.

Keep the Sports Science degree under Education, but avoid making it the main focus of the portfolio.

## Certifications and Learning

- Blue Team Junior Analyst Pathway — Security Blue Team.
- Cybrary cybersecurity foundations coursework.
- IBM / Python learning.
- TryHackMe and Hack The Box learning records.
- UpgradeHub Cybersecurity Bootcamp certificate: [`Certificates/UpgradeHub Cert.pdf`](Certificates/UpgradeHub%20Cert.pdf).

## Contact

- Website: [https://jimblogic.github.io/](https://jimblogic.github.io/)
- LinkedIn: [https://www.linkedin.com/in/jimblogic/](https://www.linkedin.com/in/jimblogic/)
- Email: [jrf91@pm.me](mailto:jrf91@pm.me)

## Notes for Future Contributors

- Verify every internal link and asset path before opening a pull request.
- Test the site locally at desktop and mobile widths.
- Run available build, validation, and lint commands.
- If a real GitHub pull request is required, push the branch and create a draft PR against `main`; do not claim a PR exists without a real GitHub PR URL.
