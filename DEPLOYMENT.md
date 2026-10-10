# Fun Fair Uganda Limited — production deployment

## Folder contents
- `index.html` — the homepage (all words, prices, booking and WhatsApp logic kept from the original)
- `images/` — optimised photos, `logo.png` (white background), favicons, `og-banner.jpg` (WhatsApp/Facebook share image)
- `favicon.ico`, `site.webmanifest`, `robots.txt`, `sitemap.xml`, `_headers` (Cloudflare Pages)

## IMPORTANT: replace the logo
`images/logo.png` is a **temporary stand-in** (FF emblem + name on white), because the real logo file was not in the upload.
To use your real logo, replace these files, keeping the same names:
- `images/logo.png` — square, at least 512 x 512 px, **white background**
- `images/favicon-48.png`, `images/favicon-192.png`, `images/apple-touch-icon.png` (180 x 180) and `favicon.ico`
- optionally `images/og-banner.jpg` (1200 x 630)

## Upload
Deploy the contents of this folder as a static site on Cloudflare Pages (no build command, output directory `/`). `index.html` is the homepage.

## DNS
Add the domain to Cloudflare and follow Cloudflare Pages' Custom Domain setup. Use the exact DNS/nameserver values shown in the Cloudflare dashboard; do not guess them.

## Google visibility
After the domain is live:
1. Verify the domain in Google Search Console.
2. Submit https://funfairugandalimited.co.ug/sitemap.xml
3. Inspect https://funfairugandalimited.co.ug/ and request indexing.
4. Create/claim the official Google Business Profile for Fun Fair Uganda Limited and upload the same logo there (this is the strongest way to get your logo beside your name in search).
5. Keep the business name, phone number, address and website consistent across the Business Profile and other legitimate business listings.

## Important
Google decides what appears in results. Indexing is not instantaneous, and no legitimate setup can guarantee that a search for the generic word "funfair" alone returns the company first (it is also a common word for amusement parks). This site is set up so Google can recognise the brand names "Fun Fair Uganda", "Funfair Uganda", "funfairuganda" and "funfairugandalimited", plus the domain, and show the logo/favicon.
