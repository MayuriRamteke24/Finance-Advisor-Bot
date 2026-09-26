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

1. Push this repository to GitHub.
2. Open the repository settings.
3. Navigate to Pages.
4. Set the source to the main branch and root folder, or use the docs folder if you add one later.
5. Save the settings.

Your site will be published at:

https://<your-username>.github.io/<your-repository-name>/

## Notes

The project includes both a static GitHub Pages homepage and a Flask starter so it can be previewed locally before deployment.