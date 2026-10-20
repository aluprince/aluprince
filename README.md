# Alu Prince | Backend Engineer

I build backend systems in **Go and Python** with a focus on correctness, reliability, data-intensive workloads, and AI integration.

From financial ledgers to semantic search and retrieval-augmented generation, I care about what happens beyond the happy path: failure handling, data integrity, testing, and maintainable architecture.

Based in Nigeria. Open to backend engineering roles and remote opportunities.

---

## Featured Projects

### 1. [Ledger Core](https://github.com/aluprince/ledger-core) | Go, PostgreSQL

**Double-entry ledger and wallet API**

A financial backend built around accounting correctness and reliable transaction processing.

- Double-entry bookkeeping and computed account balances
- Integer-based monetary amounts to avoid floating-point precision errors
- Atomic transfers and idempotency keys
- Cursor-based pagination
- Integration tests against PostgreSQL
- CI with automated testing and race detection

**Live API:** [Health check](https://ledger-core-ksma.onrender.com/health)

### 2. [Atlas-RAG](https://github.com/aluprince/atlas-rag) | Python, FastAPI, PostgreSQL, pgvector

**Document retrieval and question-answering system**

A retrieval-augmented generation application that turns documents into searchable knowledge and uses relevant retrieved context to support answers.

- Document ingestion and text extraction
- Chunking and embedding generation
- Vector similarity search with PostgreSQL and pgvector
- Retrieval results with similarity scores and source metadata
- Groq-powered answer generation
- FastAPI backend and Streamlit interface

The project explores the engineering behind RAG systems, including document processing, retrieval quality, context construction, and source traceability.

### 3. [SniperHire](https://github.com/aluprince/sniperhire) | Python, AI Integration

**Resume parsing and semantic candidate matching**

An ATS-style project that evaluates resumes against job descriptions using structured information extraction and semantic matching.

- Resume parsing and information extraction
- Embedding-based similarity scoring
- LLM-assisted analysis
- Candidate-to-role matching and skills gap analysis

### 4. [Vector-Vanguard](https://github.com/aluprince/Vector-Vanguard) | Go, Python, LLMs

**Automated web research and outreach pipeline**

A pipeline that combines data collection, LLM-assisted enrichment, and structured delivery.

- Web scraping and data extraction
- Context-aware LLM enrichment
- Structured output processing
- Telegram Bot API integration

---

## Engineering Focus

**Backend systems**
- REST API design and service boundaries
- Error handling and validation
- Idempotency and reliable request processing
- Pagination and database query design
- Integration testing and failure handling

**Data and financial infrastructure**
- PostgreSQL and raw SQL
- Transactions, atomicity, and data integrity
- Double-entry accounting
- Integer-based monetary representation
- Database-backed integration tests

**AI engineering and integration**
- Embeddings and semantic similarity
- Vector search and retrieval pipelines
- Retrieval-augmented generation (RAG)
- LLM API integration and structured outputs
- Context construction and source traceability
- Data extraction and LLM-assisted automation

---

## Tech Stack

| Category | Technologies |
|---|---|
| Languages | Go, Python, JavaScript |
| Backend | FastAPI, Node.js, REST APIs |
| Databases | PostgreSQL, SQL, pgvector |
| AI integration | Groq API, embedding models, semantic search, RAG |
| Testing | pytest, integration testing |
| Infrastructure | Docker, Docker Compose, GitHub Actions, Linux, Render |
| Integrations | Telegram Bot API, external APIs |

---

## Engineering Principles

- **Correctness before convenience.** Financial operations should preserve accounting invariants, not merely return successful HTTP responses.
- **Test real behavior.** Database-backed integration tests reveal failures that mocked dependencies can hide.
- **Design for failure.** Idempotency, transaction boundaries, validation, and error handling matter as much as the happy path.
- **Understand the abstraction.** I want to understand SQL queries, vector similarity, retrieval, and request lifecycles rather than depend blindly on frameworks.
- **Use AI where it adds value.** Semantic retrieval and LLM integration should solve concrete problems, with attention to relevance, context, and output quality.

---

## Contact

- **Email:** [aluprince03@gmail.com](mailto:aluprince03@gmail.com)
- **LinkedIn:** [linkedin.com/in/alu-onari](https://www.linkedin.com/in/alu-onari)
- **Portfolio:** [alu.lenoben.top](https://alu.lenoben.top)

