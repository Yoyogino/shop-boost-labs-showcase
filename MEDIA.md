# Public Media Register

This register tracks media intentionally approved for the public Shop Boost Labs showcase.

## Approved screenshots

| File | Product | Public purpose | Review status |
| --- | --- | --- | --- |
| `media/product-tracker-dashboard.jpg` | ShopBoost Product Tracker | Show the product research / dashboard experience | Approved for public showcase |
| `media/seo-issue-tracker-dashboard.jpg` | SEO Issue Tracker | Show the SEO audit dashboard | Approved for public showcase |
| `media/shopboost-dropshipping-link-supplier.jpg` | ShopBoost Dropshipping | Show the supplier-linking workflow without exposing supplier credentials | Approved for public showcase |

## Explicitly excluded

Do **not** publish a supplier-settings screenshot containing supplier credentials or API identifiers.

Do not add media containing:
- API keys
- access tokens
- passwords
- database connection strings
- Shopify secrets
- supplier credentials
- merchant/customer data
- internal service identifiers that are not meant to be public

## Demo video

Prepared public demo:
- public demo title/source: **DemoSBL**
- website destination: `public/media/shop-boost-labs-demo.mp4`
- optimized format: H.264 video + AAC audio
- intended role: one full-suite walkthrough covering all three Shop Boost Labs products
- current status: uploaded to the website repository at `public/media/shop-boost-labs-demo.mp4`; upload commit passed website checks and deployed successfully on Render

Final video review completed before deployment:
1. sampled frames were visually inspected,
2. no obvious secret-bearing screen was observed in the reviewed samples,
3. no sensitive browser URL/query string was observed in the reviewed samples,
4. the reviewed asset fingerprint is recorded below.


Reviewed DemoSBL asset fingerprint:
- SHA-256: `5c1fc52dafe74021065a4e9eaee8ba4631951e192fc4c3497e48c33fb4ebfc11`
- size: 9,014,457 bytes
- video: H.264, 960×540, 30 fps
- audio: AAC
- duration: approximately 5:45

## Rule

No media is considered approved merely because it exists in a private project folder. Public release is a separate decision.
