# Shop Boost Labs

Practical Shopify apps for product research, SEO workflows, and supplier-powered dropshipping.

**Website:** https://shopboostlabs.com

> This repository is the public showcase for Shop Boost Labs. Production application source code, secrets, credentials, and private infrastructure details remain in separate private repositories.

## What we build

Shop Boost Labs is building a focused suite of Shopify tools for merchants who want to research products, improve store SEO, and connect supplier-powered workflows without adding unnecessary complexity.

### ShopBoost Product Tracker

**Status:** Live  
**Pricing:** Free  
**Shopify App Store:** https://apps.shopify.com/shopboost-product-tracker

Product Finder helps merchants organize product research, track opportunities, and make margin-focused decisions inside a structured workflow.

Highlights:
- Product discovery and research
- Opportunity tracking
- Margin-focused organization
- Draft-product workflow support

### SEO Issue Tracker

**Status:** Submitted to Shopify review  
**Pricing:** $5.99/month  
**Trial:** 7 days

SEO Issue Tracker scans a Shopify store for SEO issues and helps merchants prioritize what to fix.

Highlights:
- Store-wide SEO audits
- Issues ranked by severity
- AI-assisted meta title and description suggestions
- Review-before-save workflow
- Audit history

### ShopBoost Dropshipping

**Status:** Submitted to Shopify review  
**Pricing:** $5.99/month  
**Trial:** 14 days

ShopBoost Dropshipping connects supplier discovery, product import, variant linking, and supplier-powered order workflows.

Highlights:
- Supplier product search
- Product import to Shopify
- Variant linking
- Supplier cost and selling-price workflow
- Order workflow support

## Full-suite demo

One complete walkthrough is used for the Shop Boost Labs suite rather than three duplicate videos.

The demo covers:
1. Product Finder
2. SEO Issue Tracker
3. ShopBoost Dropshipping

Prepared public demo asset: `Demo-web-public.mp4` (960×540, H.264/AAC, approximately 5:45). Sampled public-version frames were visually reviewed before publication prep; no visible API key, access token, password, database URL, or supplier credential was observed in the reviewed frames. Upload the video only to the public showcase / website destination after the final repository-level media check.

## Product media

### ShopBoost Product Tracker
![ShopBoost Product Tracker dashboard](media/product-tracker-dashboard.jpg)

### SEO Issue Tracker
![SEO Issue Tracker dashboard](media/seo-issue-tracker-dashboard.jpg)

### ShopBoost Dropshipping
![ShopBoost Dropshipping supplier linking](media/shopboost-dropshipping-link-supplier.jpg)

Use real product screenshots only.

Recommended media:
- Product Finder: Discover / search workflow and Margin Tracker
- SEO Issue Tracker: audit dashboard, AI Fix, audit history
- ShopBoost Dropshipping: dashboard, Link to Supplier, credential-safe supplier workflow

Do not publish screenshots containing API keys, supplier credentials, access tokens, passwords, database connection strings, or Shopify secrets.

## Architecture overview

```text
Shopify Merchant / Admin
          |
          v
  Shop Boost Labs Apps
    |       |       |
 Finder    SEO   Dropshipping
    |       |       |
    +---- Render ----+
             |
      PostgreSQL / Neon
```

The company website is independently deployed:

```text
shopboostlabs.com
      |
Render Static Site
      |
Product / Support / Policy pages
```

## Tech stack

High-level technologies used across Shop Boost Labs include:

- Shopify app platform
- React / Remix
- TypeScript / JavaScript
- Prisma
- PostgreSQL / Neon
- Render
- GitHub

## Milestones

- ✅ ShopBoost Product Tracker live
- ✅ SEO Issue Tracker built and submitted to Shopify review
- ✅ ShopBoost Dropshipping built and submitted to Shopify review
- ✅ Dedicated company website deployed
- ✅ Custom company domain configured
- ✅ Billing flows configured for paid apps
- ✅ Security and repository organization pass completed
- ✅ Production architecture documented
- ✅ Public-showcase security boundaries defined

## Roadmap

- Upload the final public full-suite demo video
- Complete final website desktop/mobile QA
- Add public sponsorship / collaboration information
- Respond to Shopify review feedback if requested
- Continue improving products after review and merchant feedback

## Security and privacy approach

Shop Boost Labs keeps production credentials outside source control and separates the company website from Shopify application backends.

This public showcase must never contain:
- `.env` files
- database URLs
- API keys
- Shopify secrets
- supplier credentials
- access tokens
- private source code copied from production repositories

## Support

For Shop Boost Labs product questions:

**shopboostlabs8@gmail.com**

Do not send passwords, API keys, access tokens, or other credentials by email.

## Collaboration and sponsorship

Shop Boost Labs is being built as an independent Shopify-app venture. If you want to support development, use the GitHub **Sponsor** button after the `Yoyogino` GitHub Sponsors profile is active. Official website: **https://shopboostlabs.com**

---

Shop Boost Labs · Focused Shopify tools for practical ecommerce work.
