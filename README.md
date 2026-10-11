# Dhananjay Tripathi — Portfolio

A static, single-page portfolio built from my resume, ready to host on **GitHub Pages**.

Target roles: **Systems Administrator · Cloud Engineer · DevOps Engineer**

## Files

| File | Purpose |
|------|---------|
| `index.html` | The portfolio page |
| `style.css` | Styling (responsive, dark theme) |
| `resume.pdf` | Downloadable ATS-friendly resume |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (no Jekyll processing) |

## Preview locally

Just double-click `index.html`, or run a local server:

```powershell
python -m http.server 8080
# then open http://localhost:8080
```

## Deploy to GitHub Pages

### Option A — User site (recommended): `https://<username>.github.io`

1. Create a new **public** repo on GitHub named exactly:
   `dhananjay-tripathi.github.io`
2. From this `portfolio` folder, push the files:

```powershell
git init
git add .
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/dhananjay-tripathi/dhananjay-tripathi.github.io.git
git push -u origin main
```

3. Your site is live at **https://dhananjay-tripathi.github.io** within a minute or two.

### Option B — Project site: `https://<username>.github.io/portfolio`

1. Create any public repo (e.g. `portfolio`) and push these files to `main`.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source = Deploy from a branch**,
   **Branch = main**, **Folder = / (root)**, then **Save**.
4. Site goes live at `https://<username>.github.io/portfolio/`.

## Customize

- **Colors:** edit the CSS variables at the top of `style.css` (`--accent`, `--accent-2`, `--bg`).
- **Content:** edit the text inside `index.html`.
- **Resume:** replace `resume.pdf` with an updated copy (keep the same filename).
