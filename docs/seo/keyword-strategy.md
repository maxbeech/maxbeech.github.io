# Monthly SEO Keyword Strategy Review (getathenic.com)

**Review date:** 2026-03-23  
**Primary goal:** identify keyword opportunities to grow *qualified organic traffic* and improve click-through-rate (CTR) on high-impression pages.

## Data sources used (this review)

1. **Google Search Console** (last 28 days: **2026-02-23 → 2026-03-22**, vs previous 28 days: **2026-01-26 → 2026-02-22**)
2. **Google Ads Keyword Planner**: attempted again, but the API integration is still failing due to an invalid configured Google Ads Customer ID.

**Keyword Planner error (actionable fix):**
- Error returned by API: `GOOGLE_ADS_CUSTOMER_ID is invalid: "476-798-8021\n"` (note the trailing newline)
- Fix: update the configured customer ID to a valid **10-digit** value *with no whitespace/newlines* (dashes are fine: `123-456-7890`).

---

## Executive summary (what changed vs last 28-day period)

### 1) New #1 opportunity by raw impressions: “best ecommerce platform” comparison page is now massive
The page `/blog/best-ecommerce-platform-comparison-2026` is now one of the highest-impression URLs on the site **while already ranking on page 1**.
- **0 clicks / 29,719 impressions / 0.00% CTR / avg position 4.88**

This is a pure CTR + snippet-intent match problem.

### 2) Breakout click winner: Postman vs Insomnia vs Bruno
This page is now the top click driver.
- **47 clicks / 4,625 impressions / 1.02% CTR / avg position 7.04**

Expand this cluster with single-head-to-head pages that match the exact “X vs Y” demand.

### 3) Continued pattern: comparison pages rank ~5–7 with huge impressions but near-zero CTR
The same pattern continues across:
- Claude vs GPT-4o vs Gemini
- Vercel vs Railway vs Render
- Stripe vs Paddle vs Lemon Squeezy

These are already in the top 10. CTR is the bottleneck.

### 4) Marketing automation (AI features) demand is real, but the snippet is not winning clicks
`/blog/hubspot-activecampaign-ai-agents-comparison` is earning meaningful visibility, dominated by queries like **“activecampaign vs hubspot ai features comparison (2026)”**, but still **0 clicks**.
- **0 clicks / 3,537 impressions / 0.00% CTR / avg position 8.63**

---

## Biggest immediate upside: CTR improvement on pages already ranking in positions ~4–8

**Top CTR-upside pages (last 28 days):**

| Page | Clicks | Impressions | CTR | Avg position |
|---|---:|---:|---:|---:|
| /blog/best-ecommerce-platform-comparison-2026 | 0 | 29,719 | 0.000% | 4.88 |
| /blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison | 9 | 34,302 | 0.026% | 6.05 |
| /blog/vercel-vs-railway-vs-render-ai-deployment | 15 | 26,714 | 0.056% | 6.59 |
| /blog/stripe-vs-paddle-vs-lemon-squeezy-saas-billing | 13 | 18,794 | 0.069% | 6.26 |
| /blog/langchain-vs-llamaindex-vs-haystack-rag-frameworks | 2 | 10,936 | 0.018% | 6.80 |
| /blog/anthropic-claude-vs-openai-gpt4-vs-google-gemini | 2 | 10,212 | 0.020% | 6.51 |
| /blog/best-ai-for-business-comparison-2026 | 2 | 10,331 | 0.019% | 7.09 |
| /blog/pinecone-vs-weaviate-vs-qdrant-vs-pgvector | 8 | 12,265 | 0.065% | 6.90 |
| /blog/human-in-the-loop-approval-workflows | 0 | 4,203 | 0.000% | 7.94 |
| /blog/hubspot-activecampaign-ai-agents-comparison | 0 | 3,537 | 0.000% | 8.63 |

**What this means in clicks (illustrative):**
- If `/blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison` moves from **0.026% → 0.20% CTR**, that’s roughly **+60 clicks / 28 days** at current impressions.
- If `/blog/vercel-vs-railway-vs-render-ai-deployment` moves from **0.056% → 0.20% CTR**, that’s roughly **+38 clicks / 28 days**.
- If `/blog/best-ecommerce-platform-comparison-2026` reaches **0.10% CTR**, that’s roughly **+30 clicks / 28 days**.

---

## Biggest movers (last 28 days vs previous 28 days)

