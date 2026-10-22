# Abid Hasan Rafi — Personal SEO Website

A responsive, animated, single-page personal profile website built with plain HTML, CSS, and JavaScript. No build tools or paid hosting required.

## Included
- Responsive design for mobile, tablet, and desktop
- SEO-friendly HTML title, meta description, Open Graph tags, canonical URL placeholder
- `ProfilePage` / `Person` structured data
- `robots.txt` and `sitemap.xml`
- Accessible navigation, reduced-motion support, scroll progress, reveal animations
- Social links for Facebook and Instagram

## Before publishing — important
1. Search for `YOUR-GITHUB-USERNAME.github.io` in **index.html**, **robots.txt**, and **sitemap.xml** and replace it with your actual GitHub Pages URL (or custom domain). The canonical URL, Open Graph URL/image, structured data URL, robots sitemap URL, and sitemap URL must all match your live website.
2. The LinkedIn URL supplied for this project was the same Facebook URL. To avoid sending visitors to the wrong account, LinkedIn is shown as a placeholder in the page. Replace the placeholder in `index.html` with your actual LinkedIn profile URL and add it to the JSON-LD `sameAs` array.
3. If you want a real profile photo, add your image under `assets/` and update the hero/avatar design and structured data `image` field. No photo was supplied, so the site uses an AR monogram.
4. Review every sentence before publishing. Add only truthful experience, certifications, projects, measurable outcomes, and contact details. Do not invent client results or credentials.

## Publish on GitHub Pages
1. Download and extract the ZIP.
2. Create a GitHub repository, for example `abid-hasan-rafi`.
3. Upload all files and folders in this project to the repository root (so `index.html` is at the root).
4. In the repository, open **Settings → Pages**.
5. Under build/deployment, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
6. After GitHub Pages provides the public URL, update the placeholders above and commit the changes.
7. Open Google Search Console, add/verify your website, inspect the homepage URL, and submit `/sitemap.xml`.
8. Share your real website link on your public social profiles and relevant professional profiles.

## SEO notes
The website is structured around the name **Abid Hasan Rafi** and naturally describes the professional role and education. It does not use a meta keywords tag because Google says that tag is not used for web ranking. Avoid repeating the name unnaturally or publishing fabricated claims.

No website can guarantee Google indexing, a particular ranking, a knowledge panel, or a specific time to rank. Search visibility depends on crawlability, content quality, trust, external mentions/links, and many other factors. See Google's official guides:
- https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- https://developers.google.com/search/docs/appearance/structured-data/profile-page
