# Monthly SEO Keyword Strategy Review (getathenic.com)

**Review date:** 2026-04-18  
**Primary goal:** identify keyword opportunities to grow *qualified organic traffic* and improve click-through-rate (CTR) on high-impression pages.

## Data sources used (this review)

1. **Google Search Console** (last 28 days: **2026-03-21 → 2026-04-17**, vs previous 28 days: **2026-02-21 → 2026-03-20**)
2. **Google Ads Keyword Planner**: attempted, but the API call is failing due to missing Google Ads permissions/scope.

**Keyword Planner error (actionable fix):**
- Error returned by API: `Insufficient permissions` (missing `https://www.googleapis.com/auth/adwords` scope)
- Fix:
  - Re-authenticate the Google connection with the **Google Ads / adwords** OAuth scope enabled.
  - Ensure the Google Ads **developer token** + Ads account linkage is valid for the authenticated user.

---

## Executive summary (what changed vs last 28-day period)

### 1) Ecommerce mega-comparison still dominates impressions — but rankings slipped
`/blog/best-ecommerce-platform-comparison-2026` remains one of the highest-impression pages on the site, but average position fell.
- **0 clicks / 19,557 impressions / 0.00% CTR / avg position 6.25**
- Previous period: **0 clicks / 28,757 impressions / 0.00% CTR / avg position 4.88**

This is still a *massive* opportunity, but it now needs a ranking + CTR recovery: tighter intent match, a better title/meta promise, and an above-the-fold “winner-by-use-case” block.

### 2) Deployment platforms comparison lost most of its clicks
`/blog/vercel-vs-railway-vs-render-ai-deployment` declined sharply.
- **2 clicks / 20,623 impressions / 0.01% CTR / avg position 7.14**
- Previous period: **15 clicks / 27,242 impressions / 0.06% CTR / avg position 6.56**

The query mix is increasingly “prompt-like” (long evaluation prompts), which inflates impressions but doesn’t convert. We should support this page with *exact-match* head-to-head pages.

### 3) Breakout winner: TypeScript vs Python startup stack
`/blog/typescript-vs-python-startup-stack` is now a meaningful click driver.
- **19 clicks / 5,532 impressions / 0.34% CTR / avg position 5.20**
- Previous period: **8 clicks / 4,964 impressions / 0.16% CTR / avg position 5.71**

This cluster is worth expanding (especially “for AI agents” modifiers).

### 4) “X vs Y vs Z” comparison queries continue to be the most reliable click generators
Top converting queries are still comparisons like:
- **“plane vs linear”**
- **“bruno vs postman vs insomnia”**

…but several of these are down vs last period, which is a signal to ship *single head-to-head pages* (Plane vs Linear, Postman vs Bruno, Insomnia vs Bruno) to defend and grow.

---

## Biggest immediate upside: CTR improvement on pages already ranking in positions ~4–9

**Top CTR-upside pages (last 28 days):**

| Page | Clicks | Impressions | CTR | Avg position |
|---|---:|---:|---:|---:|
| /blog/best-ecommerce-platform-comparison-2026 | 0 | 19,557 | 0.000% | 6.25 |
| /blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison | 6 | 24,752 | 0.024% | 6.58 |
| /blog/vercel-vs-railway-vs-render-ai-deployment | 2 | 20,623 | 0.010% | 7.14 |
| /blog/stripe-vs-paddle-vs-lemon-squeezy-saas-billing | 15 | 18,554 | 0.081% | 6.45 |
| /blog/pinecone-vs-weaviate-vs-qdrant-vs-pgvector | 8 | 13,564 | 0.059% | 7.71 |
| /blog/langchain-vs-llamaindex-vs-haystack-rag-frameworks | 2 | 10,936 | 0.018% | 6.80 |
| /blog/anthropic-claude-vs-openai-gpt4-vs-google-gemini | 1 | 3,124 | 0.032% | 6.67 |
| /blog/ai-website-builder-comparison-2026 | 1 | 7,381 | 0.014% | 6.52 |
| /blog/best-website-builder-comparison-2026 | 1 | 5,903 | 0.017% | 7.20 |
| /blog/hubspot-activecampaign-ai-agents-comparison | 0 | 2,033 | 0.000% | 8.66 |

---

## Biggest movers (last 28 days vs previous 28 days)

