# gotitanwash.com

Website for Titan Wash Exterior Cleaning (Miami-Dade & Broward).

Static site, no build step: `index.html` plus images. Hosted on Vercel; every push to `main` redeploys.

## Adding before/after photos
Put photos in `work/` and replace a placeholder `<figure class="ba">` in the "Our Work" section of `index.html` with:

```html
<figure class="ba photo"><img src="/work/driveway-kendall.jpg" alt="Driveway before and after in Kendall" loading="lazy"><figcaption>Driveway · Kendall</figcaption></figure>
```
