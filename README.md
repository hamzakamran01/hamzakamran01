I design and ship production agentic AI systems. Founder of **Zaaric**, where I build RAG pipelines, autonomous agents, and automation infrastructure for clients across the US and EU. Currently building **HealthDost**, an AI health memory platform that is live with real users.

My bias is toward systems that survive contact with production: grounded retrieval, deterministic guardrails around probabilistic components, and a cost per request that still works at scale.

## Now

- Architecting HealthDost's contextual memory layer: tiered profile compilation, fact supersession chains, and multi-session RAG chat
- Leading delivery and US market expansion at Zaaric
- Operations team, Qimam Fellowship Pakistan 2026, and mentor to the 2026 cohort

## Selected work

**HealthDost** · AI health memory platform · *private, live with users*

Ingests medical documents, including scanned and hybrid records, through a vision triage, extraction, and structured parsing pipeline, then commits them to a pgvector event timeline that answers patient questions over RAG with strict anti-hallucination grounding. A separate trend engine evaluates 14 biomarkers against deterministic threshold rules and escalates alerts with no LLM in the decision path, so the model explains the finding but never decides it.

`Next.js 16` `Supabase + pgvector` `GPT-4o` `LangChain` `Vercel Cron`

**Zaaric** · AI systems agency · *private client work*

10+ production systems delivered for clients in the US and EU: RAG assistants, internal copilots, lead generation automation, and SME back-office agents wired into CRM, invoicing, and inventory.

`OpenAI Agents SDK` `MCP` `FastAPI` `Next.js` `PostgreSQL` `RabbitMQ`

**Digital Queue Management Platform** · *live since September 2024*

Real time queue orchestration for multi branch operations. Cut average customer wait time by 67%, GDPR compliant, WebSocket driven, running continuously since launch.

`NestJS` `React` `PostgreSQL` `Redis` `AWS`

[Live](https://digital-queueing-system.vercel.app) · [Code](https://github.com/hamzakamran01/digital-queueing-system)

**AI Career Recommendation Engine** · *public research*

Hybrid recommender over the full O\*NET 29.0 occupational taxonomy: 40% classifier probability blended with 60% embedding cosine similarity, built on RIASEC derived feature engineering and K-Means segmentation, with automated skill gap analysis and generated learning roadmaps. Shipped and documented across four phases.

`Python` `scikit-learn` `sentence-transformers` `pandas`

[Notebooks](https://www.kaggle.com/code/hamzakamran001/ai-career-recommendation-phase-3) · [Code](https://github.com/hamzakamran01/AI-career-recommendation-model)

**Elevated Gears** · 3D product configurator · *private client project*

Real time WebGL configurator for a manufacturer selling into US and EU markets, with a full GLTF asset pipeline, persisted configurations, and checkout.

`React Three Fiber` `Next.js 15` `Prisma` `Stripe`

Enterprise work I cannot open source includes a HIPAA compliant clinical trials platform for a US pharmacy operator and a multi region luxury e-commerce system processing over €2M per month. Architecture and tradeoffs are documented on my side, and I am glad to walk through the system design directly.

## Stack

| | |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, SQL, Kotlin |
| **AI** | OpenAI Agents SDK, Claude API, LangChain, MCP, pgvector, RAG, sentence-transformers |
| **Backend** | FastAPI, NestJS, Node.js, PostgreSQL, Redis, Supabase, RabbitMQ |
| **Frontend and 3D** | Next.js, React, Tailwind, Three.js, React Three Fiber |
| **Infra** | Docker, AWS, Vercel, GitHub Actions |

## Recognition

- Qimam Fellow 2025, a McKinsey vetted selection of 38 fellows nationally
- Punjab Delegate, National Youth Summit 2025

## Contact

**[hamzakamran.tech](https://hamzakamran.tech)** is the fastest way to see the full picture.

[LinkedIn](https://www.linkedin.com/in/hamza-kamran-7b1a85294) · hamzakamran843@gmail.com
