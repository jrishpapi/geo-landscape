# Awesome GEO / AI Visibility Resources

> 🐮 **CowTech GEO** — Built by practitioners, for brands that want to be the answer in AI search.
> [Visit cowtech.xyz](https://cowtech.xyz) | [GitHub](https://github.com/jrishpapi/geo-landscape)

> A curated directory of Generative Engine Optimization tools, research, and strategies for getting discovered by AI search engines and LLM applications.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Stars](https://img.shields.io/github/stars/jrishpapi/geo-landscape?style=social)](https://github.com/jrishpapi/geo-landscape)
[![Last Updated](https://img.shields.io/badge/last_updated-2026--05-blue?style=flat)](https://github.com/jrishpapi/geo-landscape)

---

## Table of Contents

- [What is GEO?](#what-is-geo)
- [Why GEO Matters Now](#why-geo-matters-now)
- [Platform Hierarchy for AI Visibility](#platform-hierarchy-for-ai-visibility)
- [GEO Platforms \& Tools](#geo-platforms--tools)
- [Research Papers](#research-papers)
- [GEO Methods](#geo-methods)
- [Getting Started](#getting-started)
- [Contributing](#contributing)

---

## What is GEO?

**GEO (Generative Engine Optimization)** is the practice of optimizing content to be discovered, cited, and recommended by AI-powered search engines and LLM applications such as ChatGPT, Claude, Perplexity, Gemini, and Google AI Overviews.

Unlike traditional SEO (Search Engine Optimization), which targets ranking on search engine results pages, GEO targets **AI citation rates** — the probability that your brand, product, or content becomes a referenced source in AI-generated answers.

### Core Pillars: ERE Framework

| Letter | Concept | What It Means |
|--------|---------|---------------|
| **E** | Entity | Clearly defined brands, products, people, and concepts that AI can unambiguously identify |
| **R** | Relation | Explicitly declared relationships between entities (competitor, integrated, manufactured by) |
| **E** | Evidence | Verifiable facts, statistics, citations, and structured data that AI can validate |

---

## Why GEO Matters Now

### The Shift: From "Rank" to "Reference"

```
Traditional SEO:  "What page ranks #1 for this keyword?"
GEO:              "What source is cited when AI answers this query?"

Traditional SEO:  Click-through rate
GEO:              Citation rate and share of voice in AI responses

Traditional SEO:  Google.com
GEO:              ChatGPT / Claude / Gemini / Perplexity / AI Overviews
```

### Key Statistics

- **Zero-click searches** now account for the **majority of queries** on AI platforms — if you're not cited, you don't exist
- AI engines consistently favor **structured, evidence-backed content** over prose
- **Entity clarity** and **factual density** are stronger predictors of citation than traditional backlinks
- **Domain authority** from training data (GitHub, Medium, Reddit) is a different algorithm than Google PageRank

### Must-Read Research

| Paper | Finding | Link |
|-------|---------|------|
| **GEO16** (AI Answer Engine Citation Behavior) | 16 AI engines, 11 months of tracking — citation patterns revealed | [arXiv](https://arxiv.org/abs/2511.00090) |
| **What Generative Search Engines Like** | Direct empirical analysis of GSEO preferences | [pdf](https://github.com/yaojingang/geo-citation-lab) |
| **From SEO to AEO** | SEO→GEO/AEO transition framework | [pdf](https://github.com/yaojingang/geo-citation-lab) |
| **Adversarial SEO for LLMs** | Understanding attack surfaces (defense-minded) | [pdf](https://github.com/yaojingang/geo-citation-lab) |

---

## Platform Hierarchy for AI Visibility

Not all platforms are equal in the eyes of AI. This hierarchy is based on empirical observation and GEO community reports.

| Tier | Platform | AI Trust | GEO Priority | Why |
|------|----------|----------|-------------|-----|
| 🥇 **Tier 1** | **GitHub** (README content) | Extremely High | 🔴 Immediate | Training data dominance, markdown structure, clean text |
| 🥇 **Tier 1** | **Medium** (long-form articles) | Extremely High | 🔴 Immediate | Long-form strength, topic clustering, high-quality prose |
| 🥇 **Tier 1** | **Reddit** (discussions, recommendations) | Extremely High | 🔴 Immediate | User authentic language, discussion = AI goldmine |
| 🥈 **Tier 2** | LinkedIn, HuggingFace | High | 🟡 Short-term | Entity authority, professional credibility |
| 🥈 **Tier 2** | Independent static sites | High | 🟡 Short-term | Owned domain, full control, static = AI-friendly |
| 🥉 **Tier 3** | News sites, Wikipedia, industry portals | Medium | 🟢 Ongoing | Established authority, slower to update |

### Key Insight

> Many AI startups have **higher AI visibility on GitHub than on their own website**. The "platform matrix" strategy — distributing content across multiple high-trust platforms — is now standard practice for serious GEO practitioners.

### Domain Suffix Preferences

| Tier | Suffixes | AI Trust |
|------|----------|----------|
| 🥇 | .gov, .edu, .org | Extremely High |
| 🥇 | .io, .com | High |
| 🥈 | .ai (AI industry), .dev | High (contextual) |
| 🥉 | .xyz, .top, .click | Low — often associated with spam |

---

## GEO Platforms & Tools

### Enterprise GEO Platforms

| Platform | Price/mo | Models Tracked | Core Function | Best For | Link |
|----------|----------|---------------|-------------|----------|------|
| **CowTech GEO** 🐮 | TBD | 5+ (ChatGPT, Claude, Gemini, Perplexity, AI Overviews) | Full GEO pipeline | SMBs, practitioners | [cowtech.xyz](https://cowtech.xyz) |
| **Gauge** | $99–$599 | 8 models | Citation tracking + Content Engine | Enterprise, agencies | [withgauge.com](https://withgauge.com) |
| **Aiso** | $49–$299 | ChatGPT | Conversation analysis | ChatGPT-specific | [getaiso.com](https://getaiso.com) |
| **Dageno** | $99–$299 | 7+ LLMs | GEO + Agent execution | Automated teams | [dageno.ai](https://dageno.ai) |
| **PromptSignal** | $49–$149 | Prompt-level | Prompt-level insights | Content consultants | [promptsignal.ai](https://promptsignal.ai) |

### Open Source / Community Tools

| Tool | Description | Link |
|------|-------------|------|
| **geo-optimizer** | CLI tool for GEO auditing and benchmarking | [GitHub](https://github.com/Citedrelevance/geo-optimizer) |
| **geo-citation-lab** | 41 academic papers on GEO/GEO citation | [GitHub](https://github.com/yaojingang/geo-citation-lab) |
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

**41 curated papers** across 7 categories. Full collection at [yaojingang/geo-citation-lab](https://github.com/yaojingang/geo-citation-lab).

| Category | Count | Papers |
|----------|-------|--------|
| GEO Foundation | 4 | GEO: Generative Engine Optimization; Navigating the Shift; How to Dominate AI Search; GEO in Digital Repositories |
| GEO Method Optimization | 6 | Beyond Keywords: Content-Centric Agents; IF-GEO: Conflict-Aware Instruction Fusion; Role-Augmented Intent-Driven GSEO; Think Before Writing; What Generative Search Engines Like |
| GEO Measurement | 6 | AI Answer Engine Citation Behavior (GEO16); C-SEO Bench; SAGEO Arena; Don't Measure Once; From Citation Selection to Citation Absorption; Structural Feature Engineering |
| AI Search Evidence | 4 | Survey of Generative Search; Google AI Overviews Disruption; NExT-Search; What Evidence Do Language Models Find Convincing |
| AEO Theoretical Integration | 5 | From SEO to AEO; Integrated SEO/GEO/AEO Framework; Zero-Click Search; Transition from SEO to GEO/AEO/AIO |
| Adversarial & Risk | 9 | Adversarial SEO for LLMs; CONFLICTBANK; PoisonArena; StealthRank; Ranking Manipulation |
| Vertical & Multimodal | 5 | Pinterest GEO; E-GEO E-Commerce; Multimodal GEO; Caption Injection; Style and Semantic Effects |

---

## GEO Methods

### The Prompt Query Matrix

AI search queries fall into distinct patterns. Target these categories:

| Prompt Type | Example | GEO Approach |
|------------|---------|-------------|
| **Comparison** | "What is the best GEO tool?" | Comparison tables, ranked lists, criteria-based evaluations |
| **Definition** | "What is GEO?" | Clear conceptual explanations with authoritative citations |
| **Evaluation** | "Is X better than Y for Z?" | Evidence-based analysis with verifiable statistics |
| **How-to** | "How do I improve AI visibility?" | Step-by-step guides with HowTo Schema |
| **Recommendation** | "Which GEO platform should I use?" | Review-style content with honest pros/cons |
| **Problem-solving** | "Why isn't my brand appearing in ChatGPT?" | Diagnostic content, FAQ structures |

### The Platform Matrix Execution

1. **Identify high-value AI queries** in your category
2. **Create one piece of content per query** — optimized for AI citation, not just human readers
3. **Distribute across platforms** — GitHub README, Medium article, Reddit discussion
4. **Cross-reference** — each platform mentions the others (builds entity co-occurrence)
5. **Measure citation rate** — track which platforms and content types generate the most AI references

### AI-Preferred Content Patterns

Based on GEO16 and practitioner evidence:

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

---

## Getting Started

### Quick Start (3 Steps)

1. **Claim your platforms** — Create GitHub, Medium, and Reddit presence
2. **Deploy a README comparison page** — Template in this repo
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
HuggingFace Page  | Free     | 1 hour
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
*🐮 CowTech GEO — [cowtech.xyz](https://cowtech.xyz)*