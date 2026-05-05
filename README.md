# Brevard Stump Grinding lead-gen site

Created: 2026-05-04T17:34:56+00:00

Purpose: simple static SEO site for a Website Landlord / rank-and-rent test in Brevard County, FL. Original build started with Palm Bay; current launch direction is Melbourne, FL as the primary SEO/domain target with Space Coast held as a secondary/redirect brand asset.

## Domain status

Updated: 2026-05-04T18:52:54+00:00

- Purchased primary domain: `melbourneflstumpgrinding.com`
- Purchased secondary domain: `spacecoaststumpgrinding.com`
- Recommended canonical/live site: `https://melbourneflstumpgrinding.com`
- Recommended use for secondary domain: redirect `spacecoaststumpgrinding.com` to the primary domain; do not publish a duplicate site.
- Emily sent domain management invites to `thursday@emilypattillo.com` for direct access if needed.

## Launch checklist

- Pivot homepage/title/meta/schema/canonical from Brevard/Palm Bay framing to Melbourne, FL primary positioning.
- Placeholder phone `(321) 555-0198` is intentionally kept until Google Voice/call tracking is ready.
- Quote form currently uses FormSubmit routed to `thursday@emilypattillo.com`; confirm first-use FormSubmit email and later replace with real CRM/SMS routing if needed.
- Canonical URLs, schema, robots, and sitemap have been set to `https://melbourneflstumpgrinding.com`; recheck after deploy.
- Add local job photos or approved AI-generated images per `PHOTO-BRIEF.md`.
- Configure `spacecoaststumpgrinding.com` as a 301 redirect to `melbourneflstumpgrinding.com` after hosting/DNS is set.
- Submit sitemap in Google Search Console after domain is live.
- Add analytics and call/form conversion tracking.
- Avoid fake address/GBP/reviews.

## Pages

- /
- /palm-bay-stump-grinding.html
- /melbourne-stump-grinding.html
- /titusville-stump-grinding.html
- /cocoa-rockledge-stump-grinding.html
- /merritt-island-stump-grinding.html
- /stump-removal-vs-grinding.html
- /stump-grinding-cost-brevard.html
- /storm-cleanup-stump-grinding.html
- /contact.html

## Change log

### 2026-05-05T02:36:17Z — Mobile-first CSS pass

- Reworked `assets/styles.css` so the base layout is mobile-first, with tablet/desktop enhancements in `min-width` media queries.
- Kept all text, headings, links, schema, and forms in normal HTML for SEO crawlability.
- Improved mobile conversion UX: visible horizontal nav chips instead of hidden nav, full-width quote/call buttons, fixed bottom call button on mobile, larger form touch targets, single-column content/cards by default, and responsive images.
- Preserved desktop two-column hero/form layout and multi-column cards at wider viewports.
- Verification performed: checked 12 HTML pages for viewport tags and missing local links/assets; no missing local references found.
