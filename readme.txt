# Stable Table Website (Netlify-ready)

## Quick Deploy (Drag & Drop)
1) Go to https://app.netlify.com and log in.
2) Click your site **stable-table.org**.
3) Open the **Deploys** tab ► click **Deploy a site** (or **Upload a deploy**).
4) Drag & drop the ZIP file from this folder: `stable-table-site.zip`.
5) Netlify will build instantly. Refresh your site to see changes.

## Edit Text/Images
- Open `index.html` in any editor (Notepad works).
- Change text (mission, services, phone, etc.).
- Put your photos in `/assets` and update the `<img src="assets/…">` paths.
- Re-zip and redeploy to Netlify as above.

## Contact Form (Netlify Forms)
- The contact form is ready. Submissions will show in **Forms** in your Netlify dashboard.
- You can set email notifications in Netlify ► **Forms** ► **Form notifications**.

## Notes
- Tailwind CSS is loaded via CDN (no build step needed).
- This is a single-file site for simplicity. You can grow it into multiple pages later.