| Page | Clicks (prev → now) | Impressions (prev → now) | Note |
|---|---:|---:|---|
| /blog/typescript-vs-python-startup-stack | 8 → 19 | 4,964 → 5,532 | breakout; expand “for AI agents” modifiers |
| /blog/vercel-vs-railway-vs-render-ai-deployment | 15 → 2 | 27,242 → 20,623 | major decline; needs exact-match support pages |
| / | 20 → 9 | 1,207 → 1,075 | monitor branded demand + snippet |
| /blog/linear-vs-height-vs-plane-project-management | 35 → 28 | 2,695 → 2,836 | impressions up but CTR down |
| /blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison | 9 → 6 | 34,777 → 24,752 | still huge visibility; CTR remains bottleneck |

---

## Updated keyword clusters (prioritized)

### Cluster A (P0): Ecommerce platform comparisons (2026)
**Why P0:** still a top impression driver with **0 clicks**, even while ranking on page 1.

**Page mapping (primary):**
- `/blog/best-ecommerce-platform-comparison-2026`

**Observed query patterns to capture (Search Console, this month):**
- `best e-commerce platforms 2026 woocommerce vs shopify vs bigcommerce` (**positions ~2–3 on some variants, 0 clicks**)
- `best dropshipping platforms 2026 comparison shopify vs woocommerce vs bigcommerce vs wix` (position ~1–3, 0 clicks)
- `best bigcommerce alternatives 2026`
- `adobe commerce vs shopify vs bigcommerce vs woocommerce 2026` (emerging modifier)

**Recommendations (next 30 days):**
- Rewrite title/meta to aggressively match the dominant entities (Shopify/Woo/BigCommerce/Wix/Squarespace) and the “2026” modifier.
- Add an above-the-fold “Pick the winner by use case” block:
  - dropshipping, B2B, clothing, creator store, enterprise, SEO-first.
- Add FAQ sections with exact-match headings:
  - “Best ecommerce platform for SEO (2026)”, “Best ecommerce platform for dropshipping (2026)”, etc.

**Supporting pages to consider (high leverage):**
- `Shopify vs WooCommerce vs BigCommerce (2026)` (focused head terms)
- `BigCommerce alternatives (2026)`
- `Best dropshipping platforms (2026): Shopify vs WooCommerce vs Wix`

---

### Cluster B (P0): LLM model comparisons (Enterprise: Claude vs GPT-4o vs Gemini)
**Why P0:** extremely high impressions; CTR remains near-zero.

**Page mapping (primary):**
- `/blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison`

**Observed modifiers (this month):**
- `best llm for pdf to markdown ...`
- `best ai model for web scraping ...`
- `best ai for coding 2026 ...`

**Recommendations:**
- Tighten title/meta toward “enterprise model comparison” and add a 5-line summary above the fold.
- Add a use-case jump table (coding, long-doc parsing, scraping/extraction, RAG, vision).
- Add a “winner by use case” section that mirrors the modifiers above.

---

### Cluster C (P0): Deployment platforms for apps/AI workloads (Vercel vs Railway vs Render)
**Why P0:** huge impressions and a big period-over-period click collapse.

**Page mapping (primary):**
- `/blog/vercel-vs-railway-vs-render-ai-deployment`

**Observed query patterns:**
- `railway vs vercel` (**201 impressions / 1 click / avg position ~3.6**) → this should be its own page.
- `railway gpu support 2026` (meaningful impressions, 0 clicks)
- `railway free tier limits 2026` (small but high-intent)

**Recommendations:**
- Add a “Vercel vs Railway: quick answer” block above the fold + a pricing/free-tier table.
- Publish exact-match support pages:
  - `Railway vs Vercel (2026)`
  - `Railway free tier limits (2026)`
  - `Railway GPU support & pricing (2026)`

---

### Cluster D (P0): SaaS billing / Merchant of Record (Stripe vs Paddle vs Lemon Squeezy)
**Why P0:** high impressions with strong fee/compliance intent.

**Page mapping (primary):**
- `/blog/stripe-vs-paddle-vs-lemon-squeezy-saas-billing`

**Observed high-intent query to explicitly answer:**
- `compare stripe tax vs. paddle` (**194 impressions / 0 clicks / avg position ~6.45**)

**Recommendations:**
- Add an above-the-fold fee/tax table (explicitly includes “Stripe Tax” and “Paddle” wording).
- Publish a dedicated page:
  - `Stripe Tax vs Paddle (2026): what’s different + real examples`

