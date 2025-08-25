
# Sample API Documentation

This project hosts the documentation for the Sample API, a simple Express-based API deployed at [https://sample-api-pzv2.onrender.com](https://sample-api-pzv2.onrender.com). The documentation is written in Markdown, organized locally in the `docs/` directory, and managed using Git. It is built into a static site using [MkDocs](https://www.mkdocs.org/) with the Material theme and automatically deployed to GitHub Pages using [GitHub Actions](https://github.com/features/actions).

The published documentation is available at: [https://sumanlatamalik.github.io/sample-api-docs/](https://sumanlatamalik.github.io/sample-api-docs/)

## Structure
- **Home**: Overview of the Sample API.
- **API Endpoints**: Details on available endpoints (e.g., `GET /`, `GET /users`).
- **Setup Guide**: Instructions for setting up the API locally.
- **Testing**: Guide for testing the API with Jest.
- **Deployment**: Steps to deploy the API on Render.

## How to Contribute
1. Clone the repository:
   ```bash
   git clone https://github.com/sumanlatamalik/sample-api-docs.git
   cd sample-api-docs
   ```
2. Install MkDocs:
   ```bash
   pip install mkdocs mkdocs-material
   ```
3. Edit Markdown files in the `docs/` directory.
4. Test locally:
   ```bash
   mkdocs serve
   ```
   - Open `http://localhost:8000`.
5. Commit and push changes:
   ```bash
   git add .
   git commit -m "Update documentation"
   git push
   ```
6. GitHub Actions automatically builds and deploys to GitHub Pages.

## License
[MIT License](LICENSE)
```

### Site Map
site_name: Sample API Docs
site_url: https://sumanlatamalik.github.io/sample-api-docs/
docs_dir: docs
site_dir: site
theme:
  name: material
nav:
  - Home: index.md
  - API Endpoints:
      - Overview: endpoints/index.md
      - Users: endpoints/users.md
  - Setup Guide: setup/index.md
  - Testing: testing/index.md
  - Deployment: deployment/index.md
