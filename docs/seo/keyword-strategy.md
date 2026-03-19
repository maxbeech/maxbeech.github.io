# Monthly SEO Keyword Strategy Review (getathenic.com)

**Review date:** 2026-03-19  
**Primary goal:** identify keyword opportunities to grow *qualified organic traffic* and improve click-through-rate (CTR) on high-impression pages.

## Data sources used (this review)

1. **Google Search Console** (last 28 days: **2026-02-19 → 2026-03-18**, vs previous 28 days: **2026-01-22 → 2026-02-18**)
2. **Google Ads Keyword Planner**: attempted again, but the API integration is still failing due to an invalid configured Google Ads Customer ID.

**Keyword Planner error (actionable fix):**
- Error returned by API: `GOOGLE_ADS_CUSTOMER_ID is invalid: "476-798-8021\n"` (note the trailing newline)
- Fix: update the configured customer ID to a valid **10-digit** value *with no whitespace/newlines* (dashes are fine: `123-456-7890`).

---

## Executive summary (what changed vs last review)

### 1) Visibility step-change: “comparison” content is now earning large impression volume
Across the last 28 days, multiple comparison pages moved into a pattern of:
- **Avg position ~6–7** (top 10)
- **Tens of thousands of impressions**
- **Very low CTR** (often **< 0.07%**) → the site is *being shown*, but searchers aren’t choosing the snippet.

This is the highest-leverage SEO work for the next 30 days.

### 2) New cluster with real click volume: Linear vs Plane vs Height
The page `/blog/linear-vs-height-vs-plane-project-management` is now a top click driver.
- **28 clicks / 2,172 impressions / 1.29% CTR / avg position 6.30**

This is a strong signal to expand into adjacent “project management tool comparison” head-to-heads.

### 3) New high-impression / zero-click opportunity: HubSpot vs ActiveCampaign (AI features)
The page `/blog/hubspot-activecampaign-ai-agents-comparison` has meaningful visibility but no traffic yet.
- **0 clicks / 2,820 impressions / 0.00% CTR / avg position 8.58**

This is almost certainly a title/meta + intent-match issue.

---

## Biggest immediate upside: CTR improvement on pages already ranking in positions ~5–8

**Top CTR-upside pages (last 28 days):**

| Page | Clicks | Impressions | CTR | Avg position |
|---|---:|---:|---:|---:|
| /blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison | 6 | 31,192 | 0.019% | 6.01 |
| /blog/vercel-vs-railway-vs-render-ai-deployment | 12 | 23,395 | 0.051% | 6.49 |
| /blog/stripe-vs-paddle-vs-lemon-squeezy-saas-billing | 9 | 16,534 | 0.054% | 6.27 |
| /blog/pinecone-vs-weaviate-vs-qdrant-vs-pgvector | 6 | 10,431 | 0.058% | 6.85 |
| /blog/supabase-vs-firebase-vs-convex-ai-backend | 5 | 7,869 | 0.064% | 7.16 |
| /blog/hubspot-activecampaign-ai-agents-comparison | 0 | 2,820 | 0.000% | 8.58 |

**What this means in clicks (illustrative):**
- If `/blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison` moves from **0.019% → 0.20% CTR**, that’s roughly **+56 clicks / 28 days** at current impressions.
- If `/blog/vercel-vs-railway-vs-render-ai-deployment` moves from **0.051% → 0.20% CTR**, that’s roughly **+35 clicks / 28 days**.

---

## Biggest movers (last 28 days vs previous 28 days)

| Page | Clicks (prev → now) | Impressions (prev → now) | Note |
|---|---:|---:|---|
| /blog/stripe-vs-paddle-vs-lemon-squeezy-saas-billing | 4 → 9 | 1,378 → 16,534 | major impression growth; CTR now the bottleneck |
| /blog/vercel-vs-railway-vs-render-ai-deployment | 2 → 12 | 2,018 → 23,395 | huge visibility gain; snippet underperforming |
| /blog/e2b-vs-modal-vs-flyio-sandbox-comparison | 44 → 9 | 3,511 → 3,808 | clicks down sharply; monitor ranking + intent drift |
| /blog/linear-vs-height-vs-plane-project-management | (not top 50) → 28 | (not top 50) → 2,172 | new high-performing cluster |
| /blog/postman-vs-insomnia-vs-bruno-api-testing | (not top 50) → 32 | (not top 50) → 3,644 | strong performer; expand variants |

---

## Updated keyword clusters (prioritized)

### Cluster A (P0): LLM model comparisons (Enterprise: Claude vs GPT-4o vs Gemini)
**Why P0:** *largest impressions on the site* with average position ~6 and near-zero CTR.

**Observed demand patterns (Search Console):**
- Many “best model for X” use-case modifiers (e.g. *HTML extraction*, *PDF to markdown*, *legal translation*).
- Broad “best AI / best LLM” in multiple languages → suggests the page is being used by Google as a generic candidate, which can be good for impressions but bad for CTR if the snippet doesn’t match.

**Page mapping:**
- Primary: `/blog/claude-vs-gpt4o-vs-gemini-enterprise-comparison`

**Recommendations (next 30 days):**
- Title/meta: make the promise explicit and click-worthy: **“Claude vs GPT-4o vs Gemini (2026): price, context, latency, benchmarks”**.
- Add a “Use-cases” jump table near the top (HTML extraction, long-doc parsing, coding, RAG), so the snippet better matches the long-tail.
- Add an FAQ section with exact-match questions ("best model for html data extraction", "best llm for pdf to markdown").

