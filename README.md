# The Difference Counseling Services

Static site for GitHub Pages. No build step.

- index.html: home
- about.html, specialties.html, supervision.html, khufu.html, fees.html, contact.html
- styles.css: shared styles for every page

The header and footer are repeated in each page, so a nav change has to be made in every page.

1. Photos are in images/ (anne.jpg, khufu.jpg, khufu-closeup.jpg). To swap one, replace the file and keep the same name.
2. Push this folder to a repo, then Settings > Pages > Deploy from branch > main / root.
3. To use thedifferencecounseling.com, add a CNAME file containing the domain and point the domain's DNS at GitHub Pages.

When you change styles.css, bump the ?v= number on the stylesheet link in every page (for example styles.css?v=20261112b to 20261113a). Browsers otherwise keep the old cached styles and pages can look broken.
