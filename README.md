# Sun Divide — Electronic Press Kit

Press-ready site for **Sun Divide** (Salt Lake City reggae/rock).

## Live site

`https://dbaileyfam.github.io/SunDivide/`

**One-time setup (required):** GitHub Pages is not active until you turn it on.

1. Open [SunDivide → Settings → Pages](https://github.com/Dbaileyfam/SunDivide/settings/pages)
2. Under **Build and deployment**, set **Source** to **GitHub Actions**
3. Save — the next push to `main` (or a manual workflow run) publishes the site

Until that step is done, the live URL returns 404 even though `main` has the latest files.

## Local preview

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy

This repo is set up for [GitHub Pages](https://pages.github.com/) from the `main` branch, root folder (`/index.html`).
