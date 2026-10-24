# YOEI — Artist Workroom

A private-progress, public-code static website for YOEI's monthly artist-development plan.

## Publish with GitHub Pages

1. Create a **public** GitHub repository named `yoei-workroom` (or a name of your choice).
2. Upload the files from this folder to the repository **root** (`index.html`, `.nojekyll`, and `README.md`), and commit to `main`.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
4. Once published, click **Visit site** in Pages settings. The standard project URL looks like `https://YOUR-USERNAME.github.io/yoei-workroom/` (replace the username; don't assume this exact URL until GitHub confirms publication).

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Data and privacy

- **The website files will be public** if you publish via a public GitHub repository.
- Your checkboxes and personal notes are saved in **your browser's local storage**, not in the public repository. They do **not** automatically sync between browsers or devices.
- **Existing progress doesn't transfer automatically** when switching from a downloaded HTML file to the hosted page. Open the original HTML, click **Export backup**, then on the hosted site choose **Import backup**.
- Export backups regularly. Clearing site data or switching browsers may erase locally saved progress.
- GitHub Pages is static hosting. To get secure login and cloud sync across devices in the future, the app would need additional development and a database or other suitable backend.

## Maintenance

The site is self-contained: no build tools, external assets, or dependencies are required. Updating `index.html` on the publishing branch updates the website automatically through GitHub Pages.
