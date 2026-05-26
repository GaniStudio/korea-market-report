# GitHub Pages Upload Guide

Upload the contents of this folder to a GitHub repository root.

## Files To Upload

- `index.html`
- `morning.html`
- `evening.html`
- `weekly.html`
- `pdf/morning.pdf`
- `pdf/weekly.pdf`

Do not upload the full internal package.

## Method A: GitHub Web Upload

1. Create a new GitHub repository.
2. Upload every file and folder inside `public_github_pages_site`.
3. Go to repository `Settings`.
4. Open `Pages`.
5. Under `Build and deployment`, set:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. Wait until GitHub shows the Pages URL.

## Final Links

If the repository is named `korea-market-report`, the links usually look like:

```text
https://<github-user>.github.io/korea-market-report/
https://<github-user>.github.io/korea-market-report/morning.html
https://<github-user>.github.io/korea-market-report/evening.html
https://<github-user>.github.io/korea-market-report/weekly.html
https://<github-user>.github.io/korea-market-report/pdf/morning.pdf
https://<github-user>.github.io/korea-market-report/pdf/weekly.pdf
```

## PDF-Only Option

If you only want PDF sharing, upload only:

- `pdf/morning.pdf`
- `pdf/weekly.pdf`

But the recommended phone-reading flow is still `index.html` -> mobile HTML.
