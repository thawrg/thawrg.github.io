# GitHub Pages starter

Plain HTML/CSS. No WordPress, no build step.

## Publish

1. Create a GitHub account if you do not have one.
2. New repository.
   - User site (nicest URL): name it **exactly** `YOURUSERNAME.github.io`
   - Or any name, e.g. `site` → URL will be `YOURUSERNAME.github.io/site/`
3. Upload these files to the repo (`index.html` must be at the root).
4. Repo → **Settings** → **Pages**.
5. Source: **Deploy from a branch**.
6. Branch: `main` (or `master`), folder: `/ (root)`.
7. Save. Wait 1–2 minutes.
8. Open `https://YOURUSERNAME.github.io` (or `/repo-name/`).

## Custom domain later

Settings → Pages → Custom domain. Add `www.yourdomain.com`, then at your registrar:

- `www` CNAME → `YOURUSERNAME.github.io`
- apex A records that GitHub shows in that same Pages screen

Do not change Google Workspace MX / SPF / DKIM records.

## Edit locally

Open `index.html` in a browser. Change “Your Name” and the copy, commit, push.
