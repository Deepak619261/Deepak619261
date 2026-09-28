### Hi, I'm Deepak 👋

**Software Development Engineer (SDE)** working mainly in **C# / .NET**, and now **Go**. I build systems that move a lot of data reliably: ingestion pipelines, event-driven services, caching, and PostgreSQL performance.

**Stack:** C# · .NET · Go · PostgreSQL · Redis · Kafka · Docker · Python (RAG/LLM apps) · React/TypeScript

---

#### 🔧 Featured projects

| Project | What it shows |
|---|---|
| [**lead-ingest-go**](https://github.com/Deepak619261/lead-ingest-go) | Streaming CSV ingestion pipeline in **Go**: bounded worker pool, key-sharded batch writers, backpressure, retries, checkpoint/resume. **150K rows → Postgres in 2.6 s, 89× faster** than a per-row design, 0 rows lost under injected failures. |
| [**URL-shortner**](https://github.com/Deepak619261/URL-shortner) | **.NET 9 + Postgres + Redis**: cache-aside redirects, async click analytics via `Channel<T>` batch flush, distributed token-bucket rate limiting. |
| [**VelocityStream**](https://github.com/Deepak619261/VelocityStream-) | Event-driven **.NET 8 + Kafka** microservices: producer API, scalable consumer groups with partition rebalancing, persistence via EF Core. |
| [**GRIDwar**](https://github.com/Deepak619261/GRIDWAR) · [live](https://gridwar-deepaks-projects-70214c28.vercel.app/) | Real-time multiplayer grid game on **.NET 9 SignalR + Angular 20**: WebSocket broadcast to every client, lock-free conflict resolution via compare-and-swap (`ConcurrentDictionary.TryUpdate`), optimistic UI, 60 fps canvas rendering 2,500 cells. |
| [**sales-sequence-intelligence-copilot**](https://github.com/Deepak619261/sales-sequence-intelligence-copilot) | **RAG** app (FastAPI): hybrid search (embeddings + BM25 with RRF), cross-encoder reranking, prompt-injection defence, pluggable vector stores (Qdrant / Azure AI Search). |
| [**CodeGenie**](https://github.com/Deepak619261/CodeGenie) | Cost-aware **coding agent for VS Code**: three-tier model router across local and cloud LLMs, per-task budget with a hard stop, semantic context compaction. |

| [**whatsapp-agent**](https://github.com/Deepak619261/whatsapp-agent) | AI appointment-setter agent over **real WhatsApp** (Node.js/Express, Twilio + Meta WhatsApp Cloud API): swappable LLM backends (Claude / OpenAI / Gemini / Groq) behind one interface, per-lead message **debouncing** that groups bursts into a single reply, humanized typing delays and message splitting, live SSE control panel. |
---

#### 📈 Also
- **500+ DSA problems** solved: [DATA-STRUCTURES-ALGORITHMS](https://github.com/Deepak619261/DATA-STRUCTURES-ALGORITHMS)
- **Currently:** going deep on Go concurrency and distributed systems

📫 [LinkedIn](https://www.linkedin.com/in/deepak-kumar-018b0222a/) · [deepakarya140831@gmail.com](mailto:deepakarya140831@gmail.com)
