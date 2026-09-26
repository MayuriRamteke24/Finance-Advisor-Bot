# Finance Advisor Bot

A modern finance dashboard concept and landing page for a personal finance assistant. This project is organized for local development and is ready to publish as a static site on GitHub Pages.

## Features

- Clean finance-themed landing page
- Responsive layout for desktop and mobile
- Clear value proposition for budgeting, savings, and smart planning
- Ready to deploy as a GitHub Pages site
- Flask app starter included for local development

## Project structure

- app.py — Flask application entry point
- templates/ — HTML templates for the app
- static/ — CSS and other static assets
- index.html — GitHub Pages homepage
- style.css — page styling used by the static site
- README.md — project overview and deployment guide

## Run locally

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

Then open http://localhost:5000

## Publish to GitHub Pages

This project is designed for GitHub Pages deployment as a static site. The root page is [index.html](index.html), which GitHub can serve directly without needing Python or Flask runtime.

1. Push this repository to GitHub.
2. Open the repository settings.
3. Navigate to Pages.
4. Set the source to the main branch and the root folder `/`.
5. Save the changes.

Your site will be published at:

https://<your-username>.github.io/<your-repository-name>/

## Notes

- The static homepage is GitHub Pages compatible.
- The Flask app in [app.py](app.py) is kept for local development and testing.
- A `.nojekyll` file is included so GitHub does not process the site with Jekyll and break the static layout.