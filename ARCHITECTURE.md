# Shop Boost Labs — Public Architecture Overview

This document is intentionally high-level and safe for the future public showcase repository.

## System boundary

Shop Boost Labs is organized as four separate workstreams:

```text
                    Shopify Merchant
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v
 Product Tracker      SEO Issue Tracker   Dropshipping App
        |                  |                  |
        +------------------+------------------+
                           |
                      Render hosting
                           |
                 PostgreSQL / Neon
                    where required
```

The company marketing website is deployed separately:

```text
shopboostlabs.com
       |
       v
Render Static Site
       |
       +-- Product pages
       +-- Support
       +-- Privacy
       +-- Terms
       +-- Public media
```

## Separation principles

- The marketing website does not contain Shopify authentication, billing, webhook, or application-database logic.
- Each application keeps its own runtime configuration outside source control.
- Production credentials are stored through environment / secret-management systems, not in the public showcase.
- The public showcase contains only sanitized documentation, diagrams, screenshots, and approved demo media.
- NexaExchange is a separate project and is not part of this architecture.

## Technology overview

Across the Shop Boost Labs workstreams, the public technology story may reference:

- Shopify app platform
- React / Remix
- TypeScript / JavaScript
- Prisma
- PostgreSQL / Neon
- Render
- GitHub

## Public-release boundary

Safe for the showcase:
- high-level component relationships
- product workflows
- non-sensitive screenshots
- product status and pricing
- public website links
- general technology stack

Do not publish:
- environment-variable values
- database connection strings
- API keys or access tokens
- Shopify application secrets
- supplier credentials
- private service IDs
- private backend source copied from operational repositories
- internal incident material
