# COMPASS Documentation

Official documentation site for **COMPASS** — the Crew Operations Management & Personnel Assignment Support System for STARFLEET International.

Live site: https://dwizard0.github.io/compass-docs/

## Contributing

Documentation is written in Markdown and built with MkDocs Material.

### Local Development

```
pip install mkdocs-material
mkdocs serve
```

Then open http://localhost:8000.

### Adding Pages

1. Create a .md file in the appropriate docs/ subdirectory
2. Add it to the nav section of mkdocs.yml
3. Commit and push - GitHub Actions deploys automatically

## Deployment

Pushes to main automatically trigger a GitHub Actions build and deploy to GitHub Pages.
