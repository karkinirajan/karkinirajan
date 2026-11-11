# AI/LLM Engineer & Python Backend Developer

I build **production GenAI systems** — RAG pipelines, LLM agents, and the backends and interfaces that run them — with a focus on answers you can trust and bills you can afford. 7 years across backend, AI, and cloud infrastructure.

## What I build
- **RAG that holds up in production** — chunking and embedding strategy, hybrid search (BM25 + vectors), reranking, metadata filtering, and eval loops that catch retrieval regressions before users do
- **LLM agents & tool calling** — multi-step agents with function calling, structured output, memory, and MCP integrations across GPT, Claude, and Gemini
- **LLM cost & latency work** — prompt caching, model routing, streaming (SSE/WebSockets), and batching to cut spend without cutting quality
- **The backend around the model** — FastAPI/Django services, async workers, queues, auth, and observability, shipped with Docker to AWS/GCP
- **Models behind APIs** — scoring and classification models (XGBoost, scikit-learn) served from FastAPI, with the data pipelines, background jobs, and webhooks that keep them fed
- **The product in front of it** — Next.js / React / TypeScript / Tailwind apps and Chrome (Manifest V3) extensions, with streaming UIs, typed API clients, and accessible, responsive design

## How I work
- **Existing codebases first** — most of my work lands in production systems that are already running. I map the architecture and conventions before changing anything, reuse what is there, and keep changes small enough to review.
- **Proof, not "should work"** — I run the real build, lint, type-check and test gates, test against real databases where it matters, and use mutation testing to check that the tests fail when the code is wrong.
- **Security as part of the job** — token and session handling, SSRF-safe outbound calls, secrets at rest, and webhook signature checks are reviewed as I go, not bolted on at the end.
- **Honest hand-off** — a README that matches reality, plus a plain record of what changed, how it was checked, and what was *not* verified.

## Stack
| Layer      | Tools |
|------------|-------|
| GenAI      | OpenAI, Anthropic Claude, Gemini, LangChain, LlamaIndex, Vercel AI SDK, Hugging Face |
| RAG        | pgvector, Pinecone, Elasticsearch, Cohere Rerank, embeddings, hybrid search, evals |
| Agents     | Tool/function calling, structured output, MCP, agentic workflows, Zep memory |
| Backend    | Python, FastAPI, Django, DRF, Flask, Celery, AsyncIO, WebSockets |
| Frontend   | React, Next.js (App Router), TypeScript, Tailwind CSS, shadcn/ui |
| Extensions | Chrome Manifest V3 |
| Data       | PostgreSQL, MySQL, MongoDB, Redis, Supabase |
| DevOps     | AWS, GCP, Azure, Docker, Kubernetes, Nginx, GitHub Actions, Railway, Vercel |
| Quality    | pytest, Vitest, Playwright, Ruff, mypy, ESLint, mutation testing |

## Reach out
📫 kneeraazon@gmail.com · [kneeraazon.com](https://kneeraazon.com) · [Upwork](https://www.upwork.com/freelancers/nirajankarki) · [LinkedIn](https://linkedin.com/in/kneeraazon)
