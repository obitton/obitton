# Ofir Bitton

Backend and AI engineer in Jersey City. I build agent systems that run in production: MCP servers, RAG pipelines, and the plumbing that connects them to real business data.

Most of what I build is client work, so it stays private. This profile is the small public slice, and the rest is described below rather than shown.

## What is here

| Repo | |
|---|---|
| [opal-scene-search](https://github.com/obitton/opal-scene-search) | Semantic video scene search exposed as custom Optimizely Opal tools. Describe a moment in plain language, get the clip with timestamps and its license line. SigLIP embeddings over shot-level video, FastAPI, four registered agent tools. |
| [sourdough](https://github.com/obitton/sourdough) | A seeded organization simulator. Generates a fictional startup's whole event history, then replays it on a timeline you can scrub to any date. |
| [duvo-assessment](https://github.com/obitton/duvo-assessment) | An MCP server that does a category buyer's job: find products running short across stores, explain why, raise replenishment orders with a person approving. |
| [knowledge-base](https://github.com/obitton/knowledge-base) | A local, citable knowledge base over saved content. FTS5 plus local ONNX embeddings fused with reciprocal rank fusion, served to Claude Code and Codex over MCP. Zero runtime dependencies, and a README that argues why there is no vector database. |
| [RSJT](https://github.com/obitton/RSJT) | Operations tool for delegated repair jobs at my IT business. Expo app, Fastify API, Postgres with Drizzle, RepairShopr intake, technician updates, approvals, and payout reconciliation over Twilio. Rails first; the model comes later. |
| [GrubEyes](https://github.com/obitton/GrubEyes) | Camera-first React Native app. Photograph your fridge, Gemini reads the ingredients, recipes come back respecting allergies and dislikes. |

## Open source

[Reactive-Resume #2781](https://github.com/AmruthPillai/Reactive-Resume/pull/2781), merged: fixed multi-page PDF crashes and Gemini API ingestion errors.

## What I cannot open source

- **Enterprise financial MCP server** over JD Edwards for a commercial real estate client. Agent tool calls became parameterized SQL for GL, AP/AR, and budget-vs-actual, inside the client's existing access model. Penny-level accuracy was the requirement, so the model never did the arithmetic.
- **AI-native freight CRM** at CargoMatrix. RAG over Outlook mail and attachments using pgvector and Microsoft Graph, entity resolution to tie stray threads back to the right shipment, and human-in-the-loop quote drafts.
- **80+ n8n automation workflows** for logistics document processing, including an air cargo manifest pipeline that cut manifest entry from over half an hour to minutes.
- **I.R.I.S.**, a real-time inventory overlay for the extraction shooter ARC Raiders. C#/.NET Native AOT capture and rendering, MobileNetV3 embeddings through ONNX Runtime matched against a per-item reference database, and a recommendation engine that scores each item KEEP / SELL / RECYCLE from your active quests. Private while I decide whether to productize it.

## Background

Eight years running My Computer Tech, an IT services business in New York: a team of three, 10,000+ customers, 1,500+ services a year. That is where the customer-facing half of my work comes from. Forward deployed at Tenex, an Anthropic partner, including Claude SMB Tour workshops for SMB owners and operators. Before that, AI automation at CargoMatrix, with on-site deployments in a DHL warehouse.

BBA in Computer Information Systems from Baruch College, CUNY. Computer science at UMass Amherst before that. Salesforce Certified Agentforce Specialist.

## Open to

AI engineering, solutions architecture, forward deployed engineering, backend, security, and systems roles.

Python, TypeScript, Go, SQL. LangChain, MCP, RAG, agent tool-use. Postgres and pgvector, BigQuery, Pinecone. GCP, Azure, Docker, Cloud Run.

Reach me at ofir-bitton@outlook.com or on [LinkedIn](https://www.linkedin.com/in/ofir-bitton/).
