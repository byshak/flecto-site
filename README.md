# Flecto — Free Tools & Best Deals

**Website:** [flecto.shop](https://flecto.shop)

Free tools hub and deals finder. Work smarter, save more — no signup, no cost, always free.

## Pages

| File | Page |
|---|---|
| `index.html` | Main homepage |
| `about.html` | About Flecto |
| `contact.html` | Contact page |
| `privacy-policy.html` | Privacy Policy |
| `terms.html` | Terms of Use |
| `disclaimer.html` | Disclaimer & Affiliate Disclosure |

## Setup — GitHub Pages + Custom Domain (flecto.shop)

### Step 1 — Create GitHub Repository
1. Go to github.com → New repository
2. Name it exactly: `flecto-site` (or any name you prefer)
3. Set to **Public**
4. Do NOT add README (you have one)
5. Click Create

### Step 2 — Upload Files
Upload all these files to the repository:
- `index.html`
- `about.html`
- `contact.html`
- `privacy-policy.html`
- `terms.html`
- `disclaimer.html`
- `LICENSE.txt`
- `README.md`
- `CNAME`

### Step 3 — Enable GitHub Pages
1. Go to repository **Settings**
2. Click **Pages** in the left sidebar
3. Under Source → select **main** branch → **/ (root)**
4. Click Save
5. Wait 2-3 minutes — GitHub will show your Pages URL

### Step 4 — Connect flecto.shop Domain (Hostinger DNS)
1. Log in to **Hostinger** → Domains → flecto.shop → DNS Zone
2. Delete any existing A records for @
3. Add these 4 A records:
   ```
   Type: A  |  Name: @  |  Value: 185.199.108.153
   Type: A  |  Name: @  |  Value: 185.199.109.153
   Type: A  |  Name: @  |  Value: 185.199.110.153
   Type: A  |  Name: @  |  Value: 185.199.111.153
   ```
4. Add this CNAME record:
   ```
   Type: CNAME  |  Name: www  |  Value: byshak.github.io
   ```
5. Wait 10-30 minutes for DNS to propagate

### Step 5 — Set Custom Domain in GitHub
1. In GitHub Pages settings
2. Under "Custom domain" → type: `flecto.shop`
3. Click Save
4. Tick "Enforce HTTPS" once it appears

### Step 6 — Verify it works
Visit https://flecto.shop — should load your site!

---

## AdSense Setup (after domain is live)

1. Go to adsense.google.com → Sign up
2. Enter: https://flecto.shop
3. Add the AdSense verification code to `<head>` in index.html
4. Wait for approval (1-14 days)
5. Once approved, replace the placeholder ad divs with real AdSense code
6. Replace `ca-pub-XXXXXXXXXXXXXXXX` with your real publisher ID

**AdSense-ready checklist already done:**
- ✅ Privacy Policy page
- ✅ Terms of Use page
- ✅ About page
- ✅ Contact page
- ✅ Disclaimer + Affiliate disclosure
- ✅ Cookie consent banner
- ✅ Clean navigation
- ✅ Mobile responsive
- ✅ Original content
- ✅ No broken links
- ✅ Custom domain (.shop)
- ✅ Ad placeholder slots in correct positions

---

© 2026 Flecto by G. Shakeel — [flecto.shop](https://flecto.shop)
