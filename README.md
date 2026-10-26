# Shaida Muhammad Sherpao — Portfolio

## Files
- `index.html` — responsive portfolio, SEO metadata, full CV content, project catalogue, and consistently formatted publications.
- `images/shaida-muhammad-sherpao.jpg` — profile photo, kept at its native square aspect ratio; the AI/ML caption moves below the portrait on phones.
- `Shaida-Muhammad-Resume-2026.pdf` — supplied 2026 CV, linked from the homepage.
- `robots.txt` and `sitemap.xml` — crawler instructions and sitemap for the canonical homepage.
- `thanks.html` — branded confirmation page used after a message is sent through the contact form.

## Publish on GitHub Pages
1. Extract the ZIP and copy the **contents** of this folder to the root of `ShaidaMuhammad.github.io`.
2. Preserve the `images` folder and keep `index.html`, the PDF, `robots.txt`, `sitemap.xml`, and `thanks.html` in the publishing root.
3. In GitHub, open **Settings → Pages** and ensure the publishing source matches the branch and root folder where these files were uploaded.
4. The canonical website URL is `https://shaidamuhammad.github.io/`.
5. Once published, add the website in Google Search Console and Bing Webmaster Tools, submit `https://shaidamuhammad.github.io/sitemap.xml`, and request indexing.

## Contact form setup
The website is hosted statically on GitHub Pages, so it cannot send email directly from its own server. The contact form uses FormSubmit (`https://formsubmit.co`) to forward messages to `shaidasherpao@gmail.com` without a separate backend.

After publishing the archive:
1. Open the live contact section and send yourself one test message.
2. Check `shaidasherpao@gmail.com` for FormSubmit's one-time activation/confirmation email, then follow its confirmation link.
3. Submit a second test message to verify delivery. After activation, new contact form submissions should be forwarded to the email address above.

FormSubmit is a third-party service and will process the submitted contact details. Keep this in mind when deciding whether to use a third-party form backend. You can replace the form action with an endpoint from another provider later without redesigning the form.

## Publication style
Publications use a consistent compact bibliographic format: title, authors, venue/source, year, and a DOI or official link when available. The ICAAD 2026 paper is listed as accepted with publication details pending; event scheduling information and the long submission abstract are intentionally not displayed. The Springer item is listed as a published book chapter. Its earlier CV working title is available in a collapsed note on the same record, not as a duplicate publication.

## SEO notes
The site includes a descriptive title and meta description, canonical URL, Open Graph/Twitter metadata, meaningful headings, descriptive photo alt text, and Schema.org Person structured data. Search engines decide whether and where to rank a page; these measures improve crawlability and identity clarity but cannot guarantee a top position. Legitimate, consistent links from professional profiles, research records, and relevant project repositories can also help discovery.