---

### Cluster B (P0): Deployment platforms for apps/AI workloads (Vercel vs Railway vs Render)
**Why P0:** very high impressions; page already ranks in top 10; CTR still extremely low.

**Observed modifiers to capture:**
- **free tier limits / pricing**
- **GPU support**
- “Railway vs Render (2026)” variants

**Page mapping:**
- Primary: `/blog/vercel-vs-railway-vs-render-ai-deployment`

**Recommendations:**
- Add a visible **Pricing / Free tier (2026)** table above the fold.
- Add FAQ targeting: “Railway free tier limits 2026”, “Does Railway support GPUs?”, “Railway vs Render pricing 2026”.
- Consider 1 supporting page if this query class continues to grow:
  - `Railway free tier limits (2026): what you get + when you pay`

---

### Cluster C (P0): SaaS billing / Merchant of Record (Stripe vs Paddle vs Lemon Squeezy)
**Why P0:** very high impressions; recurring “fees/pricing” intent; current snippet under-matches.

**Observed modifiers to capture:**
- “Stripe Tax vs Paddle”
- “Lemon Squeezy pricing 5% + $0.50”

**Page mapping:**
- Primary: `/blog/stripe-vs-paddle-vs-lemon-squeezy-saas-billing`

**Recommendations:**
- Add a fee-breakdown table that explicitly includes **“5% + $0.50”** wording.
- Add a dedicated on-page section “Stripe Tax vs Paddle: what’s different?”
- Consider 1 supporting page:
  - `Lemon Squeezy pricing explained: 5% + $0.50 (examples + calculator)`

---

### Cluster D (P0): BaaS decisions (Convex vs Supabase vs Firebase)
**Why P0:** strong head-term visibility; the head query is getting impressions but not clicks.

**Evidence:**
- Query → page mapping: `convex vs supabase` → `/blog/supabase-vs-firebase-vs-convex-ai-backend`
- For `convex vs supabase`: **267 impressions / 0 clicks / avg position 5.01**

**Recommendations:**
- Adjust title to lead with the dominant head-to-head: **“Convex vs Supabase (vs Firebase) (2026)”**.
- Add an above-the-fold “Who should pick Convex vs Supabase?” summary.
- Add FAQ: “Is Convex better than Supabase?”, “Convex pricing vs Firebase”, “Supabase to Convex migration”.

---

### Cluster E (P1): API testing tools (Postman vs Insomnia vs Bruno)
**Why P1:** already the top click driver; expand to capture variant head-to-heads.

**Page mapping:**
- Primary: `/blog/postman-vs-insomnia-vs-bruno-api-testing`

**Recommendations:**
- Add explicit H2s for “Bruno vs Postman” and “Insomnia vs Postman”.
- Add a short “Which should you use in 2026?” decision tree.

---

### Cluster F (P1): Project management tools (Linear vs Plane vs Height)
**Why P1:** strong CTR + meaningful clicks; easy adjacent expansion.

**Page mapping:**
- Primary: `/blog/linear-vs-height-vs-plane-project-management`

**Next keywords/pages to add (based on observed demand + adjacent SERPs):**
- Linear vs Height
- Linear vs Plane
- Linear vs Jira vs Asana (already getting impressions)
- Linear vs Asana (already getting impressions)

---

### Cluster G (P1): Marketing automation AI features (HubSpot vs ActiveCampaign)
**Why P1:** substantial impressions with **0 clicks** and average position ~8.6.

**Page mapping:**
- Primary: `/blog/hubspot-activecampaign-ai-agents-comparison`

**Recommendations:**
- Title/meta must explicitly match the dominant query framing:
  - include “**AI features**”, “**marketing automation**”, and “**2026**”.
- Add an above-the-fold comparison table that includes the words users search (AI features, personalization, segmentation, deliverability, workflows).

---

### Cluster H (P2): Vector database comparisons
**Why P2:** high impressions, moderate clicks; CTR improvement still useful but secondary to the top 3 clusters.

**Page mapping:**
- `/blog/pinecone-vs-weaviate-vs-qdrant-vs-pgvector`
- `/blog/pinecone-vs-weaviate-vs-qdrant-vector-databases`

---

## Deprioritize / exclude (this month)

1. **One-word/no-intent queries**: `english`, `yes`, and other noise.
2. **Prompt-like “evaluate the company…” queries**: treat as non-primary. Don’t build dedicated pages for these.
3. **Quoted code/token queries** (e.g. library import strings): these create impressions but rarely drive qualified traffic. Avoid optimizing titles/meta toward these; keep content readable and well-structured.

---

## 30-day action plan (SEO execution)

1. **CTR sprint (highest ROI):** update titles/meta + add above-the-fold summary blocks for:
   - Claude vs GPT-4o vs Gemini
   - Vercel vs Railway vs Render
   - Stripe vs Paddle vs Lemon Squeezy
   - Convex vs Supabase
   - HubSpot vs ActiveCampaign

2. **Publish 2 supporting pages** to capture clear modifiers already visible in Search Console:
   - Railway free tier limits (2026)
   - Lemon Squeezy pricing (5% + $0.50) explained

3. **Expand winning clusters:** publish 1–2 additional “Linear vs X” pages (low effort, high intent-match).

4. **Unblock Keyword Planner (platform-level):** fix the Google Ads customer ID configuration so we can enrich these clusters with net-new keywords that aren’t yet appearing in Search Console.

---

## Appendix: previous review snapshot (2026-03-09)

The previous review content has been superseded by this update; see git history for the full prior snapshot.
