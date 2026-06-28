# SEO / GEO / AEO Audit Report
## fibrocoach.de
**Audit type:** Full Audit | **Date:** 2026-06-28 | **Auditor:** Claude SEO Skill

---

## Scores at a Glance

| Dimension | Score | Status |
|---|---|---|
| SEO | 7/10 | On Track |
| GEO | 7/10 | On Track |
| AEO | 5/10 | Needs Work |
| **Combined** | **19/30** | **On Track** |

---

## Executive Summary

FibroCoach has a solid technical SEO foundation: canonical tags, Open Graph, Twitter Cards, and a Physician schema with full credentials are all correctly implemented on the homepage. The recently completed URL slug migration (e.g. `/fibromyalgie-selbsttest.html`) improves keyword signal in URLs. The active blog with weekly fibromyalgia content is a significant content asset, and Dr. De Beer's medical credentials are a strong E-E-A-T differentiator.

The most urgent gaps are in structured data and content depth. No page beyond the homepage has any schema markup, and the selbsttest page — which contains 8 question-phrased headings perfectly suited for featured snippets — has no FAQ schema. The leitfaden lead-magnet page has only ~300 words, far too thin for a health topic. The blog living on a subdomain (`blog.fibrocoach.de`) prevents its content from consolidating domain authority onto the main site.

Addressing the AEO gaps (FAQ schema, HowTo schema, direct answer paragraphs) is the highest-leverage opportunity — the site already has the right content structure; it just lacks the markup to surface it in AI Overviews and featured snippets.

---

## Pages Audited

| URL | Page Type | Notes |
|---|---|---|
| https://www.fibrocoach.de/ | Homepage | Rich schema; full OG/Twitter tags |
| https://www.fibrocoach.de/fibromyalgie-selbsttest.html | Self-test tool | ~900 words; no schema |
| https://www.fibrocoach.de/fibrocoach-leitfaden.html | Lead magnet | Thin content (~300 words); no schema |
| https://www.fibrocoach.de/kontakt.html | Contact | NAP partial (no phone); no schema |
| https://www.fibrocoach.de/impressum.html | Legal / Imprint | Standard; no schema needed |
| https://www.fibrocoach.de/datenschutz.html | Privacy policy | References Google Analytics + WebinarJam |
| https://blog.fibrocoach.de | Blog (subdomain) | 11 recent posts; no H1; no Article schema |

---

## SEO Analysis — 7/10

### Technical On-Page

| Signal | Finding | Status |
|---|---|---|
| Title tag — homepage | "FibroCoach – Besser leben mit Fibromyalgie" — 48 chars, primary keyword present | ✅ Good |
| Title tag — selbsttest | "Fibromyalgie Selbsttest – FibroCoach Dr. Kathrin De Beer" — 56 chars | ✅ Good |
| Title tag — leitfaden | "Kostenloser Leitfaden: Fibromyalgie verstehen – FibroCoach Dr. Kathrin De Beer" — **78 chars** (limit is 60) | ⚠️ Needs Attention |
| Title tag — kontakt | "Kontakt – FibroCoach" — 21 chars, very short, no keyword | ⚠️ Needs Attention |
| Meta description — homepage | 160 chars, includes CTA elements, name and specialty | ✅ Good |
| Meta description — selbsttest | 150 chars, includes keyword and doctor name | ✅ Good |
| Meta description — leitfaden | ~143 chars, includes CTA "Jetzt kostenlos anfordern" | ✅ Good |
| Meta description — datenschutz | Not set (legal page — low priority) | ℹ️ Acceptable |
| H1 — homepage | "Endlich echte Unterstützung bei Fibromyalgie – online." — singular, keyword present | ✅ Good |
| H1 — selbsttest | "Was steckt hinter deinen Beschwerden?" — **"Fibromyalgie" not in H1** | ⚠️ Needs Attention |
| H1 — leitfaden | Very long, mirrors title exactly — redundant | ⚠️ Needs Attention |
| H1 — kontakt | "Kontakt" — bare, no keyword value | ⚠️ Acceptable |
| H1 — blog | No H1 detected on blog index page | ⚠️ Needs Attention |
| Heading hierarchy | Homepage H2/H3 logical and relevant; selbsttest H2s are question-phrased | ✅ Good |
| Canonical tags | Present and correctly self-referencing on all 6 main pages | ✅ Good |
| Robots meta | Noindex correctly applied to all 3 danke pages; main pages indexable | ✅ Good |
| robots.txt | All 3 danke pages disallowed; sitemap referenced | ✅ Good |
| Sitemap | 6 URLs, correct filenames after migration, all priorities set | ✅ Good |
| Viewport meta | Present on all pages | ✅ Good |
| lang="de" | Set on all pages | ✅ Good |
| URL structure | Keyword-rich slugs: `/fibromyalgie-selbsttest.html`, `/fibrocoach-leitfaden.html` | ✅ Good |
| HTTPS | Site served over HTTPS | ✅ Good |
| Open Graph tags | Full set (type, url, title, description, image, locale, site_name) on all main pages | ✅ Good |
| Twitter Card | summary_large_image with title, description, image on all main pages | ✅ Good |
| OG image | Same image (`dr_de_beer.jpeg`) used across all pages — consistent branding | ✅ Acceptable |
| Internal links | Navigation links to all key pages from every page | ✅ Good |
| Image alt text | Homepage: "Dr. med. Kathrin De Beer – Fibromyalgie-Spezialistin" — descriptive | ✅ Good |
| Tailwind CDN | Loaded via `<script src="https://cdn.tailwindcss.com">` — **render-blocking JS, hurts Core Web Vitals** | ⚠️ Needs Attention |

