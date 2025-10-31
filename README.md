# Github-Pages
# Enhanced User Experience — GitHub Pages demo

This repository contains a minimal GitHub Pages site with:

- `index.html` — home page (includes contact email).
- `404.html` — custom, helpful 404 page with suggestions and a link back to home.
- This README.

Contact email present on both pages: <!--email_off-->24f1002542@ds.study.iitm.ac.in<!--/email_off-->

How to publish
1. Create a repository on GitHub (for example: `your-repo`) or push these files to an existing repo.
2. Push the files to the repository root on the `main` branch.
3. In GitHub, go to Settings → Pages (or Repository Settings → Pages) and select "main" branch and root as the source.
4. Save. GitHub will provide the Pages URL (it usually appears a minute after build).

Example expected project Pages URL (after enabling Pages and publishing):
https://pranjal-amulani.github.io/your-repo/

Notes
- If you prefer a user site instead of a project site, name the repository `pranjal-amulani.github.io` and push to main; the site will be available at:
  https://pranjal-amulani.github.io/
- Both `index.html` and `404.html` must be at the repository root (not in /docs) if you choose root publishing.
- The 404 page is static HTML and works offline; adjust copy and styles as you like.

If you'd like, I can:
- create this repo and push these files for you (I can use your GitHub handle `Pranjal-Amulani`), or
- provide a small CI workflow that validates build and checks for the email presence on each push.

Tell me which option you prefer and I'll proceed.
