# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

FibroCoach is a static German-language marketing website for Dr. med. Kathrin De Beer, a fibromyalgia specialist. No build tools, no npm, no framework — just HTML files opened directly in a browser.

## Development

There is no build step. Open any `.html` file directly in a browser, or serve locally:

```bash
python3 -m http.server 8000
```

## Architecture

All pages are self-contained HTML files. Each page duplicates the same Tailwind config block (teal palette + Figtree font) and navigation markup — there is no shared template or component system.

**Page inventory:**
- `index.html` — main landing page; sections anchored at `#reise`, `#ueber-mich`, `#webinare`, `#themen`, `#newsletter`
- `selbst-test.html` — interactive fibromyalgia self-test (WPI/SSS criteria); all logic is vanilla JS inline at the bottom
- `leitfaden.html` — free guide lead-magnet page
- `danke.html` — newsletter confirmation page (`noindex`)
- `impressum.html`, `datenschutz.html`, `kontakt.html` — legal/contact pages
- `archive/` — previous design iterations (not linked from live site)

## Design system

Tailwind Play CDN is used (not installed via npm). The config is copy-pasted into every page's `<script>` block. When updating colors or fonts, update **all pages**.

Key values:
- **Teal palette**: `teal-500 = #2DC9A8`, `teal-600 = #22A88C`, `teal-700 = #187060`
- **Text**: `#1A1A1A` (headings), `#333333` (body), `#6B7280` / `gray-500` (muted)
- **Font**: Figtree (Google Fonts)
- **Max width**: `max-w-[1200px]`
- **Fixed nav height**: `72px` — body has `pt-[72px]`, `scroll-padding-top: 72px`
- **Border/divider**: `#E8E8E8`

## External integrations

- **Community platform**: `https://fibrocoach.app.mentortools.com/app/login/` (MentorTools)
- **Blog**: `https://blog.fibrocoach.de`
- CTA buttons throughout link to `selbst-test.html` or the MentorTools community

## Conventions

- All content is in German.
- Navigation markup (desktop + mobile menu + hamburger JS) is duplicated per page. On inner pages, nav links use `index.html#section` anchors; on `index.html` they use bare `#section` anchors.
- Accessibility: every page has a skip link, `role="banner"`, `aria-label` on nav, and `aria-hidden` on decorative SVGs.
