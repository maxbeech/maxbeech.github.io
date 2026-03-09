# Monthly SEO Keyword Strategy Review (getathenic.com)

**Review date:** 2026-03-09  
**Primary goal:** identify keyword opportunities to grow *qualified organic traffic* and improve click-through-rate (CTR) on high-impression pages.

## Data sources used (this month)

1. **Google Search Console** (last 28 days: **2026-02-09 → 2026-03-07**, vs previous 28 days: **2026-01-12 → 2026-02-08**)
2. **Google Ads Keyword Planner**: *attempted but blocked by API configuration error* (invalid Google Ads Customer ID formatting). This document therefore uses Search Console as the ground truth for “real demand we’re already showing for”, which is typically more actionable than planner estimates.

---

## Executive summary (what changed this month)

### 1) Biggest immediate upside: improve CTR on pages already ranking in positions ~5–8
Several pages have **very large impression volume** and **average position inside the top 10**, but **CTR near ~0.05%–0.08%**. This is usually a snippet + intent-match problem (title/meta, SERP features, missing “pricing / free tier / 2026” modifiers).

**Top CTR-upside pages (last 28 days):**

| Page | Clicks | Impressions | CTR | Avg position |
|---|---:|---:|---:|---:|
| /blog/vercel-vs-railway-vs-render-ai-deployment | 10 | 18,628 | 0.054% | 6.40 |
| /blog/stripe-vs-paddle-vs-lemon-squeezy-saas-billing | 10 | 13,268 | 0.075% | 6.36 |
| /blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison | 3 | 22,400 | 0.013% | 5.84 |
| /blog/supabase-vs-firebase-vs-convex-ai-backend | 5 | 6,593 | 0.076% | 7.03 |
| /blog/pinecone-vs-weaviate-vs-qdrant-vs-chroma-vector-search | 4 | 5,330 | 0.075% | 7.56 |

### 2) Notable “trend / emergence” signals
Compared to the prior 28 days, the site started showing meaningful demand for:

- **railway vs vercel**: 238 impressions (was 4) → *major jump*.
- **paddle vs lemon squeezy** and related Lemon Squeezy fee/pricing variants → *new and growing set*.
- Continued demand for **e2b vs modal** and related runtime/sandbox comparisons.

### 3) Service terms (“bespoke web design”) are not currently competitive
The page `/blog/bespoke-web-design-complete-guide-2026` is currently showing **very low impressions** and **very weak average positions** for the core head terms:

- “bespoke web design” (avg position ~80)
- “bespoke web development” (avg position ~93)

This suggests the site’s topical authority is currently stronger around “X vs Y” comparison queries than around agency/service terms. If bespoke web design remains a core revenue driver, we need **dedicated landing pages** + **supporting cluster content**.

---

## Updated keyword clusters (prioritized)

### Cluster A (P0): Deployment platforms for apps/AI workloads
**Why P0:** highest impressions, page already ranks in top 10; CTR is extremely low.

**Core keywords (observed demand):**
- railway vs vercel (238 impressions, pos ~3.5)
- vercel vs railway (165 impressions, pos ~4.45)
- railway vs vercel comparison 2026 (50 impressions, pos ~4.74)
- railway free tier limits 2026 (18 impressions, pos ~10.78)
- railway vs render pricing 2026 (11 impressions, pos ~9.91)

**Page mapping:**
- Primary: `/blog/vercel-vs-railway-vs-render-ai-deployment`

**Recommendations (next 30 days):**
- Rewrite title/meta to explicitly include **“Railway vs Vercel (2026)”** and one differentiator: *pricing*, *free tier*, *DX*, *long-running services*, *AI workloads*.
- Add a short **“2026 pricing / free tier”** section near the top; many query modifiers indicate price sensitivity.
- Add FAQ section targeting: “Is Railway cheaper than Vercel?”, “Does Railway support GPUs?”, “Railway free tier limits 2026”.

---

### Cluster B (P0): SaaS billing / Merchant of Record comparisons
**Why P0:** very high impressions; many query variants around pricing/fees.

**Core keywords (observed demand):**
- paddle vs lemon squeezy (120 impressions, pos ~7.83)
- lemon squeezy vs paddle (96 impressions, pos ~7.40)
- lemon squeezy vs paddle vs stripe (31 impressions, pos ~5.97)
- compare stripe tax vs paddle (39 impressions, pos ~6.62)
- lemon squeezy pricing 5% + $0.50 (17 impressions, pos ~10.35)

