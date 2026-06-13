# dromologue.com — outstanding work

_Last updated: 2026-06-13. Site is **pre-launch** ("still in stealth mode" banner is intentional)._

## Content

- [ ] **About page** — still the "Coming soon" placeholder. Write copy; formats into the editorial template (`eyebrow:` + headline, same as Perspective/Services).
- [ ] **Confirm Services headline** — "We redesign how your organisation works with AI" was AI-chosen, still to confirm. Hero headline confirmed.

## Credibility before launch

- [x] **Source-anchor the Perspective statistics** — done 2026-06-12. Inline links to S&P Global, BCG, McKinsey, EUR-Lex; corrected McKinsey ("nearly three times") and EU AI Act penalty framing.
- [x] **McKinsey stat consistency noted** — essay says "twice as likely"; Perspective says "nearly three times". Left as-is (essay is Justin's wording). Align before wide promotion.
- [ ] **Remove "still in stealth mode" banner** at launch — in `_layouts/home.html` and `_layouts/post.html`.

## Email and forms

- [x] **transform@dromologue.com forwarding** — working (ForwardEmail DNS, confirmed 2026-06-12).
- [x] **Contact form** at `/contact/` — Netlify Forms, `contact` form registered and capturing, redirect to `/contact/thanks/`.
- [ ] **Add email notification** for form submissions: Netlify → dromologue-site → Forms → `contact` → Settings & notifications → email to transform@dromologue.com. (Submissions land in the Netlify Forms dashboard until this is done.)
- [ ] Optional: catch-all alias (any @dromologue.com → Gmail) or extra aliases — only `transform@` currently forwards.
- [ ] Optional: send-as transform@ (SMTP) for outbound from that address.

## SEO

- [x] Per-page `description:` front matter on all pages.
- [x] `author: dromologue` in `_config.yml` JSON-LD.
- [x] Cross-link from Perspective → "Two Clocks" post.
- [x] Removed organisationalprompts.ai from `sameAs` structured data.
- [ ] **Submit sitemap to Google Search Console** — `<https://dromologue.com/sitemap.xml>` is live; submit once site goes public.
- [ ] **Validate OG share card** via LinkedIn Post Inspector / X card validator.
- [ ] **Write the About page** — highest E-E-A-T signal for a solo practice.
- [ ] **Publish more posts** — "Two Clocks" is the only indexed content; each new substantive post compounds.

## Blog and tags

- [x] **Tag system** — `tags:` in front matter, Topics cloud in sidebar, JS filtering, tag chips on feed and post pages.
- [ ] **Review tag taxonomy** — current tags on "Two Clocks": `ai-strategy`, `operating-model`, `transformation`, `regulation`. Adjust as more posts arrive.

## Verification / QA

- [x] **Check on real phone** — confirmed working (2026-06-12).
- [ ] **Human click-through of Perspective source links** — corporate domains block bots; URLs confirmed to exist but destination content not auto-verified.
- [ ] **Test contact form end to end** — submit a real message from `/contact/`, confirm it lands in Netlify Forms dashboard (and email once notification is configured).
- [ ] **Re-check colour contrast** if any brand colours change (text uses darkened `--bronze-ink`; bright bronze reserved for decorative elements).

## Optional polish

- [ ] J-curve diagram: decide whether to re-add the "a modest gain above the start, then flat" annotation (dropped for clarity).
- [ ] OG image: `og-default.png` is a 50KB placeholder. A proper branded share card (1200×630px) would improve LinkedIn/X unfurls.

---

## Completed (2026-06)

- Rebrand: navy/bronze/paper + Inter; D mark favicon.
- Homepage: asymmetric hero, strapline as banner-explainer under wordmark, CTA button → /contact/, latest-article panel, sectioned footer.
- Etymology line: "What is a dromologue?" inline in footer (label + explanation side by side, new wording).
- Blog: drop-in `_posts/`, two-column layout with sidebar, tag cloud + JS filtering.
- "Two Clocks" essay published (3,000 words, four tags, standfirst, sources note).
- Our Perspective + Services pages with editorial formatting, J-curve SVG, source links.
- SEO foundations: jekyll-seo-tag, jekyll-sitemap, per-page meta, OG/Twitter cards, robots.txt.
- Contact form at /contact/ (Netlify Forms, honeypot, thanks page).
- Email forwarding: transform@dromologue.com → jdfarbuckle@gmail.com.
- Hairline CSS variable fixed (was self-referential, silently broke all dividers).
- Branch renamed master → main; Netlify webhook auto-deploys on push.
- Removed Organisational Prompts link site-wide (footer, sidebar, blog hub, SEO sameAs).
- Footer links renamed: Concepto → Take a break; Concept Mapper → Thinking Tools.
