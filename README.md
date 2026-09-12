# Cinema Atlas — GitHub Pages Ready

This folder is ready to publish as a static website with GitHub Pages.

## Before publishing

Replace `YOURUSERNAME` in these three places with your GitHub username:

- `index.html` — canonical URL, Open Graph URL and structured-data URL
- `robots.txt` — sitemap URL
- `sitemap.xml` — site URL

Example: if your GitHub username is `alex123`, the site URL is:

`https://alex123.github.io/cinema-atlas/`

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `cinema-atlas`.
2. Upload every file in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to deploy the site.
7. Open `https://YOURUSERNAME.github.io/cinema-atlas/`.

## Google indexing

After the site is live, add the URL to Google Search Console and submit:

`https://YOURUSERNAME.github.io/cinema-atlas/sitemap.xml`

Google decides when and where the site appears in search results; indexing and ranking are not guaranteed immediately.

## Notes

- Movie posters load dynamically from Wikimedia page thumbnails, so an internet connection is required for poster images.
- The IMDb Top 250 section links to the official live IMDb chart and displays a local selection.
- This is a static site, so it works with GitHub Pages without a server.