**Page mapping:**
- Primary: `/blog/stripe-vs-paddle-vs-lemon-squeezy-saas-billing`

**Recommendations (next 30 days):**
- Tighten snippet to match intent: include “**fees**”, “**Merchant of Record**”, “**Stripe Tax**”, and “**pricing (2026)**”.
- Add a “Fees calculator” style table (even static) to win clicks for the recurring “5% + $0.50” searches.
- Add internal links from adjacent finance content (Atlas article) using anchors like “paddle vs lemon squeezy” and “merchant of record”.

---

### Cluster C (P0): Backend-as-a-Service (BaaS) decisions (Supabase / Convex / Firebase)
**Why P0:** clear head-term demand with solid positions (~3–5) but near-zero CTR → snippet mismatch.

**Core keywords (observed demand):**
- convex vs supabase (290 impressions, pos ~4.56)
- supabase vs convex (186 impressions, pos ~4.76)
- convex vs firebase (40 impressions, pos ~7.9)
- convex vs firebase vs supabase (30 impressions, pos ~6.87)

**Page mapping:**
- Primary: `/blog/supabase-vs-firebase-vs-convex-ai-backend`

**Recommendations (next 30 days):**
- Adjust title to explicitly include “**Convex vs Supabase**” (since that’s the dominant head-to-head in Search Console).
- Add a “Who should choose Convex vs Supabase?” block at the top.
- Add FAQ: “Is Convex better than Supabase?”, “Convex pricing vs Firebase”, “Supabase to Convex migration”.

---

### Cluster D (P1): API testing tools (Postman / Insomnia / Bruno)
**Why P1:** consistent clicks, but there are still many variants you can capture with better intent alignment.

**Core keywords (observed demand):**
- insomnia vs bruno (116 impressions, 3 clicks, pos ~6.07)
- postman vs insomnia vs bruno (59 impressions, 2 clicks, pos ~2.97)
- bruno vs postman vs insomnia (72 impressions, 2 clicks, pos ~3.58)

**Page mapping:**
- Primary: `/blog/postman-vs-insomnia-vs-bruno-api-testing`

**Recommendations:**
- Add sections for “Bruno vs Postman” and “Insomnia vs Postman” as explicit H2s; those variants show up with impressions but low clicks.

---

### Cluster E (P2): Bespoke web design / custom website (commercial intent)
**Why P2:** this is commercial-intent but currently not ranking well.

**Observed keywords (low visibility):**
- bespoke web design (3 impressions, avg pos ~80)
- bespoke web development (1 impression, avg pos ~93)

**Page mapping:**
- Current: `/blog/bespoke-web-design-complete-guide-2026`

**Recommendations (strategy shift):**
- Create a **dedicated landing page** (not a blog post) targeting: “Bespoke web design”, “custom web design”, “bespoke website”, “web design for startups”.
- Build supporting cluster posts:
  - “Custom website vs template: ROI breakdown”
  - “Website redesign checklist (2026)” (already exists—strengthen internal linking)
  - “Next.js website builder guide” (already exists—link to bespoke landing page)

---

## Deprioritize / exclude (this month)

These are showing in Search Console but are either noise, low relevance, or not aligned to the site’s strategy:

- One-word/no-intent queries: `english`, `yes`
- Very long prompt-like “evaluate the company…” queries (likely LLM-generated searches). Treat as **non-primary**; do not build pages specifically for them.
- Misspellings with negligible volume (`anthenic`, `athenics`) → handle via minor copy tweaks if desired, but don’t prioritize.

---

## 30-day action plan (SEO execution)

1. **CTR sprint (highest ROI):** update titles/meta + top-of-article summaries for the P0 clusters (Deployment, Billing, BaaS). Target +0.3% CTR on the two biggest pages.
2. **Create 2 supporting pages** to capture modifiers already showing:
   - “Railway free tier limits (2026)” (or add as dedicated section + jump links)
   - “Lemon Squeezy fees: 5% + $0.50 explained (with examples)”
3. **Commercial page build:** add a bespoke web design landing page + internal links from the high-traffic comparison posts.

---

## Notes / issues

- **Google Ads Keyword Planner API is currently failing** due to an invalid configured customer ID. Fixing this will let us enrich these clusters with **net-new keywords** that aren’t yet appearing in Search Console.
