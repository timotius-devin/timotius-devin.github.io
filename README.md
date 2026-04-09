# Timotius Devin

Personal website built with GitHub Pages.

**Live:** https://timotiusdevin.github.io

## About

This is a minimal personal site to share:

- Work in AI product and enterprise deployments
- Selected projects across LLMs, OCR, and data workflows
- Short readings and notes on AI, product, and business

The goal is clarity over complexity, and substance over design.

## Structure

```
.
├── index.html          # Homepage
├── styles.css          # Shared styles
└── readings/
    ├── index.html      # List of all readings
    ├── first-post.html
    └── second-post.html
```

Each reading is a standalone page, simple and shareable.

## Philosophy

- Minimal and fast, no frameworks
- Static HTML, easy to maintain
- Writing-first, not design-first
- Treat content as versioned thinking

## How to run locally

### Option 1: Open directly
Open `index.html` in your browser.

### Option 2: Run a local server (recommended)

```bash
python3 -m http.server 8000
```

Then open:

```
http://localhost:8000
```

## Deployment

This site is deployed using GitHub Pages.

- Repository name must be: `timotiusdevin.github.io`
- Branch: `main`
- Folder: `/ (root)`

Once pushed, changes are automatically deployed.

## Writing

New readings go under:

```
/readings/
```

Steps:
1. Create a new `.html` file
2. Add it to `/readings/index.html`
3. Commit and push

## Future Improvements (optional)

- Markdown support (Jekyll or static generator)
- Tagging / categorisation
- Analytics (Plausible or similar)
