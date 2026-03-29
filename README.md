# GetCreditNow.com

A credit repair and debt relief resource site monetized through the **National Debt Relief affiliate program** (pay-per-lead via ShareASale).

## What This Is

GetCreditNow.com is a static lead generation affiliate website that earns $27.50 per qualified lead sent to National Debt Relief. The site educates visitors about debt relief options and drives them to request a free, no-obligation debt relief quote.

## Pages

| Page | Purpose |
|------|---------|
| `index.html` | Homepage — hero, debt calculator, trust signals, testimonials, FAQ, CTAs |
| `debt-relief-guide.html` | SEO content: how debt settlement works |
| `improve-credit-score.html` | SEO content: credit score improvement tips |
| `debt-consolidation-vs-settlement.html` | SEO content: comparison of debt relief options |
| `about.html` | About page for E-E-A-T trust signals |
| `privacy.html` | Privacy policy |
| `disclaimer.html` | Affiliate disclosure & financial disclaimers |
| `terms.html` | Terms of use |

## Setup Instructions

### 1. Replace Affiliate Tracking ID

All affiliate links use the placeholder `YOURAID`. Do a global find-and-replace across all HTML files:

**Find:** `YOURAID`
**Replace with:** Your actual ShareASale / National Debt Relief affiliate tracking ID

### 2. Sign Up for the Affiliate Program

1. Go to [ShareASale](https://www.shareasale.com) and create a publisher account
2. Search for **National Debt Relief** (Merchant ID: 54898) and apply to their program
3. Once approved, get your affiliate tracking ID from your ShareASale dashboard
4. Replace `YOURAID` in all HTML files with your tracking ID

### 3. Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set Source to: `Deploy from a branch` → `main` → `/ (root)`
4. Wait 2-3 minutes for the site to deploy

### 4. Configure Custom Domain (DNS)

Add these DNS records at your domain registrar:

| Type | Name | Value |
|------|------|-------|
| CNAME | www | `USERNAME.github.io` |
| A | @ | `185.199.108.153` |
| A | @ | `185.199.109.153` |
| A | @ | `185.199.110.153` |
| A | @ | `185.199.111.153` |

Replace `USERNAME` with your GitHub username.

After DNS propagates (up to 48 hours), enable **Enforce HTTPS** in GitHub Pages settings.

## Tech Stack

- Pure static HTML, CSS, vanilla JavaScript
- No build tools, frameworks, or npm dependencies
- Google Fonts (Plus Jakarta Sans + Sora)
- Mobile-first responsive design
- GitHub Pages hosting

## Qualified Lead Requirements

A qualified lead must:
- Have at least **$10,000 in unsecured credit card debt**
- Live in a **qualified US state** (all states except CT, OR, VT, WV)
- Complete National Debt Relief's free quote form

## Revenue Model

- **$27.50 per qualified lead** (visitor clicks affiliate link → fills out 6-field quote form)
- No purchase required by the visitor — they get a free, no-obligation debt relief quote
- Commission tracked and paid through ShareASale

## License

All rights reserved.
