# Gautam Gupta — portfolio

Single-page static site for GitHub Pages. Plain HTML and CSS. No build step.

Intended public URL: https://guptagautam768.github.io

## Publish

These files belong in a **new** public repository named `guptagautam768.github.io` on the `guptagautam768` account. GitHub serves a repository with that name from the repository root.

```bash
git init
git checkout -b main
git add .
git commit -m "Add personal portfolio site"
git remote add origin https://github.com/guptagautam768/guptagautam768.github.io.git
git push -u origin main
```

Create the empty public repository first (GitHub → New repository → name `guptagautam768.github.io`, no README so this history can push cleanly). User sites publish from the default branch automatically. After a minute or two, https://guptagautam768.github.io should return the site.

Then set the GitHub profile website to `https://guptagautam768.github.io` (Settings → Public profile → Website, or `gh api -X PATCH /user -f blog=https://guptagautam768.github.io`).

## Files

- `index.html` — the page
- `styles.css` — layout, dark and light themes
- `favicon.svg`
- `.nojekyll` — skip Jekyll processing
