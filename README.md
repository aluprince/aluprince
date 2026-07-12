# Alu Prince — Backend Engineer

Go and Python for systems where correctness isn't optional. Fintech infrastructure, payment APIs, financial systems, and AI-powered backends.

Based in Nigeria. Open to fintech roles locally and remotely.

---

## What I Build

**Financial infrastructure** — double-entry ledgers, wallet APIs, payment systems with real accounting models. Not balance columns that get decremented — actual immutable ledger entries, computed balances, idempotency guarantees.

**AI-powered backends** — RAG pipelines, semantic search, LLM integration, embedding-based scoring. Not wrappers around ChatGPT — actual systems with retrieval, context management, and structured outputs.

**Automation pipelines** — scrapers that feed LLMs that feed Telegram bots. End-to-end, deployed, running.

---

## Featured Projects

### [ledger-core](https://github.com/aluprince/ledger-core) — Go
Production-grade double-entry ledger and wallet API. Integer money storage (kobo, not naira float), atomic transfers, idempotency keys, cursor pagination, computed balances. Full integration tests against real PostgreSQL. CI with race detector on every push.

**Live:** `https://ledger-core-ksma.onrender.com/health`

### [sniperhire](https://github.com/aluprince/sniperhire) — Python
Resume parsing engine with AI semantic scoring. Matches candidates to job descriptions using LLM + embedding similarity — not keyword matching. Generates ATS-style gap analysis from vector similarity scores.

### [vector-vanguard](https://github.com/aluprince/vector-vanguard) — Go + Python
Automated outreach pipeline. Go-based web scraper → LLM pitch generation from scraped context → structured Telegram delivery. Zero manual intervention.

---

## Stack

| Layer | Tools |
|---|---|
| Primary language | Go |
| Secondary | Python |
| Databases | PostgreSQL (raw SQL, sqlc), vector databases |
| AI / LLM | Groq API, OpenAI API, Anthropic API |
| Embeddings | Embedding models, semantic search, similarity scoring |
| RAG | Retrieval-augmented generation, vector search, context management |
| Scraping | Playwright, BeautifulSoup, Selenium, Go HTTP clients |
| Infra | Docker, GitHub Actions CI, Linux/VPS, Render |
| APIs | REST, Telegram Bot API, payment webhooks |
| Concepts | Double-entry accounting, idempotency, system design, ACID transactions |

---

## AI Integration — What I Actually Know

Most people call themselves "AI engineers" because they can call an API. Here's what I actually do:

**Embedding models** — converting text into vector representations for semantic understanding. Used in sniperhire to score resume-to-job fit beyond keyword matching.

**Semantic search** — finding meaning, not just exact matches. A search for "payment processing engineer" surfaces "fintech backend developer" because the vectors are close, not because the words match.

**Similarity scoring** — cosine similarity between embedding vectors to rank how closely a resume matches a job description. Produces a score, not a yes/no.

**Vector databases** — storing and querying high-dimensional vectors efficiently for retrieval at scale.

**RAG pipelines** — retrieval-augmented generation: retrieve relevant context from a knowledge base, inject it into an LLM prompt, get grounded responses. Used this to build systems that answer questions from real documents rather than hallucinating.

**LLM API integration** — Groq, OpenAI, Anthropic. Prompt engineering, structured outputs, context window management, cost-aware model selection.

**Web scraping for AI** — scraping raw data that feeds into LLM pipelines. Go scrapers for speed, Python (Playwright/BeautifulSoup) for JavaScript-heavy sites. Built scrapers that extract structured business data and pass it to LLMs for enrichment.

---

## What I Know That Most Don't

- Why `float64` for money is wrong and how to fix it (`int64` kobo)
- How double-entry accounting works and why it matters for wallet systems
- Nigerian payment infrastructure: Monnify virtual accounts, Paystack webhooks, Providus inflow patterns
- The difference between cursor and offset pagination and when each breaks
- How RAG actually works under the hood — not just "use LangChain"
- Why embedding similarity beats keyword search for semantic tasks

---

## Contact

- Email: aluprince03@gmail.com
- LinkedIn: [linkedin.com/in/alu-onari](https://www.linkedin.com/in/alu-onari)
- Portfolio: coming soon

