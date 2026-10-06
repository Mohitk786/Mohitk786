### Mohit Kumar

Software engineer at [Lunacal](https://mylunacal.co). I build backend-heavy products end to end, usually where **AI meets real developer workflows**: webhooks, queues, LLMs, and the boring parts that make them reliable.

---

#### Things I've built

**[AI PR Reviewer](https://github.com/Mohitk786/ai-pr-reviewer)** · GitHub App · TypeScript, Next.js, Postgres, pg-boss<br>
Reviews pull requests on open/push and posts inline comments. Webhooks are verified and stored before anything else runs, slow LLM work goes to a separate worker, and every comment the model produces is checked against the real diff lines before it's posted, because one hallucinated line makes GitHub reject the whole review.

**[token-bucket-limiter](https://github.com/Mohitk786/Rate-Limiter)** · Express middleware · Redis, Lua<br>
A distributed rate limiter. The refill-and-decrement step runs as one Lua script inside Redis, so the decision stays atomic across any number of Node processes. No race conditions, no extra lock layer.

**[lunacal-mcp](https://github.com/Mohitk786/lunacal-mcp)** · MCP server · TypeScript, Docker<br>
Lets AI assistants check availability and book meetings on Lunacal through the Model Context Protocol.

**[Who's #1](https://whos1.bid)** · live<br>
One leaderboard spot. Pay to take it, and anyone can outbid you. A small experiment in getting attention for a simple product. Its sibling, [WorldMap](https://worldmap.whos1.bid), lets you claim territory on a map.

---

#### What I work with

**Product & backend:** `TypeScript` `Node.js` `Next.js` `PostgreSQL` `Prisma` `Redis` `ClickHouse` `Docker` `AWS` `Azure`<br>
**AI:** `Python` `FastAPI` `LangChain` `LangGraph` `RAG` `Vector DBs` `Neo4j` `Mem0` `Ollama` `MCP` `OpenAI / Gemini APIs`

#### Right now

Building **Trace**, a product analytics tool on ClickHouse, and adding codebase-aware RAG to the PR reviewer: embeddings, hybrid retrieval and Redis-queued indexing.

---

Reach me at hi@ringjenny.com
