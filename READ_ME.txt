LUXBUILD WEBSITE

Upload the contents of this folder to Netlify.

Main pages:
- index.html = home page
- work.html = gallery page
- admin.html = edit gallery page
- gallery-data.js = gallery photo/category data

How to edit photos on the site:
1. Open luxbuild.it.com/admin.html
2. Choose a category.
3. Upload photos, paste image URLs, drag photos to reorder, or move photos between categories.
4. Click Export gallery-data.js.
5. Replace the old gallery-data.js in this website folder with the exported one.
6. Zip the folder and deploy to Netlify again.

Important: Because this is a static Netlify website, changes made in admin.html are saved in your browser first. To make them visible for everyone, you must export gallery-data.js and redeploy.
