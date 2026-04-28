# WithHeart Marketing Sandbox

## Voice
Talie Knutson's brand — warm, heart-centered, professional. NOT Connor's voice. This is a client site. Talie is a brand marketing consultant in Santa Clarita.

## Standing Orders
- THIS IS A CLIENT SITE. Never deploy without Talie's explicit approval.
- Live site is withheart-marketing.com — DO NOT TOUCH without approval.
- Manual deploy only. Always.

## Netlify Sites

### Production (live)
- **Project name:** `whm03092026`
- **URL:** https://withheart-marketing.com
- **Site ID:** `a50b93c7-1ae8-464b-94dd-ee1a8fe47c85`
- **Last deploy:** 2026-04-17 01:16 UTC (manual, contains e2ef253 "schema, hero title case, workbook CTA, FAQ consultant line" changes)
- **Rule:** NEVER deploy here without Talie's explicit approval.

### Experimental sandbox (all WIP work)
- **Project name:** `whm-sandbox`
- **URL:** https://whm-sandbox.connorcoded.com
- **Site ID:** `8f3c8484-70a3-4a7a-97a4-98729dc5c60e`
- **Purpose:** Holds all exploratory work — brand-marketing page drafts, doorway sections, nav additions, etc. Talie has reviewed this and flagged "too much" on April 19. Preserved as-is for reference; do NOT wipe without Connor's explicit OK.
- **State mismatch:** Files were deployed via direct API upload, not from this git repo. The sandbox has more content than git HEAD.

### Approved-preview sandbox (review before production)
- **Project name:** `whm2-sandbox`
- **URL:** https://whm2-sandbox.netlify.app
- **Site ID:** `9f86352e-48b3-4d7e-889a-6612bb1b9039`
- **Created:** 2026-04-20
- **Purpose:** Shows the approved-only state = live site + only the changes Talie has blessed. Used for Connor's final review before he promotes to production.

## Current Approved Changes (awaiting production deploy)

As of 2026-04-20, Talie has explicitly approved these 4 homepage wording tweaks (from iMessage thread, "Tall-e" Talie K., April 18-19, confirmed in email reply April 20):

1. Hero eyebrow: "Brand Strategy with Heart and Soul" → **"Brand Marketing with Heart and Soul"** (her North Star)
2. Hero mission: "heart-centered brand strategy framework" → **"heart-centered brand marketing framework"**
3. Namecard subtitle: "Brand & Marketing Consultant" → **"Brand Marketing Consultant"**
4. Approach headline: "A Heart-Centered Framework for Brand Clarity" → **"A Heart-Centered Brand Marketing Framework"**

All four committed in `4fdc73e`. Branch: `claude/build-new-website-page-MuaJg`.

## Work Talie Has NOT Approved (hold)

- New `/brand-marketing/` page — Talie said "WAY too much, nervous system going haywire." She is sending her own simpler spec (expected April 20+). Current draft lives only on the whm-sandbox experimental site, not in git.
- Brand Marketing nav link (desktop + mobile + footer) — Talie said "adding one more thing to the nav and this main one-page type site is too much." Kill from production plan.
- Homepage doorway section below "Work With Me" — same ruling.
- SEO sweep removing "brand strategy" terms — Talie said **additive only**: add "brand marketing" and "heart-centered brand marketing" to schema, keywords, etc., WITHOUT removing anything. Hold on title tag / meta description changes until Google Search Console data is reviewed.
- Pricing on any page — Talie said "I want to leave all pricing off the site for now."

## Google Search Console

- Set up with Talie on a call the week of April 13, 2026.
- Data can be pulled whenever. No further action needed from Talie.

## Key Documents in This Repo

- `.project-docs/meetings/2026-04-17-talie-connor-partnership-expansion.md` — full Zoom meeting summary
- `.project-docs/sms/2026-04-18-talie-sms-brain-dump.md` — iMessage thread with the 4 approved tweaks
