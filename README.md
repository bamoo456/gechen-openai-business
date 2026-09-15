# GECHEN AI — OpenAI Partner Application Landing Page

A lightweight static landing page for GECHEN AI's OpenAI Partner Network application and business AI practice.

## Purpose

The site is designed to clearly communicate the areas OpenAI highlights for prospective partners:

- Company capabilities
- Technical expertise
- Customer experience and delivery
- Ability to build, deploy, and support AI solutions

The copy intentionally states that the OpenAI Partner Network application is **in progress**. It does not claim an existing OpenAI partnership or use OpenAI branding in a way that could imply endorsement.

## Run locally

No build step is required.

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy with GitHub Pages

A GitHub Pages Actions workflow is included in `.github/workflows/pages.yml`.

In the repository:

1. Open **Settings → Pages**.
2. Set **Source** to **GitHub Actions**.
3. Push to `main` or manually run the `Deploy static site to Pages` workflow.

## Before submitting the partner application

Recommended finalization items:

- Connect a professional custom domain.
- Replace the GitHub contact CTA with a company-domain business email or contact form.
- Add the legal company name and registration details if appropriate.
- Add 1–3 real customer outcomes/case studies once they are publishable.
- Add a privacy policy if the site starts collecting leads.

## Official references

- OpenAI Partner Network: https://openai.com/business/partners/
- OpenAI Partner Portal: https://partners.openai.com/

## Trademark note

GECHEN AI is independent and is not currently an OpenAI partner. “OpenAI” and “ChatGPT” are trademarks of OpenAI.
