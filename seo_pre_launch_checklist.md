# SEO & Pre-Launch Verification Checklist

**Project:** Fun Fair Uganda Limited  
**Domain:** `https://funfairugandalimited.co.ug/`  
**Target Market:** Uganda (Kampala, Entebbe International Airport, Jinja, Mukono, National Parks)

---

## 1. Meta Data & Search Engine Discovery

- [x] **Title Tag Optimization:** Includes primary brand keyword and main services (*Fun Fair Uganda Limited | Airport Transfers, Chauffeur & Private Car Hire in Uganda*).
- [x] **Meta Description:** Clear value proposition under 160 characters highlighting flight tracking, Entebbe Airport transfers, and 24/7 dispatch.
- [x] **Canonical Tag:** Defined as `https://funfairugandalimited.co.ug/` to prevent duplicate indexing issues.
- [x] **Robots Meta Tag:** Set to `index, follow, max-image-preview:large`.
- [x] **Robots.txt:** Configured and pointing directly to `sitemap.xml`.
- [x] **XML Sitemap:** Validated at `/sitemap.xml`.

---

## 2. Structured Data (JSON-LD Schema)

- [x] **`LocalBusiness` / `TaxiService` Schema:**
  - Phone: `+256752485485`
  - Email: `funfairugandaltd78@yahoo.com`
  - Operating Hours: 24/7 (`00:00` - `23:59`)
  - Geographic Coverage: Kampala, Entebbe, Mukono, Jinja, Uganda
  - Price Range: `$$`
- [x] **`FAQPage` Schema:** Includes 9 complete Q&A items matching on-page content.
- [x] **`WebSite` Schema:** Declares primary brand name and name variations (`funfair`, `funfairuganda`, `funfairugandalimited`).

---

## 3. Social Media & Open Graph Protocol

- [x] **OG Tags (`og:title`, `og:description`, `og:url`, `og:image`):** Standardized with production URL and primary preview banner (`/images/logo3.jpeg`).
- [x] **Twitter Cards:** Configured for `summary_large_image`.

---

## 4. Post-Deployment Verification Tasks

Once the website is live on custom hosting/domain, perform the following verification steps:

### A. Google Search Console Setup
1. Log into [Google Search Console](https://search.google.com/search-console).
2. Add Domain property: `funfairugandalimited.co.ug` (or URL Prefix `https://funfairugandalimited.co.ug/`).
3. Verify ownership via DNS TXT record or HTML tag.
4. Navigate to **Sitemaps** and submit `https://funfairugandalimited.co.ug/sitemap.xml`.
5. Perform an **URL Inspection** on the homepage and click **Request Indexing**.

### B. Google Business Profile & Local SEO Setup
1. Claim/Verify **Fun Fair Uganda Limited** on [Google Business Profile](https://business.google.com/).
2. Set primary category to **Airport Shuttle Service** or **Taxi Service**.
3. Set secondary category to **Chauffeur Service** / **Car Leasing Service**.
4. Set exact website link to `https://funfairugandalimited.co.ug/`.
5. Ensure the phone number matches `+256752485485` and physical address matches **Plot 12 Entebbe Road, Kampala, Uganda**.

### C. Performance & Mobile Accessibility Check
1. Run [Google PageSpeed Insights](https://pagespeed.web.dev/) on the live URL.
2. Verify image loading speeds for local asset files inside the `images/` folder.
3. Test WhatsApp dispatch deep-link flow on iOS and Android devices.