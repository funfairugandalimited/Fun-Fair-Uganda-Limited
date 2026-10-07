# Deployment & Hosting Guide

**Client:** Fun Fair Uganda Limited  
**Website URL:** `https://funfairugandalimited.co.ug/`  
**Tech Stack:** Native HTML5, Tailwind CSS (CDN), FontAwesome 6, Vanilla JS

---

## Project Structure

Ensure all files are arranged in the root folder of your web hosting environment as shown below:

```text
/ (root)
├── index.html
├── robots.txt
├── sitemap.xml
├── SEO-DEPLOYMENT-CHECKLIST.md
├── DEPLOYMENT.md
└── images/
    ├── logo3.jpeg
    ├── WhatsApp Image 2026-10-05 at 06.17.06.jpeg
    ├── WhatsApp Image 2026-10-05 at 06.17.06 (1).jpeg
    ├── WhatsApp Image 2026-10-05 at 06.17.07.jpeg
    ├── WhatsApp Image 2026-10-05 at 06.17.08.jpeg
    └── WhatsApp Image 2026-10-05 at 06.17.08 (1).jpeg
```

---

## Deployment Methods

### Option A: Hosting via cPanel / DirectAdmin (Traditional Hosting)

1. Log into your domain's cPanel control panel.
2. Open **File Manager** and navigate to `public_html`.
3. Compress your local project folder into a `.zip` archive.
4. Upload the zip file to `public_html` and extract it.
5. Verify that `index.html` is located directly inside `public_html/index.html`.
6. Ensure **SSL (HTTPS)** is enabled under *SSL/TLS Status* or *Let's Encrypt*.

---

### Option B: Hosting via Netlify

1. Log into your [Netlify](https://www.netlify.com/) account.
2. Drag and drop the root directory containing `index.html`, `robots.txt`, `sitemap.xml`, and the `images/` directory directly into Netlify's **Sites** upload area.
3. In Site Configuration, go to **Domain Management** -> **Add Custom Domain**.
4. Enter `funfairugandalimited.co.ug`.
5. Update your domain registrar's DNS settings with Netlify's nameservers or A/CNAME records.

---

### Option C: Hosting via Vercel

1. Install Vercel CLI or connect your GitHub repository to [Vercel](https://vercel.com/).
2. Run `vercel` in the project directory, or click **Import Project** in the Vercel Dashboard.
3. Framework Preset: Choose **Other** / **Static HTML**.
4. Click **Deploy**.
5. Assign custom domain `funfairugandalimited.co.ug` in project settings.

---

## Post-Deployment Verification Checklist

1. **HTTPS Enforcement:** Verify that visiting `http://funfairugandalimited.co.ug` automatically redirects to `https://funfairugandalimited.co.ug/`.
2. **Image Loading:** Confirm all 6 local images load correctly from the `images/` path.
3. **WhatsApp Dispatch Testing:**
   - Test clicking **Reserve this ride** in the Instant Fare Estimator.
   - Fill out the modal booking form and verify that clicking **Send booking on WhatsApp** opens WhatsApp with pre-filled route details, fare, passenger count, flight number, and pickup date.
4. **Phone Links:** Test clicking `+256 752 485 485` on mobile devices to verify direct dialing dialer activation.