### Content Quality

| Signal | Finding | Status |
|---|---|---|
| Homepage word count | Substantial; multiple content sections covering journey, about, webinars, topics, community | ✅ Good |
| Selbsttest word count | ~900–1,000 words; adequate for an interactive tool page | ✅ Good |
| Leitfaden word count | **~280–320 words** — critically thin for a health topic lead-magnet page | ❌ Missing |
| Blog post frequency | 11 posts in May–June 2026; consistent weekly cadence | ✅ Good |
| Blog content relevance | Highly specific fibromyalgia topics: diet, pain, partnership, yoga, exercise — strong semantic coverage | ✅ Good |
| Content freshness | Blog updated weekly; homepage content undated | ✅ Good |
| Readability | Short paragraphs, subheadings, empathetic tone throughout | ✅ Good |
| Keyword density | Primary term "Fibromyalgie" present in titles, headings, body copy across all pages | ✅ Good |

### Structured Data

| Signal | Finding | Status |
|---|---|---|
| Organization schema | Present on homepage with name, URL, logo, contactPoint | ✅ Good |
| Physician schema | Present on homepage: name, image, description, medicalSpecialty, worksFor | ✅ Good |
| WebSite schema | Present on homepage with name, description, publisher | ✅ Good |
| Schema on inner pages | **No schema markup on selbsttest, leitfaden, kontakt, impressum, datenschutz** | ❌ Missing |
| Organization logo field | Uses `dr_de_beer.jpeg` (a photo) — Google expects a logo image, not a headshot | ⚠️ Needs Attention |
| SameAs in Organization | No social profile URLs linked in schema — weakens entity graph | ⚠️ Needs Attention |
| BreadcrumbList schema | Not present on any inner page | ⚠️ Needs Attention |
| FAQ schema | Not present anywhere | ❌ Missing |
| Article schema on blog | Blog is on subdomain; Article schema not confirmed | ⚠️ Needs Attention |

---

## GEO Analysis — 7/10
*GEO = Generative Engine Optimization: optimizing for AI-powered search (Google AI Overviews, Perplexity, ChatGPT Search)*

### E-E-A-T Assessment

| Signal | Finding | Status |
|---|---|---|
| Named author / expert | Dr. med. Kathrin De Beer named prominently on every page | ✅ Good |
| Credentials stated | "Fachärztin für Innere Medizin, Ernährungsmedizin, Mikronährstoffmedizin und Psychotherapie; 15+ Jahre Erfahrung" — in schema and on-page | ✅ Good |
| Medical specialty declared | "Fibromyalgie" as medicalSpecialty in Physician schema | ✅ Good |
| About page / bio | Bio content on homepage; no dedicated /ueber-mich page in sitemap | ⚠️ Needs Attention |
| Contact information | Email and full business address visible on kontakt + impressum | ✅ Good |
| Phone number | **Not listed anywhere** — reduces trust signal | ⚠️ Needs Attention |
| Testimonials / social proof | Pricing section referenced; testimonials not confirmed from fetches | ⚠️ Unverified |
| Institutional affiliation | IQM – Institut für Qualität und Management in der Medizin GmbH — legitimate medical institution | ✅ Good |
| Active content production | Weekly blog output demonstrates ongoing expertise | ✅ Good |

