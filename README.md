# cultureofcivility.org – static mirror

Static copy of the 10 published WordPress pages plus all images, CSS, JS and fonts.

## Deploy to Vercel
- Dashboard: New Project -> import this folder (Framework preset: "Other", no build command, output dir = root).
- CLI: `npm i -g vercel` then run `vercel --prod` inside this folder.

## Limitations (WordPress server features)
- The Elementor contact/popup forms post to `/wp-admin/admin-ajax.php`, which won't exist on Vercel. Point them at a form service (Formspree, Vercel function, etc.).
- The iubenda cookie banner is configured for the cultureofcivility.org domain.
