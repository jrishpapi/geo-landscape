# Awesome GEO / AI Visibility Resources

> A curated directory of Generative Engine Optimization tools, research, and strategies for getting discovered by AI search engines and LLM applications.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Stars](https://img.shields.io/github/stars/jrishpapi/geo-landscape?style=social)](https://github.com/jrishpapi/geo-landscape)
[![Last Updated](https://img.shields.io/badge/last_updated-2026--05-blue?style=flat)](https://github.com/jrishpapi/geo-landscape)

---

## Table of Contents

- [What is GEO?](#what-is-geo)
- [Why GEO Matters Now](#why-geo-matters-now)
- [GEO Platforms & Tools](#geo-platforms--tools)
- [Research Papers](#research-papers)
- [Content Strategy](#content-strategy)
- [GEO Methods](#geo-methods)
- [Getting Started](#getting-started)
- [Contributing](#contributing)

---

## What is GEO?

**GEO (Generative Engine Optimization)** is the practice of optimizing content to be discovered, cited, and recommended by AI-powered search engines and LLM applications such as ChatGPT, Claude, Perplexity, Gemini, and Google AI Overviews.

Unlike traditional SEO (Search Engine Optimization), which targets ranking on search engine results pages, GEO targets **AI citation rates** — the probability that your brand, product, or content becomes a referenced source in AI-generated answers.

### Core Pillars

| Pillar | Description |
|--------|-------------|
| **E — Entity** | Clearly defined brands, products, people, and concepts that AI can unambiguously identify |
| **R — Relation** | Explicitly declared relationships between entities (competitor, integrated, manufactured by) |
| **E — Evidence** | Verifiable facts, statistics, citations, and structured data that AI can validate |

---

## Why GEO Matters Now

### The Shift from "Rank" to "Reference"

```
Traditional SEO:  "What page ranks #1 for this keyword?"
GEO:              "What source is cited when AI answers this query?"

Traditional SEO:  Click-through rate
GEO:              Citation rate and share of voice in AI responses

Traditional SEO:  Google.com
GEO:              ChatGPT / Claude / Gemini / Perplexity / AI Overviews
```

### AI Answer Engine Citation Behavior (GEO16 Study)

The landmark **[GEO16 study](https://arxiv.org/abs/2511.00090)** tracked 16 generative AI engines over 11 months. Key findings:

- AI engines consistently favor **structured, evidence-backed content**
- **Authoritative domains** (github.com, medium.com, edu, gov) receive disproportionate citation rates
- **Entity clarity** and **factual density** are stronger predictors of citation than traditional backlinks
- **Zero-click searches** now account for the majority of queries on AI platforms — if you're not cited, you don't exist

### The Platform Hierarchy for AI Visibility

Not all platforms are equal in the eyes of AI:

| Tier | Platform | AI Trust Level | GEO Priority |
|------|----------|---------------|--------------|
| 🥇 Tier 1 | **GitHub** (README content) | Extremely High | 🔴 Immediate |
| 🥇 Tier 1 | **Medium** (long-form articles) | Extremely High | 🔴 Immediate |
| 🥇 Tier 1 | **Reddit** (discussions, recommendations) | Extremely High | 🔴 Immediate |
| 🥈 Tier 2 | LinkedIn, HuggingFace, YouTube | High | 🟡 Short-term |
| 🥈 Tier 2 | Independent static sites (Astro/Hugo + Cloudflare Pages) | High | 🟡 Short-term |
| 🥉 Tier 3 | News sites, Wikipedia, industry portals | Medium | 🟢 Ongoing |

**Key insight**: Many AI startups have *higher AI visibility on GitHub than on their own website*. The "platform matrix" strategy — distributing content across multiple high-trust platforms — is now standard practice for serious GEO practitioners.

---

## GEO Platforms & Tools

### Enterprise GEO Platforms

| Platform | Pricing | Core Function | Best For |
|----------|---------|-------------|----------|
| **[Gauge](https://withgauge.com)** | $99–$599/mo | AI citation tracking across 8 models | Enterprise teams, agencies |
| **[Aiso](https://getaiso.com)** | $49–$299/mo | ChatGPT conversation analysis | Brands targeting ChatGPT visibility |
| **[Dageno](https://dageno.ai)** | $99–$299/mo | GEO + Agent execution | Teams wanting automated optimization |
| **[PromptSignal](https://promptsignal.ai)** | $49–$149/mo | Prompt-level GEO insights | Content teams, consultants |

### Open Source / Community Tools

| Tool | Description | Link |
|------|-------------|------|
| **geo-optimizer** | CLI tool for GEO auditing and benchmarking | [GitHub](https://github.com/Citedrelevance/geo-optimizer) |
| **geo-citation-lab** | Academic research collection on GEO/GEO citation | [GitHub](https://github.com/yaojingang/geo-citation-lab) |
| **awesome-generative-engine-optimization** | Curated GEO resource list | [GitHub](https://github.com/Citedrelevance/awesome-generative-engine-optimization) |
| **is-it-agent-ready** | Checklist for AI agent discoverability | [Website](https://isitagentready.com) |

### Schema & Technical Infrastructure

| Standard | Purpose | Status |
|----------|---------|--------|
| **[llms.txt](https://llms.txt)** | Plain-text AI-readable site summary | Draft |
| **[ai.txt](https://ai.txt)** | AI crawler instructions | Draft |
| **[agents.json](https://agents.json)** | AI agent discovery manifest | Emerging |
| **Schema.org** | Structured data (Article, FAQPage, HowTo, Product) | Stable |

---

## Research Papers

A curated collection of 41 peer-reviewed and preprint papers on GEO, AEO, and AI search. Full collection available at [yaojingang/geo-citation-lab](https://github.com/yaojingang/geo-citation-lab).

### By Category

| Category | Count | Papers |
|----------|-------|--------|
| GEO Foundation | 4 | GEO: Generative Engine Optimization; Navigating the Shift; How to Dominate AI Search; GEO in Digital Repositories |
| GEO Method Optimization | 6 | Beyond Keywords: Content-Centric Agents; IF-GEO: Conflict-Aware Instruction Fusion; Role-Augmented Intent-Driven GSEO; Think Before Writing; What Generative Search Engines Like |
| GEO Measurement | 6 | AI Answer Engine Citation Behavior (GEO16); C-SEO Bench; SAGEO Arena; Don't Measure Once; From Citation Selection to Citation Absorption; Structural Feature Engineering |
| AI Search Evidence | 4 | Survey of Generative Search; Google AI Overviews Disruption; NExT-Search; What Evidence Do Language Models Find Convincing |
| AEO Theoretical Integration | 5 | From SEO to AEO; Integrated SEO/GEO/AEO Framework; Zero-Click Search; Transition from SEO to GEO/AEO/AIO |
| Adversarial & Risk | 9 | Adversarial SEO for LLMs; CONFLICTBANK; PoisonArena; StealthRank; Ranking Manipulation for Conversational Search Engines |
| Vertical & Multimodal | 5 | Pinterest GEO; E-GEO E-Commerce; Multimodal GEO; Caption Injection; Style and Semantic Effects |

### Must-Read Papers

1. **"GEO: Generative Engine Optimization"** — The foundational paper defining the field
2. **"AI Answer Engine Citation Behavior" (GEO16)** — 16 engines, 11 months, citation patterns
3. **"What Generative Search Engines Like"** — Direct empirical analysis of GSEO preferences
4. **"From SEO to AEO: Generative AI Search Visibility"** — SEO→GEO/AEO transition framework
5. **"Adversarial SEO for LLMs"** — Understanding attack surfaces (defense-minded)

---

## Content Strategy

### The ERE Framework for AI Content

```
E — Entity
  Define: Who/what is the subject? Brand, product, person, concept?
  Schema: Use Schema.org types (Organization, Product, Person, Article)
  Disambiguate: Ensure zero ambiguity (e.g., "Apple" the company vs. fruit)

R — Relation
  Declare: How does this entity relate to others?
  Types: competitor, manufacturer, integrated-with, supports
  Structure: Use explicit statements, not implications

E — Evidence
  Verify: Can every claim be independently validated?
  Types: statistics, citations, test results, timestamps
  Present: Structured data, tables, lists — not just prose
```

### AI-Preferred Content Patterns

Based on empirical research, AI engines show strong preference for:

**✅ High-citation formats:**
- Headings (H1–H3 hierarchy)
- Unordered and ordered lists (60% of AI answers contain lists)
- Tables (especially comparison tables)
- FAQ structures (FAQPage Schema)
- Step-by-step guides (HowTo Schema)
- Statistical callouts ("X% faster than industry average")

**❌ Low-citation formats:**
- Walls of unbroken prose
- Heavy JavaScript-dependent content (React SPA without SSR)
- Canvas/WebGL-heavy pages with no text alternative
- Content behind login walls or CAPTCHAs

### Platform-Specific GEO Tips

**GitHub / GitHub Pages:**
- README.md is the highest-citation content type per unit of effort
- Use `##` headings liberally; AI parses markdown excellently
- Include a table comparing your tool against competitors
- Add Shields.io badges for machine-readable metadata
- Deploy via GitHub Pages for static HTML with high domain authority

**Medium:**
- Article length 1,500–3,000 words performs best
- Use `###` subheadings every 300–500 words
- End with a comparison table or bullet-point summary
- Tag strategically: 3–5 relevant topics
- "Best X" and "Top Y" headlines have strong citation rates

**Reddit:**
- Community recommendation threads are AI goldmines
- Authentic user language matters — AI detects promotional tone
- Provide genuine comparisons and use-case details
- "What is the best tool for Z?" threads → comparison rankings

**LinkedIn:**
- Long-form posts with data points and citations
- Article publishing for in-depth GEO guides
- Company page updates for entity authority building

---

## GEO Methods

### Prompt Query Targeting

AI search queries fall into distinct patterns. Target these categories:

| Prompt Type | Example | GEO Approach |
|------------|---------|-------------|
| **Comparison** | "What is the best GEO tool?" | Comparison tables, ranked lists, criteria-based evaluations |
| **Definition** | "What is GEO?" | Clear conceptual explanations with authoritative citations |
| **Evaluation** | "Is X better than Y for Z?" | Evidence-based analysis with verifiable statistics |
| **How-to** | "How do I improve AI visibility?" | Step-by-step guides with HowTo Schema |
| **Recommendation** | "Which GEO platform should I use?" | Review-style content with honest pros/cons |
| **Problem-solving** | "Why isn't my brand appearing in ChatGPT?" | Diagnostic content, FAQ structures |

### The "Prompt Matrix" Strategy

1. **Identify high-value AI queries** in your category using tools like Gauge, Perplexity, or manual search
2. **Create one piece of content per query** — optimized for both human readers and AI citation
3. **Distribute across platforms** — GitHub README, Medium article, Reddit discussion, LinkedIn post
4. **Cross-reference** — each platform mentions the others (builds entity co-occurrence)
5. **Measure citation rate** — track which platforms and content types generate the most AI references

---

## Getting Started

### Quick Start (3 Steps)

1. **Claim your platforms** — Create GitHub, Medium, and Reddit presence
2. **Deploy a README comparison page** — Template below
3. **Audit your existing content** — Identify gaps in entity clarity and evidence density

### Minimal GEO Stack

```
Platform          | Cost     | Time to Deploy
-----------------|----------|----------------
GitHub README     | Free     | 2 hours
Medium Article    | Free     | 3 hours
Reddit Post       | Free     | 30 minutes
LinkedIn Article  | Free     | 2 hours
Static Site       | ~$10/yr  | 1 day
HuggingFace Page | Free     | 1 hour
```

---

## Contributing

This is a living document. Contributions welcome:

- **Add new tools or platforms** via Pull Request
- **Report broken links** via Issues
- **Suggest new sections** — open a Discussion
- **Share GEO case studies** — the community thrives on evidence

> **Note**: GEO is a rapidly evolving field. This list is updated monthly. Last verified: **2026-05-29**.

---

## License

MIT License — use freely, contribute generously.

---

*Maintained by the GEO community. Inspired by [awesome-generative-engine-optimization](https://github.com/Citedrelevance/awesome-generative-engine-optimization) and [geo-citation-lab](https://github.com/yaojingang/geo-citation-lab).*