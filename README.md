# pune-airport-plot

One-page sale site for a 2,000 sq ft corner plot in Dhanori, Pune.
Aimed at buyers in India and abroad (NRIs, OCI card holders). Hosted free on GitHub Pages.

Live at `https://ashish051321.github.io/pune-airport-plot/`

## Editing the content
Open `index.html` and scroll to the `CONFIG` block near the bottom. It holds:
WhatsApp number, email, price, USD rate, photos, video, distances and the documents list.

- Photos (`images/1.jpeg` … `5.jpeg`) and the video (`images/Vid.mp4`) are listed
  in `CONFIG.photos` / `CONFIG.video`. The first photo in the list is the large one.
  Keep each photo under ~500 KB. Filenames are case-sensitive on GitHub Pages.
- `images/3.jpeg` is used as the WhatsApp link preview (`og:image` in the `<head>`).

## Publishing (GitHub Pages)
One-time setup, on GitHub: **Settings → Pages → Build and deployment →
Source: Deploy from a branch → Branch: `master`, folder `/ (root)` → Save.**
The repo must be public on a free account. The first deploy shows up under the
**Actions** tab and takes 1–2 minutes.

## Updating the live site
```bash
git add .
git commit -m "Describe the change"
git push origin master
```
The site refreshes within a minute or two. If WhatsApp shows an old link preview,
share the link with `?v=2` (any new number) on the end to force a fresh one.
