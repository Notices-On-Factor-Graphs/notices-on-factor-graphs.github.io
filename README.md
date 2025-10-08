# Notices on Factor Graphs — Website

A very simple GitHub Pages site (Jekyll + Markdown) for an online colloquium on factor graphs.

## Structure
- `_config.yml` — site config (Minima theme + top navigation)
- `index.md` — homepage
- `agenda.md` — upcoming meetings (online colloquium)
- `materials.md` — curated resources (papers, tutorials, software, drawing templates)
- `contact.md` — how to get in touch

## How to publish on GitHub Pages
1. Create a new public repository on GitHub (e.g., `notices-on-factor-graphs`).
2. Upload (or push) the contents of this folder to the default branch.
3. Go to **Settings → Pages** and enable GitHub Pages.  
   - **Source:** Deploy from a branch (default) or GitHub Actions (either works for Minima).
4. Wait for the site to build and publish. Your site will be live at the URL GitHub provides.

## Editing content
All pages are Markdown. Just edit `agenda.md`, `materials.md`, or `contact.md` and commit. The site will rebuild automatically.

## Optional niceties
- Add a `CNAME` file if you plan to use a custom domain.
- Add a `LICENSE` if you want to specify reuse terms for the site’s content.
