# pune-airport-plot

One-page sale site for a 2,000 sq ft corner plot in Dhanori, Pune.
Aimed at NRI buyers in the US. Hosted free on GitHub Pages.

## Before you publish
1. Open `index.html`, scroll to the `CONFIG` block near the bottom, and fill in:
   WhatsApp number, email, price, USD rate, distances.
2. Photos (`images/1.jpeg` … `5.jpeg`) and the video (`images/Vid.mp4`) are listed
   in `CONFIG.photos` / `CONFIG.video`. The first photo in the list is the large one.
   Keep each photo under ~500 KB.
3. `images/3.jpeg` is used as the WhatsApp link preview (`og:image`).

## Deploy
```bash
git init && git add . && git commit -m "Pune airport plot site"
git branch -M main
git remote add origin https://github.com/ashish051321/pune-airport-plot.git
git push -u origin main
```
Then on GitHub: Settings → Pages → Source: `main` / root → Save.
Live at `https://ashish051321.github.io/pune-airport-plot/`
