# Sagaya Sree Z — Portfolio website

A responsive, single-page professional portfolio built with plain HTML, CSS and JavaScript.

## Files
- `index.html` — page content and metadata
- `assets/style.css` — responsive dark theme
- `assets/script.js` — mobile navigation and current year
- `Sagaya_Sree_Z_Resume.docx` — resume download
- `CNAME` — custom domain placeholder (`sagayasree.com`)

## Publish free with GitHub Pages
1. Create a GitHub account (if needed) and a **public** repository, for example `sagaya-portfolio`.
2. Upload all files and folders in this package to the repository root. Keep the `assets` folder structure.
3. Open **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. In the custom domain field, enter `sagayasree.com` and save. GitHub may create/update the `CNAME` file.
5. At your domain registrar, add these DNS records:
   - A records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - CNAME for `www`: `YOUR-GITHUB-USERNAME.github.io`
6. Wait for DNS to propagate. Return to **Settings → Pages** and enable **Enforce HTTPS** once available.

## Before publishing
- Confirm the domain purchase and replace the GitHub username in the DNS CNAME record.
- Add her actual LinkedIn profile URL in `index.html` (currently a generic LinkedIn link).
- Review the public contact email and resume download. The supplied resume has a masked phone number, so no phone number is shown.
- Confirm that the case-study summaries are appropriate for public sharing. Do not add confidential internal data, screenshots or customer information.
- The site currently uses Google Fonts from a CDN; the page still works with fallback fonts if unavailable.

## Customisation
Edit `index.html` for text and links, and `assets/style.css` for colours and layout. No build step or paid hosting is required.
