# TIDE Lab website

This repository contains the bilingual Quarto website for the Technology, Immigration, Demography and Education Research Lab in the [Department of Economics](https://iktisat.medeniyet.edu.tr/en) at [Istanbul Medeniyet University](https://www.medeniyet.edu.tr/en).

- English is published at the site root.
- Turkish is published under `/tr/`.
- Both versions share `theme.scss`.
- GitHub Actions renders and deploys both projects to GitHub Pages.

## Local rendering

```bash
quarto render
quarto render tr
```

The combined website is generated in `_site/`.

## Before public launch

Add approved short biographies, research interests, photographs, and personal links for the four members. Review the draft mission and research text in both languages before publishing.

In the GitHub repository settings, select **GitHub Actions** as the Pages deployment source.
