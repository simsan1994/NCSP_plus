# Link Hub Website

A simple Linktree-style website you can publish publicly in minutes.

## What This Project Includes
- Single static page: [index.html](index.html)
- Styling and animations: [style.css](style.css)
- Local favicon: [favicon.svg](favicon.svg)
- Social preview image: [screenshot.png](screenshot.png)

## 1. Customize Your Links
Edit [index.html](index.html) and update:
- Page title and meta tags in the head section
- Profile image URL
- Username text
- Link URLs and labels
- Email address and website URL

## 2. Run Locally
You can open [index.html](index.html) directly, or use a local server.

If you use VS Code, click Go Live (Live Server extension).

## 3. Publish Publicly With GitHub Pages
Run these commands from this project folder:

```bash
git init
git add .
git commit -m "Initial public link hub"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

Then in GitHub:
1. Open your repository.
2. Go to Settings > Pages.
3. Under Build and deployment, set Source to Deploy from a branch.
4. Set Branch to main and folder to / (root).
5. Save.

Your site URL will be:
- https://YOUR_USERNAME.github.io/YOUR_REPO/

## 4. Update Social Preview Tags
After GitHub Pages is live, edit [index.html](index.html) and replace placeholder values:
- https://YOUR-USERNAME.github.io/YOUR-REPO/
- https://YOUR-USERNAME.github.io/YOUR-REPO/screenshot.png

Commit and push again:

```bash
git add index.html
git commit -m "Update production metadata"
git push
```

## 5. Republish After Edits
Any future update is:

```bash
git add .
git commit -m "Update links"
git push
```

GitHub Pages auto-deploys on push.

## Optional Next Steps
- Add a custom domain later using a CNAME file and DNS records.
- Add analytics (Plausible or Google Analytics).
- Self-host icon fonts for fewer third-party dependencies.