| Page | Clicks (prev → now) | Impressions (prev → now) | Note |
|---|---:|---:|---|
| /blog/postman-vs-insomnia-vs-bruno-api-testing | 1 → 47 | 106 → 4,625 | breakout winner; expand variants |
| /blog/linear-vs-height-vs-plane-project-management | 0 → 35 | 59 → 2,755 | new high-performing cluster |
| /blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison | 0 → 9 | 3,683 → 34,302 | massive visibility; CTR now the bottleneck |
| /blog/vercel-vs-railway-vs-render-ai-deployment | 3 → 15 | 4,709 → 26,714 | huge visibility gain; snippet underperforming |
| /blog/stripe-vs-paddle-vs-lemon-squeezy-saas-billing | 4 → 13 | 3,198 → 18,794 | major impression growth; CTR now the bottleneck |
| /blog/best-ecommerce-platform-comparison-2026 | 0 → 0 | 472 → 29,719 | top-5 average position; snippet not converting |
| /blog/hubspot-activecampaign-ai-agents-comparison | 0 → 0 | 340 → 3,537 | demand is rising; needs title/meta + above-fold table |
| /blog/e2b-vs-modal-vs-flyio-sandbox-comparison | 39 → 10 | 3,706 → 4,258 | clicks down sharply; monitor ranking + intent drift |

---

## Updated keyword clusters (prioritized)

### Cluster A (P0): Ecommerce platform comparisons (2026)
**Why P0:** one page is already ranking **avg position ~4.9** with **~30k impressions** and **0 clicks**.

**Page mapping (primary):**
- `/blog/best-ecommerce-platform-comparison-2026`

**Observed query patterns to capture (Search Console):**
- `woocommerce vs shopify vs bigcommerce` (and “vs wix / squarespace” variants)
- `best dropshipping platforms 2026 comparison shopify vs woocommerce vs bigcommerce vs wix`
- `best bigcommerce alternatives 2026`

**Recommendations (next 30 days):**
- Rewrite title/meta to be *decision-first* and include the dominant entities:
  - Suggested: **“Shopify vs WooCommerce vs BigCommerce (2026): pricing, SEO, features (best ecommerce platform)”**
- Add an above-the-fold comparison table that literally repeats the head terms: *Shopify*, *WooCommerce*, *BigCommerce*, *Wix*, *Squarespace*.
- Add a “Pick the winner by use case” block (dropshipping, B2B, clothing, food, bookstore, enterprise).

**Supporting pages to consider (if impressions persist):**
- `Shopify vs WooCommerce vs BigCommerce (2026)` (more focused than the mega-roundup)
- `Best BigCommerce alternatives (2026)`
- `Best dropshipping platforms (2026): Shopify vs WooCommerce vs Wix`

---

### Cluster B (P0): LLM model comparisons (Enterprise: Claude vs GPT-4o vs Gemini)
**Why P0:** the page is one of the top impression earners on the site with avg position ~6.

**Page mapping (primary):**
- `/blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison`

**Observed modifiers to capture:**
- `best coding llm claude vs gpt-4o vs gemini`
- `best ai model for data scraping claude vs gpt-4o vs gemini`

**Important nuance:** this page is also appearing for extremely broad multilingual “best AI” queries. That inflates impressions but drags CTR.

**Recommendations:**
- Tighten the promise in the title/meta to match *enterprise comparison intent* (and reduce “generic best AI” mismatch):
  - Suggested: **“Claude vs GPT-4o vs Gemini (Enterprise) (2026): price, context, latency, benchmarks”**
- Add a “Use cases” jump table near the top (coding, long-doc parsing, scraping/extraction, RAG).
- Add FAQ sections with exact match H3s for the modifiers above.

---

### Cluster C (P0): Deployment platforms for apps/AI workloads (Vercel vs Railway vs Render)
**Why P0:** huge impressions, avg position ~6.6, CTR ~0.06%.

**Page mapping (primary):**
- `/blog/vercel-vs-railway-vs-render-ai-deployment`

**Recommendations:**
- Add a visible **Pricing / Free tier limits (2026)** table above the fold.
- Add FAQ targeting: “Railway free tier limits 2026”, “Railway vs Render pricing 2026”, “Does Railway support GPUs?”

**Supporting page (still recommended):**
- `Railway free tier limits (2026): what you get + when you pay`

---

### Cluster D (P0): SaaS billing / Merchant of Record (Stripe vs Paddle vs Lemon Squeezy)
**Why P0:** very high impressions; strong “fees/pricing” intent; CTR is extremely low.