### Content for AI Synthesis

| Signal | Finding | Status |
|---|---|---|
| Factual density | Homepage states specific credentials, years of experience, treatment modalities | ✅ Good |
| Clear value proposition | Stated at top of homepage: "Fachärztlich begleitetes Online-Programm" | ✅ Good |
| External source citations | No citations to medical literature or guidelines visible on any fetched page | ❌ Missing |
| Comprehensiveness | Homepage and selbsttest address topic well; leitfaden page too thin | ⚠️ Needs Attention |
| Entity clarity | "FibroCoach" and "Dr. med. Kathrin De Beer" consistently used across all pages | ✅ Good |
| Original perspective | First-person clinical perspective from a treating physician — differentiating | ✅ Good |
| Blog content as AI citation source | 11 recent posts with specific fibromyalgia subtopics — high citation potential | ✅ Good |

### Technical GEO

| Signal | Finding | Status |
|---|---|---|
| HTTPS | ✓ Secure | ✅ Good |
| robots.txt crawlability | Only danke pages blocked; all content pages open to crawlers | ✅ Good |
| JavaScript rendering | Tailwind CDN loads via JS — content may partially depend on JS rendering | ⚠️ Needs Attention |
| SameAs / brand entity links | **No social profile links in Organization schema** (no Facebook, Instagram, LinkedIn URLs) | ❌ Missing |
| Social links on-page | Not confirmed in fetches — important for entity graph | ⚠️ Unverified |
| Blog on subdomain | `blog.fibrocoach.de` — AI crawlers may not associate blog authority with main domain | ⚠️ Needs Attention |

---

## AEO Analysis — 5/10
*AEO = Answer Engine Optimization: optimizing for featured snippets, People Also Ask, voice search, and AI direct answers*

### Featured Snippet Eligibility

| Signal | Finding | Status |
|---|---|---|
| Direct answer paragraphs | No page opens with a concise 40–60 word definition answering the primary query | ❌ Missing |
| Definition patterns | No "Fibromyalgie ist…" definition sentence near the top of any page | ❌ Missing |
| Question-phrased H2s | Selbsttest has 8 question headings; homepage has question-style H2s ("Erkennst du dich wieder?") | ✅ Good |
| List content | Numbered test questions on selbsttest; topic lists on homepage | ✅ Good |
| Table content | No comparison tables detected | ❌ Missing |

### Structured Answer Formats

