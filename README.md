# LC Attendance Analytics Report

This folder contains a static HTML report generated from anonymized LC attendance data.

## Files

- `index.html` — main report page
- `*.png` — charts and visualizations

## Deployment to GitHub Pages

1. Create a new GitHub repository (e.g., `lc-attendance-report`).
2. Run the deployment script:
   ```bash
   ./deploy.sh YOUR_GITHUB_USERNAME REPO_NAME
   ```
3. Or deploy manually:
   ```bash
   cd docs
   git init
   git add .
   git commit -m "LC attendance analytics report"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
   git push -u origin main
   ```
4. Go to repo Settings → Pages → Source → Deploy from a branch → main / (root).
5. Your site will be available at `https://YOUR_USERNAME.github.io/REPO_NAME/`.

## Privacy

All names and identifiers have been anonymized. Do not commit raw data or mapping files.
