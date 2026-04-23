# 🚀 Pooja Tandon & Associates — Website Deployment Guide

## Files Included
```
index.html    → Main website (rename from the .html file)
sitemap.xml   → Helps Google discover and index your pages
robots.txt    → Tells search engines what to crawl
CNAME         → Custom domain config for GitHub Pages
README.md     → This guide
```

---

## OPTION A: GitHub Pages (FREE)

### Step 1 — Create a GitHub Account
1. Go to https://github.com
2. Click "Sign up" and create a free account
3. Verify your email

### Step 2 — Create a Repository
1. Click the **"+"** icon (top-right) → **"New repository"**
2. Name it: `poojatandonadvocate`
3. Set it to **Public**
4. Click **"Create repository"**

### Step 3 — Upload Files
1. Click **"uploading an existing file"** on the repo page
2. Drag and drop ALL files from this folder:
   - `index.html`
   - `sitemap.xml`
   - `robots.txt`
3. Click **"Commit changes"**

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under "Source", select **Branch: main**, folder: **/ (root)**
3. Click **Save**
4. Wait 2–3 minutes
5. Your site is now live at:
   `https://YOUR-USERNAME.github.io/poojatandonadvocate`

### Step 5 (Optional) — Add Custom Domain (~₹500/year)
1. Buy a domain (e.g., `poojatandonadvocate.com`) from:
   - Namecheap (https://namecheap.com) — cheapest
   - GoDaddy (https://godaddy.com)
   - Google Domains
2. Upload the `CNAME` file to your repo (edit it to match your domain)
3. In your domain provider's DNS settings, add:
   ```
   Type: CNAME
   Name: www
   Value: YOUR-USERNAME.github.io

   Type: A
   Name: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   ```
4. In GitHub repo → Settings → Pages → Custom domain: enter `www.poojatandonadvocate.com`
5. Check ✅ "Enforce HTTPS"
6. Wait 24-48 hours for DNS propagation

---

## OPTION B: Hostinger (₹149/month)

1. Go to https://hostinger.in
2. Buy the cheapest "Single Web Hosting" plan
3. Register a domain during checkout
4. In Hostinger panel → File Manager → public_html
5. Upload all files from this folder
6. Your site is live immediately!

---

## 📢 GET FOUND ON GOOGLE

### Google Search Console (Free — DO THIS!)
1. Go to https://search.google.com/search-console
2. Click "Add Property" → enter your domain/URL
3. Verify ownership (HTML file method or DNS method)
4. Submit your sitemap: enter `sitemap.xml` and click Submit
5. Google will start indexing your site within a few days

### Google Business Profile (Free — VERY IMPORTANT!)
1. Go to https://business.google.com
2. Click "Manage now"
3. Enter business name: "Pooja Tandon & Associates"
4. Category: "Lawyer" or "Law Firm"
5. Add address: Chamber No. 405, Lawyers Chamber Block III, Delhi High Court, New Delhi 110003
6. Add phone: (+91) 8459442423
7. Add website URL
8. Verify via postcard/phone
9. This makes you appear on Google Maps and local search results!

### Free SEO Boosters
- List on JustDial (already done ✅)
- List on GetLaw.in (already done ✅)
- Create profiles on:
  - LawRato.com
  - Vakil.com
  - IndiaFilings lawyer directory
  - LinkedIn (personal + firm page)

---

## 💰 TOTAL COST SUMMARY

| Option | Monthly | Yearly | Includes |
|--------|---------|--------|----------|
| GitHub Pages (no domain) | ₹0 | ₹0 | Free hosting, HTTPS |
| GitHub Pages + domain | ₹0 | ~₹500-800 | Free hosting + custom domain |
| Hostinger + domain | ~₹149 | ~₹2,500 | Hosting + domain + email |

**Recommended: GitHub Pages + Namecheap domain = ~₹600/year total**
