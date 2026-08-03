# Duke Energy Bill Pay — Independent Guide

An independent, fact-checked reference guide for paying a Duke Energy bill: payment channels, fees, disconnection timing, and how to spot the scam phone numbers that circulate in search results for this topic.

**This site is not affiliated with, endorsed by, or operated by Duke Energy Corporation.** It does not process payments, store account data, or route calls. Every payment action described in the guide sends visitors to Duke Energy's own official domain (`duke-energy.com`) or published phone line.

## Live structure

| File | Purpose | URL path (once published) |
|---|---|---|
| `index.html` | Main guide — payment methods, fees, FAQ, Start/Stop/Move service | `/` |
| `about-us.html` | Who publishes this site and why | `/about-us.html` |
| `privacy-policy.html` | What data is (and isn't) collected | `/privacy-policy.html` |
| `contact-us.html` | Editorial contact form + correct official Duke Energy channels | `/contact-us.html` |
| `404.html` | Custom not-found page, redirects to homepage | any unmatched path |
| `robots.txt` | Crawler rules, points to sitemap | `/robots.txt` |
| `sitemap.xml` | Full URL list for search engines | `/sitemap.xml` |

All internal links use relative paths and assume every file above lives in the **same directory** (repo root, or the same published subfolder). Keep them together — moving one file without updating the others will break the interlinking.

## States covered

Duke Energy's regulated electric and/or natural gas service territory spans six states. This guide covers billing/payment mechanics generally, and flags where rules diverge by state (disconnection grace periods, in particular, are set by each state's own utility commission, not by Duke Energy alone):

- North Carolina — regulated by the North Carolina Utilities Commission
- South Carolina — regulated by the Public Service Commission of South Carolina
- Florida — regulated by the Florida Public Service Commission
- Indiana — regulated by the Indiana Utility Regulatory Commission
- Ohio — regulated by the Public Utilities Commission of Ohio
- Kentucky — regulated by the Kentucky Public Service Commission

This repo does not currently include a separate page per state. If you want state-specific landing pages (e.g. `/north-carolina.html`), that's a reasonable next step, but the sitemap below only lists pages that actually exist — a sitemap listing URLs that don't resolve is a fast way to get flagged in Search Console, not a shortcut to better indexing.

## Deploying on GitHub Pages

1. Push all files above to the repo root (or to whichever folder Pages is configured to serve).
2. In repo Settings → Pages, set the source branch/folder.
3. Confirm `index.html` is the file GitHub Pages picks up automatically at the root URL.
4. Wait for the Pages build to finish, then verify every internal link actually resolves — file names on GitHub Pages are case-sensitive.

## Editorial standard

Every fact in this guide is sourced to Duke Energy's own domain, on-the-record reporting, or explicitly flagged as uncertain when sources disagree (see `about-us.html`). Corrections and source disputes are welcome via `contact-us.html`.

## License

Content is provided as-is for informational purposes. Duke Energy and any related marks belong to Duke Energy Corporation and are referenced descriptively only.
