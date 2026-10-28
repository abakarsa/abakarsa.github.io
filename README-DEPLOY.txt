ABAKARSA STATIC WEBSITE PACKAGE

Files
- index.html: Fox/Panda destination selector and site-wide development notice.
- about-us.html: About Abakarsa page.
- favicon.svg / favicon.ico / apple-touch-icon.png: flower brand icon.
- og-image.png: social preview card for Open Graph and Twitter.
- robots.txt / sitemap.xml: crawler discovery files.
- site.webmanifest: browser install/theme metadata.
- og-image.png: 1200×630 social share preview used by Open Graph and Twitter cards.

IMPORTANT — destination links
The actual Fox and Panda destination URLs were not supplied. In index.html, replace these two href values before publishing:
- https://example.com/fox
- https://example.com/panda
They are placeholders; no live destination has been invented.

SEO notes
- Canonical URLs assume the website is hosted at https://abakarsa.com/ and the About page at https://abakarsa.com/about-us.html. If the production URL structure differs (e.g. /about/), update the canonical, og:url, JSON-LD, and sitemap entries together.
- Keep both pages crawlable and do not add noindex if they should appear in search. Upload sitemap.xml and robots.txt to the website root.
- Use Google Search Console to verify the domain, submit /sitemap.xml, and inspect both live URLs after deployment. Metadata and structured data help search engines understand the pages but cannot guarantee rankings. More specific SEO requires accurate information about Abakarsa's actual products, services, audience, and destination sites.