---

### Cluster E (P0): Marketing automation AI features (HubSpot vs ActiveCampaign)
**Why P0:** sustained visibility with **0 clicks**.

**Page mapping (primary):**
- `/blog/hubspot-activecampaign-ai-agents-comparison`

**Recommendations:**
- Title/meta must explicitly include **AI features** + **marketing automation** + **2026**.
- Add an above-the-fold table: AI features, workflows, segmentation, deliverability, reporting, pricing.

---

### Cluster F (P1): API testing tools (Postman vs Insomnia vs Bruno)
**Why P1:** still the top click driver, but defensibility comes from head-to-head pages.

**Page mapping (primary):**
- `/blog/postman-vs-insomnia-vs-bruno-api-testing`

**Next pages to add:**
- `Postman vs Bruno (2026)`
- `Insomnia vs Bruno (2026)`

---

### Cluster G (P1): Project management tools (Linear vs Plane vs Height)
**Why P1:** queries convert well, but CTR softened this period.

**Page mapping (primary):**
- `/blog/linear-vs-height-vs-plane-project-management`

**Next pages to add:**
- `Plane vs Linear (2026)`
- `Height vs Linear (2026)`

---

### Cluster H (P1): Human-in-the-loop approval workflows (AI)
**Why P1:** meaningful impressions (1,480) with 0 clicks.

**Page mapping (primary):**
- `/blog/human-in-the-loop-approval-workflows`

**Recommendations:**
- Retitle toward “approval workflows for AI agents” and add an above-the-fold pattern library.

---

### Cluster I (P2): Vector database comparisons
**Why P2:** still strong impressions; secondary to P0 CTR recovery work.

**Page mapping:**
- `/blog/pinecone-vs-weaviate-vs-qdrant-vs-pgvector`
- `/blog/pinecone-vs-weaviate-vs-qdrant-vector-databases`

---

### Cluster J (P1): Startup stack comparisons (TypeScript vs Python)
**Why P1:** growing clicks and improving average position; clear adjacent modifiers exist.

**Page mapping (primary):**
- `/blog/typescript-vs-python-startup-stack`

**Observed modifiers worth targeting:**
- `python vs typescript for ai agents 2026`
- `typescript vs python for backend`

**Recommendations:**
- Add a short “AI agents” section near the top and a mini decision table.
- Avoid optimizing toward low-intent library queries surfaced by the page (e.g. `pip vs typescript`, `pytorch vs typescript`, `scikit-learn vs typescript`).

**Supporting page to consider:**
- `Python vs TypeScript for AI agents (2026)`

---

## Deprioritize / exclude (this month)

1. **One-word/no-intent queries**: `english`, `yes`, etc.
2. **Prompt-like “evaluate the company…” queries**: useful for impression volume, but not primary; don’t optimize titles/meta around these.
3. **Quoted code/token queries**: avoid optimizing snippets/headings for these.
4. **Misleading library-vs-language queries** (e.g. `pip vs typescript`, `pytorch vs typescript`): treat as noise unless you intentionally publish dedicated explainers.

---

## 30-day action plan (SEO execution)

1. **CTR + intent sprint (highest ROI):** update titles/meta + add above-the-fold summary blocks + tables for:
   - Best ecommerce platform comparison (2026)
   - Vercel vs Railway vs Render
   - Claude vs GPT-4o vs Gemini (Enterprise)
   - Stripe vs Paddle vs Lemon Squeezy (add Stripe Tax section)
   - HubSpot vs ActiveCampaign (AI features)
   - Human-in-the-loop approval workflows

2. **Publish 4 supporting pages (exact-match demand):**
   - Shopify vs WooCommerce vs BigCommerce (2026)
   - Railway vs Vercel (2026)
   - Railway GPU support & pricing (2026)
   - Stripe Tax vs Paddle (2026)

3. **Expand winning clusters (lightweight head-to-heads):**
   - Postman vs Bruno (2026)
   - Insomnia vs Bruno (2026)
   - Plane vs Linear (2026)

4. **Unblock Keyword Planner (platform-level):**
   - Re-authenticate Google Ads access with the **adwords** scope so we can use Keyword Planner to find *net-new* keywords beyond what’s already in Search Console.

---

## Appendix: previous review snapshot (2026-03-23)

The previous review content has been superseded by this update; see git history for the full prior snapshot.
