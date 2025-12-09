
# Scalex Global LLP - Static Website
Modern, responsive multi-page static website for Scalex Global LLP (water treatment & scaling solutions).

## Structure
- index.html
- about.html
- Water Treatment.html
- Solar services.html
- contact.html
- .github/workflows/deploy.yml
- privacy and policy
- Terms of service


## Tech
- HTML + Tailwind CSS (CDN) — mobile-first responsive design.
- Mailto-based contact form (lightweight). using formspree Can be upgraded to netlify/ EmailJS.

## Deploy
This repo includes a GitHub Actions workflow (`.github/workflows/deploy.yml`) to automatically deploy the site to `gh-pages` branch using `peaceiris/actions-gh-pages`. To enable automatic publish:
1. Add this project files and commit to `main`.
2. The workflow uses the built-in `GITHUB_TOKEN` to push to `gh-pages` branch.

Note: If your repository has branch protections preventing the workflow's token from pushing, create a deploy key or use a personal access token in secrets.

