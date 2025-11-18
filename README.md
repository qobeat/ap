# AP Bio Unit 7 Quiz

This repository hosts the **AP Biology Unit 7: Natural Selection Practice Quiz** as a single static `index.html`. You can view it locally or host it on GitHub Pages.

## Viewing locally

1. Clone the repository:
   ```bash
   git clone https://github.com/qobeat/ap.git
   cd ap
   ```
2. Start a simple HTTP server (any static server works):
   ```bash
   python -m http.server 8000
   ```
3. Visit <http://localhost:8000> and load `index.html`.

## Publishing to GitHub Pages

1. Push the repository (with the `index.html`) to GitHub:
   ```bash
   git add index.html README.md
   git commit -m "Add AP Bio quiz"
   git push origin main
   ```
2. In the GitHub repository settings (`https://github.com/qobeat/ap/settings/pages`):
   - Under **Build and deployment**, choose **Deploy from a branch**.
   - Select the **main** branch and the **/ (root)** folder, then click **Save**.
3. GitHub Pages will publish the site. Your quiz will be live at `https://qobeat.github.io/ap/` once the deployment finishes.

> Tip: Any time you change `index.html`, re-run `git add`, `git commit`, and `git push` to update the published site automatically.
