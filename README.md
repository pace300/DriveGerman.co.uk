# Drive German — Coming Soon (Static Page)

A single-file, mobile‑first “Coming Soon” page. No Wix, no builders. 
Just upload and done.

## How to use

1. Replace the placeholder image:
   - Put your image at `images/hero.jpg` (keep the same filename).
   - Recommended size: 2000–3000px width, JPG, ~400–800 KB.

2. (Optional) Change the overlay text:
   - Open `index.html` and edit the `<h1>` and `<p>` inside the `.caption` block.
   - If you want **only the image** with no text, delete the entire `<div class="caption">…</div>` block.

3. Deploy anywhere:
   - **Netlify:** Drag this whole folder into the Netlify dashboard.
   - **GitHub Pages:** Push to a repo and enable Pages (root).
   - **Any cPanel/host:** Upload the folder’s contents to your site’s root (where your `index.html` lives).
   - **Cloudflare Pages / Vercel:** Same—create a new project and point to this folder.

## Notes
- The image fills the screen and scales proportionally across desktop, tablet and mobile.
- No Javascript, zero dependencies.
- Lighthouse-friendly and fast.
