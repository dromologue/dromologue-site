# dromologue.com — outstanding work

_Last updated: 2026-06-12. The site is **pre-launch** ("still in stealth mode" banner is intentional)._

## Content
- [ ] **About page** — still the "Coming soon" placeholder. Write copy; it will format itself into the editorial template (use an `eyebrow:` + headline like Perspective/Services).
- [ ] **Blog** — replace the seed post `_posts/2026-06-11-the-first-prompt-is-structural.md` with real content when ready. `_posts/README.md` documents the drop-in workflow.
- [ ] Confirm final **hero copy** and the **Services headline** ("We redesign how your organisation works with AI" was my choice, not supplied).

## Credibility before launch
- [ ] **Source-anchor the Perspective statistics** — BCG 10/20/70, McKinsey "twice as likely", the abandonment-rate doubling, and the EU AI Act figures (€35m / 7%, Aug 2026). Add footnote-style citations or a sources note so they're defensible in front of buyers.
- [ ] **Remove / replace the "still in stealth mode" banner** at launch (`_includes/` + `.stealth-banner`).

## Email
- [ ] **Send a test** to transform@dromologue.com from an external account; confirm it lands in jdfarbuckle@gmail.com.
- [ ] Optional: add a **catch-all** (any @dromologue.com → Gmail) or extra aliases — currently only `transform@` forwards, everything else bounces.
- [ ] Optional: set up **send-as transform@** (SMTP) if outbound from that address is wanted.

## Verification / QA
- [ ] **Check the homepage on a real phone** — the local headless browser couldn't render a trustworthy mobile width. CSS is responsive (hero stacks ≤820px, footer 2-up ≤680px) but unverified on-device.
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
