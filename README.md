# GitHub Pages Homepage (Jekyll)

This repository is ready to push to GitHub and deploy via GitHub Pages.

## Quick Start (GitHub Pages)
1. Create a new GitHub repo (e.g., `yourname.github.io`).
2. Upload all files in this folder to the repo root.
3. In GitHub: Settings → Pages → Build and deployment → Source: "Deploy from a branch"
   - Branch: `main` (or `master`), Folder: `/ (root)`
4. Your site will be available at `https://<username>.github.io/`.

## Customization
- Replace portrait image: `assets/images/avatar.jpg`
- Edit sidebar text in `_layouts/default.html`
- Edit page contents: `index.md`, `publications.md`, `talks.md`, `service.md`, `awards.md`

## Local Preview (optional)
If you have Ruby + Jekyll installed:
```bash
bundle exec jekyll serve
```
