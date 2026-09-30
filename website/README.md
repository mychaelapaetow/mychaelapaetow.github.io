# Personal website — setup

Files: `index.html` (all content), `style.css` (design), `cv.pdf`, `images/`, `papers/`.

## To finish
1. Add `images/headshot.jpg` (square crop works best) and `images/jmp.png` (a map or key figure).
2. Add `papers/paetow_jmp.pdf` when the draft is ready.
3. Replace the `#` links under Policy Work with the IGC URLs.
4. Uncomment the Google Scholar / LinkedIn lines in the header if you want them.
5. Replace `cv.pdf` whenever you update your CV (keep the same filename).

## Publish on GitHub Pages (free)
1. Create a GitHub account, then a new **public** repo named exactly `<your-username>.github.io`.
2. On the repo page: **Add file → Upload files**, drag in everything in this folder (keep the `images/` and `papers/` folders), commit.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After ~1 minute the site is live at `https://<your-username>.github.io`.
5. Optional custom domain (e.g. mychaelapaetow.com): buy it from any registrar, add it under Settings → Pages → Custom domain, and follow GitHub's DNS instructions.

To edit later: open `index.html` on GitHub, click the pencil icon, change text, commit. Each paper is one `<div class="paper">` block — copy/paste one to add another.
