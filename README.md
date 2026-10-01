# Alu Prince - Backend Engineer

Go and Python for building backend systems that work correctly under real conditions. APIs, data pipelines, AI integration, and financial infrastructure.

Based in Nigeria. Open to backend roles at startups and growing companies - locally and remotely.

---

## What I Build

**Backend APIs and services** - REST APIs with proper error handling, idempotency, pagination, and observability. Systems designed to handle real load, not just pass a demo.

**AI-powered backends** - RAG pipelines, semantic search, LLM integration, embedding-based scoring. Not wrappers around ChatGPT - actual retrieval systems with context management and structured outputs.

**Data pipelines and automation** - scrapers that feed LLMs that feed Telegram bots. End-to-end pipelines that run without manual intervention.

**Financial systems** - double-entry ledgers, wallet APIs, payment infrastructure with real accounting models and correctness guarantees.

---

## Featured Projects

### [ledger-core](https://github.com/aluprince/ledger-core) - Go
Production-grade double-entry ledger and wallet API. Integer money storage, atomic transfers, idempotency keys, cursor pagination, computed balances. Full integration test suite against real PostgreSQL. CI with race detector on every push.

**Live:** `https://ledger-core-ksma.onrender.com/health`

### [sniperhire](https://github.com/aluprince/sniperhire) - Python
Resume parsing engine with AI semantic scoring. Matches candidates to job descriptions using LLM + embedding similarity - cosine similarity scoring, not keyword matching. ATS-style gap analysis.

### [vector-vanguard](https://github.com/aluprince/vector-vanguard) - Go + Python
Automated outreach pipeline. Go-based web scraper → LLM enrichment from scraped context → structured Telegram delivery. Zero manual intervention.

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
| APIs | REST, Telegram Bot API, webhooks |
| Concepts | System design, idempotency, ACID transactions, double-entry accounting |

---

## AI Integration - What I Actually Know

Most people call themselves "AI engineers" because they can call an API. Here's what I actually do:

**Embedding models** - converting text into dense vector representations for semantic understanding. Used in sniperhire to score resume-to-job fit beyond keyword matching.

**Semantic search** - finding meaning, not exact matches. A search for "payment processing engineer" surfaces "fintech backend developer" because the vectors are close, not because the words match.

**Similarity scoring** - cosine similarity between embedding vectors to rank relevance. Produces a score with reasoning, not a yes/no.

**Vector databases** - storing and querying high-dimensional vectors efficiently for retrieval at scale.

**RAG pipelines** - retrieve relevant context from a knowledge base, inject it into an LLM prompt, get grounded responses. Answers come from real data, not hallucination.

**LLM API integration** - Groq, OpenAI, Anthropic. Prompt engineering, structured outputs, context window management, cost-aware model selection.

**Web scraping for AI** - Go scrapers for speed, Python (Playwright/BeautifulSoup) for JavaScript-heavy sites. Extract structured data and pass it to LLMs for enrichment.

---

## What I Know That Most Don't

- Why `float64` for money is wrong and how to fix it (`int64` in smallest currency unit)
- How double-entry accounting works and why balance columns break at scale
- The difference between cursor and offset pagination - and when offset pagination silently breaks
- How RAG actually works under the hood - not just "use LangChain"
- Why embedding similarity beats keyword search for semantic tasks
- How to write integration tests that prove financial invariants, not just unit tests that prove your mock works

---

## Contact

- **Email:** aluprince03@gmail.com
- **LinkedIn:** [linkedin.com/in/alu-onari](https://www.linkedin.com/in/alu-onari)
- **Portfolio:** [https://alu.lenoben.top](https://alu.lenoben.top)