**Page mapping (primary):**
- `/blog/stripe-vs-paddle-vs-lemon-squeezy-saas-billing`

**Recommendations:**
- Add a fee-breakdown table with explicit wording people repeat: **“5% + $0.50”**.
- Add a dedicated section: “Stripe Tax vs Paddle: what’s different?”

**Supporting page (still recommended):**
- `Lemon Squeezy pricing explained: 5% + $0.50 (examples + calculator)`

---

### Cluster E (P0): Marketing automation AI features (HubSpot vs ActiveCampaign)
**Why P0:** sustained visibility with **0 clicks**, dominated by “AI features comparison (2026)” queries.

**Page mapping (primary):**
- `/blog/hubspot-activecampaign-ai-agents-comparison`

**Observed queries to mirror in headings/FAQ:**
- `activecampaign vs hubspot ai features comparison 2025 or 2026` (271 impressions)
- `activecampaign vs hubspot cross-channel marketing automation comparison 2025 or 2026`
- `activecampaign vs hubspot pricing comparison 2025 or 2026`

**Recommendations:**
- Title/meta must explicitly include **AI features** + **marketing automation** + **2026**.
- Add an above-the-fold table with columns: AI features, segmentation/personalization, workflows, deliverability, reporting, pricing.
- Add FAQ blocks for pricing + deliverability + personalization queries.

---

### Cluster F (P1): API testing tools (Postman vs Insomnia vs Bruno)
**Why P1:** currently the top click driver; expand to capture single head-to-head intent.

**Page mapping (primary):**
- `/blog/postman-vs-insomnia-vs-bruno-api-testing`

**Next pages to add (based on observed demand):**
- `Insomnia vs Bruno (2026)`
- `Postman vs Bruno (2026)`

---

### Cluster G (P1): Project management tools (Linear vs Plane vs Height)
**Why P1:** strong click volume; multiple exact-match queries are already converting.

**Page mapping (primary):**
- `/blog/linear-vs-height-vs-plane-project-management`

**Next pages to add:**
- `Linear vs Plane (2026)`
- `Linear vs Height (2026)`

---

### Cluster H (P1): Human-in-the-loop approval workflows (AI)
**Why P1:** strong impression volume with 0 clicks; likely salvageable with better snippet + clearer “what you’ll learn” framing.

**Page mapping (primary):**
- `/blog/human-in-the-loop-approval-workflows`

**Recommendations:**
- Retitle toward “approval workflows for AI agents” and add an above-the-fold pattern library.

---

### Cluster I (P2): Vector database comparisons
**Why P2:** high impressions; CTR improvement still useful but secondary to the P0 clusters.

**Page mapping:**
- `/blog/pinecone-vs-weaviate-vs-qdrant-vs-pgvector`
- `/blog/pinecone-vs-weaviate-vs-qdrant-vector-databases`

---

## Deprioritize / exclude (this month)

1. **One-word/no-intent queries**: `english`, `yes`, and other noise.
2. **Prompt-like “evaluate the company…” queries**: treat as non-primary.
3. **Quoted code/token queries** (e.g. library import strings): these create impressions but rarely drive qualified traffic. Avoid optimizing titles/meta toward these; keep content readable and well-structured.

---

## 30-day action plan (SEO execution)

1. **CTR sprint (highest ROI):** update titles/meta + add above-the-fold summary blocks for:
   - Best ecommerce platform comparison (2026)
   - Claude vs GPT-4o vs Gemini
   - Vercel vs Railway vs Render
   - Stripe vs Paddle vs Lemon Squeezy
   - HubSpot vs ActiveCampaign (AI features)
   - Human-in-the-loop approval workflows

2. **Publish 2–3 supporting pages** (targeting the clearest modifiers already visible in Search Console):
   - Shopify vs WooCommerce vs BigCommerce (2026)
   - Railway free tier limits (2026)
   - Lemon Squeezy pricing (5% + $0.50) explained

3. **Expand winning clusters:** publish 2 lightweight head-to-heads:
   - Insomnia vs Bruno
   - Linear vs Plane (or Linear vs Height)

4. **Unblock Keyword Planner (platform-level):** fix the Google Ads customer ID configuration so we can enrich these clusters with net-new keywords that aren’t yet appearing in Search Console.

---

## Appendix: previous review snapshot (2026-03-19)

The previous review content has been superseded by this update; see git history for the full prior snapshot.
