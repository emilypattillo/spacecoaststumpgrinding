# Space Coast Stump Grinding Pro site

Created: 2026-05-04T17:34:56+00:00

Purpose: simple static SEO site for a Website Landlord / rank-and-rent test in Brevard County, FL. Original build started with Palm Bay; current launch direction is Melbourne, FL as the primary SEO/domain target, with public branding updated to `Space Coast Stump Grinding Pro` so the site reads like a focused local operator rather than a directory or lead marketplace.

## Domain status

Updated: 2026-05-04T18:52:54+00:00

- Purchased primary domain: `melbourneflstumpgrinding.com`
- Purchased secondary domain: `spacecoaststumpgrinding.com`
- Recommended canonical/live site: `https://melbourneflstumpgrinding.com`
- Recommended use for secondary domain: redirect `spacecoaststumpgrinding.com` to the primary domain; do not publish a duplicate site.
- Emily sent domain management invites to `thursday@emilypattillo.com` for direct access if needed.

## Launch checklist

- Pivot homepage/title/meta/schema/canonical from Brevard/Palm Bay framing to Melbourne, FL primary positioning.
- Active validation phone: Google Voice `(321) 294-3433`, controlled by Emily, added 2026-05-05.
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

### 2026-05-05T03:40:12Z — Operator-style brand update

- Updated public brand from `Melbourne FL Stump Grinding` to `Space Coast Stump Grinding Pro` across visible navigation, footer, page titles, metadata, and schema.
- Shifted homepage and shared page language away from directory/lead-marketplace phrasing and toward a focused local operator voice while avoiding unsupported claims like fake reviews, addresses, licensing, or years in business.
- Kept the canonical SEO/domain target as `https://melbourneflstumpgrinding.com` for the Melbourne search beachhead.

### 2026-05-05T03:21:30Z — Email field and replication SOP

- Added an optional typed email field to the quote forms so form submissions can capture both phone and email follow-up.
- Created the reusable Website Landlord launch SOP at `/root/.hermes/profiles/wednesday/artifacts/website-landlord/sops/website-landlord-rank-and-rent-launch-sop.md`.
- Documented the FormSubmit activation requirement: submit a live test inquiry, confirm the activation email in Thursday, then verify a second test submission.

### 2026-05-05T03:13:23Z — Google Voice validation number added

- Replaced the placeholder phone with Emily-controlled Google Voice number `(321) 294-3433` across public HTML pages, `tel:` links, schema telephone fields, and README documentation.
- Purpose: early lead validation before moving to CallRail/WhatConverts/Twilio.

### 2026-05-05T02:36:17Z — Mobile-first CSS pass

- Reworked `assets/styles.css` so the base layout is mobile-first, with tablet/desktop enhancements in `min-width` media queries.
- Kept all text, headings, links, schema, and forms in normal HTML for SEO crawlability.
- Improved mobile conversion UX: visible horizontal nav chips instead of hidden nav, full-width quote/call buttons, fixed bottom call button on mobile, larger form touch targets, single-column content/cards by default, and responsive images.
- Preserved desktop two-column hero/form layout and multi-column cards at wider viewports.
- Verification performed: checked 12 HTML pages for viewport tags and missing local links/assets; no missing local references found.

- 2026-05-05T06:14:30Z — Model-style content expansion: homepage expanded to 4,000+ useful words, six service-intent pages added, sitemap updated, and CTA class collision cleaned up after CTO/CMO review.
