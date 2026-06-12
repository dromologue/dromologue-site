# dromologue.com — outstanding work

_Last updated: 2026-06-12. The site is **pre-launch** ("still in stealth mode" banner is intentional)._

## Content
- [ ] **About page** — still the "Coming soon" placeholder. Write copy; it will format itself into the editorial template (use an `eyebrow:` + headline like Perspective/Services).
- [ ] **Blog** — replace the seed post `_posts/2026-06-11-the-first-prompt-is-structural.md` with real content when ready. `_posts/README.md` documents the drop-in workflow.
- [ ] Confirm final **hero copy** and the **Services headline** ("We redesign how your organisation works with AI" was my choice, not supplied).

## Credibility before launch
- [x] **Source-anchor the Perspective statistics** — done 2026-06-12. Inline links to S&P Global, BCG, McKinsey, EUR-Lex; corrected the McKinsey ("nearly three times", dropped the unsupported sequencing) and EU AI Act (€35m/7% is the top tier, not high-risk) wording. _Human click-through of each link still advisable (corporate domains bot-block, so couldn't auto-verify)._
- [ ] **Remove / replace the "still in stealth mode" banner** at launch (`_includes/` + `.stealth-banner`).

## Email
- [x] **Send a test** to transform@dromologue.com — confirmed working (2026-06-12).
- [ ] Optional: add a **catch-all** (any @dromologue.com → Gmail) or extra aliases — currently only `transform@` forwards, everything else bounces.
- [ ] Optional: set up **send-as transform@** (SMTP) if outbound from that address is wanted.

## Verification / QA
- [x] **Check the homepage on a real phone** — confirmed working (2026-06-12).
- [ ] **Validate the OG share card** via LinkedIn Post Inspector / X card validator (tags + `/assets/images/og-default.png` are in place).
- [ ] Re-check colour **contrast** if any brand colours change (text uses darkened `--bronze-ink`; bright bronze reserved for rules/borders).

## Optional polish
- [ ] J-curve diagram: decide whether to re-add the "a modest gain above the start, then flat" annotation (dropped for clarity).
- [ ] Decide whether Organisational Prompts (Substack) should appear in both the footer **and** the blog sidebar, or just one.

---

## Recently completed (2026-06)
- Rebrand to navy/bronze/paper + Inter; favicon from the D mark.
- Homepage redesign: asymmetric type-first hero, latest-article panel, sectioned footer, dromologue etymology callout.
- Blog system: drop-in `_posts/`, two-column layout with left link gallery, `/blog/` hub.
- Our Perspective + Services pages with editorial formatting and the J-curve SVG.
- SEO: jekyll-seo-tag + jekyll-sitemap, per-page titles, OG/Twitter cards, OG image, robots.txt.
- Accessibility: darkened bronze/grey for WCAG AA text contrast.
- Branch renamed master → main so pushes deploy.
- Email forwarding for transform@dromologue.com (see memory: dromologue-email-forwarding).
