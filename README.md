# The Difference Counseling Services

Static site for GitHub Pages. No build step.

- index.html: home
- approach.html, about.html, specialties.html, supervision.html, khufu.html, fees.html, contact.html
- styles.css: shared styles for every page

The header and footer are repeated in each page, so a nav change has to be made in all eight files.

1. Photos are in images/ (anne.jpg, khufu.jpg, khufu-closeup.jpg). To swap one, replace the file and keep the same name.
2. Push this folder to a repo, then Settings > Pages > Deploy from branch > main / root.
3. To use thedifferencecounseling.com, add a CNAME file containing the domain and point the domain's DNS at GitHub Pages.