| Signal | Finding | Status |
|---|---|---|
| FAQ schema | **Not present on any page** — highest priority gap | ❌ Missing |
| HowTo schema | No HowTo markup (content explaining steps to manage fibromyalgia exists but isn't marked up) | ❌ Missing |
| Speakable schema | Not present | ❌ Missing |
| Question-phrased headings | Present on selbsttest and partially on homepage — structure is correct, markup is missing | ⚠️ Needs Attention |
| BreadcrumbList | Not implemented | ❌ Missing |

### Voice Search Readiness

| Signal | Finding | Status |
|---|---|---|
| Conversational language | Content uses du-form, natural German phrasing throughout | ✅ Good |
| Long-tail question coverage | Blog covers specific questions (e.g. "Gibt es eine Fibromyalgie-Persönlichkeit?") — strong | ✅ Good |
| Main site question coverage | Selbsttest questions cover WPI/SSS criteria but no standalone FAQ page exists | ⚠️ Needs Attention |
| Local signals | Address in Dortmund present on kontakt + impressum | ✅ Good |
| LocalBusiness / MedicalClinic schema | Not implemented despite having NAP data available | ❌ Missing |

---

## Priority Recommendations

| Priority | Issue | Dimension | Effort | Impact |
|---|---|---|---|---|
| 🔴 Critical | Add FAQ schema to selbsttest page — 8 question H2s are ready; just needs JSON-LD wrapper | AEO | Low | Very High |
| 🔴 Critical | Add SameAs social profile URLs to Organization schema (Facebook, Instagram, LinkedIn) | GEO | Low | High |
| 🔴 Critical | Expand leitfaden page content from ~300 to 800+ words — add what the guide contains, why fibromyalgia guidance matters, what readers can expect | SEO | Medium | High |
| 🟠 High | Fix Organization schema "logo" — use an actual logo image, not the doctor headshot | GEO | Low | Medium |
| 🟠 High | Add MedicalClinic or LocalBusiness schema to kontakt page using the NAP data already present | AEO/GEO | Low | Medium |
| 🟠 High | Fix selbsttest H1 — change "Was steckt hinter deinen Beschwerden?" to include "Fibromyalgie" | SEO | Low | Medium |
| 🟠 High | Shorten leitfaden title tag from 78 chars to under 60 | SEO | Low | Medium |
| 🟠 High | Add Article schema to blog posts (name, author, datePublished, description) | GEO/AEO | Medium | High |
| 🟡 Medium | Add BreadcrumbList schema to all inner pages | SEO/AEO | Low | Medium |
| 🟡 Medium | Add a standalone FAQ page (e.g. `/fibromyalgie-faq.html`) with HowTo and FAQ schema | AEO | High | High |
| 🟡 Medium | Consider migrating blog from `blog.fibrocoach.de` to `fibrocoach.de/blog/` — consolidates domain authority | SEO/GEO | High | High |
| 🟡 Medium | Add phone number to kontakt page and Physician/Organization schema | GEO | Low | Medium |
| 🟡 Medium | Add direct answer paragraphs to key pages — open selbsttest with a 50-word definition of fibromyalgie | AEO | Low | Medium |
| 🟢 Quick Win | Add Speakable schema to the most answer-oriented paragraphs on homepage | AEO | Low | Low–Medium |
| 🟢 Quick Win | Add `dateModified` to sitemap entries to signal freshness | SEO | Low | Low |
| 🟢 Quick Win | Cite 1–2 external medical sources (e.g. DGRh guidelines) on the selbsttest page | GEO | Low | Medium |
| 🟢 Quick Win | Add a visible "Zuletzt aktualisiert" date to homepage and selbsttest for freshness signalling | SEO/GEO | Low | Low |

---

## What's Working Well

| Strength | Evidence |
|---|---|
| Complete technical SEO baseline | Canonical, OG, Twitter Cards, robots.txt, sitemap all correctly implemented across every page |
| Strong Physician schema | Homepage declares Dr. De Beer's full credentials in structured data — rare for health sites |
| Keyword-rich URL slugs | `/fibromyalgie-selbsttest.html` and `/fibrocoach-leitfaden.html` embed high-value search terms in the URL |
| Active, topically rich blog | 11 posts in 8 weeks covering specific fibromyalgia subtopics — excellent semantic depth signal |
| Clear entity identity | "FibroCoach" + "Dr. med. Kathrin De Beer" used consistently across all pages and schema |
| Medical credentials prominently stated | "Fachärztin, 15+ Jahre Erfahrung" — strong E-E-A-T signal for a YMYL (Your Money Your Life) health site |
| Empathetic, conversational copy | Du-form, patient-centric language — excellent for voice search and engagement |
| Thank-you pages properly excluded | All 3 danke pages have noindex + robots.txt Disallow — clean crawl budget |

---

## Glossary

**SEO (Search Engine Optimization):** The practice of optimizing a website so that traditional search engines like Google rank it higher in search results for relevant queries.

**GEO (Generative Engine Optimization):** Optimizing content so that AI-powered search tools (Google AI Overviews, Perplexity, ChatGPT Search) select and cite your pages when generating synthesized answers. Rewards factual density, authority signals, and entity clarity.

**AEO (Answer Engine Optimization):** Optimizing for featured snippets, People Also Ask boxes, and voice assistants that need to extract a direct, concise answer from your page. Rewards question-formatted headings, FAQ schema, and short definition paragraphs.

**E-E-A-T:** Experience, Expertise, Authoritativeness, Trustworthiness — Google's framework for assessing content quality, especially critical for health (YMYL) topics.

**Schema / Structured Data:** JSON-LD code added to a page's `<head>` that tells search engines and AI tools exactly what the page is about — who the author is, what type of content it contains, what questions it answers.

---

*Report generated by Claude SEO/GEO/AEO Skill · fibrocoach.de · 2026-06-28*
