# Finwin Edu Campus Website

Static HTML website for Finwin Edu Campus.

## Pages

- `index.html` redirects to `home.html` for GitHub Pages compatibility.
- `home.html` is the main website landing page.
- Other pages are plain HTML files with assets stored in `ss/` and `FINWIN courses/`.

## Publish on GitHub Pages

1. Upload this folder to a GitHub repository.
2. In GitHub, open **Settings > Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Select the branch, usually `main`, and the root folder `/`.
5. Save. GitHub will provide the live website URL after deployment.

## Command-Line Upload

```bash
git add .
git commit -m "Initial website upload"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

## Local Preview

Open `index.html` or `home.html` in a browser. No build step is required.
