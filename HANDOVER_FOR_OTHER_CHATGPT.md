# PRIME DIGITAL · PRISM OS · COMPLETE HANDOVER

**Prepared:** 9 October 2026  
**Website:** https://www.prime-digital.co.za/  
**GitHub source:** NOT YET IDENTIFIED. Previously checked `cyevanniekerk2-debug/cye-carla-google-ads`, but the owner confirmed that is the WRONG account. DO NOT upload, push, merge or deploy there.  
**Vercel project:** A `prime-digital` project was visible in an older account connection; ownership of the intended target is NOT YET CONFIRMED. Do not change its configuration until the owner confirms the correct account and project.  
**Status:** Website package built locally. **NOT published or uploaded to the live website.**

## Instructions to paste into your other ChatGPT account

> I am uploading the Prime Digital PRISM OS complete website ZIP. Please inspect the contents before changing my live site. I own prime-digital.co.za, hosted via Vercel/GitHub. A previously discovered repository (`cyevanniekerk2-debug/cye-carla-google-ads`) was explicitly confirmed by me to be the WRONG GitHub account. Do not touch it. Verify the correct GitHub owner/repository and Vercel project from my connected account first. Help me back up the current site, create a preview branch/deployment, test desktop/mobile and the payments and contact process, and ONLY publish to production after I explicitly approve. Keep domain connections and working email DNS unchanged. Do not ask for passwords in the chat. Pages relating to refunds/terms/privacy are drafts requiring review.

## What's in the package

- All **22 HTML files** (including a 404 page, a real order-enquiry checkout, and a client portal UI demonstration)
- `assets/site.css`: original responsive colourful futuristic design
- `assets/site.js`: navigation, Google Ads package tabs, planner, FAQ filter, safe local product IDs, WhatsApp enquiries
- `assets/favicon.svg`: brand icon
- `robots.txt`, `sitemap.xml`, `site.webmanifest`
- `docs/*`: page listing, test notes and deployment checklist

## Main pages

Home `index.html`, services `services.html`, ads `packages.html`, websites `websites.html`, domain care `domains.html`, email `email.html`, pricing `pricing.html`, branding `branding.html`, SEO `seo.html`, portfolio `portfolio.html`, about `about.html`, process `process.html`, project planner `planner.html`, FAQ `faq.html`, contact `contact.html`, resource hub `resources.html`, launch checklist `launch-checklist.html`, portal demo `client-portal.html`, manual EFT checkout `eft-checkout.html`, privacy `privacy.html`, terms `terms.html`, refunds `refunds.html`, 404 `404.html`.

## Going live with GitHub + Vercel

1. Connect the correct GitHub account. Confirm its exact GitHub login and repository with me before any write action. A previously discovered account `cyevanniekerk2-debug` is NOT the intended account. Vercel and domain work can be handled later.
2. Back up the GitHub repository and inspect the currently deployed site. Preserve any working integrations in the repo. Do NOT overwrite serverless functions or environment variables without reviewing differences.
3. Create a new branch (suggested `preview/prime-prism-os`) and add the package files to the repository root (or the application's correct public path).
4. Verify the Vercel project points to that exact repository/branch and that its build settings accept static HTML. Create a preview deployment.
5. Test every page, forms, checkout, pricing, links, responsive layouts and performance on the preview URL.
6. Review drafted `privacy.html`, `terms.html` and `refunds.html` and the advertised prices with the actual business owner and legal adviser.
7. Confirm the EFT account details directly with the business owner and confirm what portion of any Google Ads package price constitutes media spend versus management fees.
8. Confirm domain ownership, email DNS and SSL remain working. Keep PayFast disabled until verified.
9. Ask the owner for explicit approval to publish. Only then merge/commit to the production branch or promote the approved Vercel deployment.
10. After launch, check `www` and bare domains, mobile usability, 404 handling, canonical URLs, sitemap and robots.

## Critical functional limitations (be transparent)

- **PayFast is not live.** EFT is a manually confirmed bank transfer, not a payment processor or a bank balance integration.
- **Bank details are printed in static HTML.** Before going live, the owner must directly verify accuracy and agree to publish these receiving details.
- **Checkout amounts come from a local allowlisted catalogue** and cannot be set by `?amount=` URL parameters. These are display values only; before fulfilment the team must independently verify cleared funds and correct pricing. It is not an invoicing system.
- **Google Ads Search certificate** linked to the user-supplied credential. No unverified official Google Partner company badge or guaranteed results are claimed.
- **The client portal is a design demo**, not authenticated. It contains no real customer information or interactive billing accounts.
- **WhatsApp enquiry forms open a prepared WhatsApp message.** They do not store customer data or submit an order to a server. Customers must press Send and attach any proof themselves.
- **Domain checks are WhatsApp requests**, not live DNS/registrar availability results.
- **Portfolio examples are concepts**, not past-client case studies or fabricated testimonials.
- **SEO work and branding services** are enquiry only, not fixed-price promises.
- **Privacy, terms and refund pages are drafts** and should be reviewed for applicable South African requirements before production use.
- **Web fonts are system fallbacks**; no font files are packaged or required.

## Ownership and security

- Treat the user's existing domain and registrar login as theirs; don't ask them to share passwords in chat.
- Secure administration, backend/client accounts, email provisioning and PayFast need separate implementation before being marketed as operational.
- The live site should not be replaced without preview and approval.