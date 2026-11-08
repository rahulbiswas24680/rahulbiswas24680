<div align="center">
  <h1>Hi, I'm Rahul Biswas 👋</h1>
  <p><strong>Backend Engineer</strong> — Django &amp; LLM systems · 4+ years</p>

  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20to%20Remote-4ECDC4?style=flat-square" />
</div>

---

### 🚀 About

Backend engineer, **4+ years** in production Django. I build the parts that have to stay correct under
retries and concurrency — payments, inventory, multi-tenant APIs — on **PostgreSQL**, **Celery** and
**Redis**. Lately I've been working on the other end: **LLM agent orchestration** and deterministic
verification, where the interesting question is what a model is allowed to decide.

- Six client backends in production — logistics dispatch, facility booking with inventory, ERP, and a
  rewards/syllabus platform
- Cut API latency ~40% and server load ~30% through query analysis, composite indexes and Redis caching
- Built a self-hostable agent engine where the provider, planner, tools and memory each sit behind a
  Protocol

---

### 🔥 Featured Projects

**[EventFlow — paid ticketing platform](https://github.com/rahulbiswas24680/eventflow)** · [Live demo](https://eventflow-gray.vercel.app)
Checkout runs as an idempotent Celery job, so a retried Stripe delivery cannot issue a second ticket, and
inventory is row-locked before it is decremented. QR, PDF and email fulfilment run on separate queues.
`Django 5 · DRF · PostgreSQL · Celery/Redis · Stripe · Docker`

**Pramana — deterministic fact-checker for finance copy** *(private, walkthrough on request)*
Extracts every percentage, basis-point move and margin from an article and checks it by arithmetic or
code execution against the article's own figures. No model is allowed to judge a match — the model only
reads. 306 offline tests, sha256-pinned regression corpus.
`Python · Decimal · asyncio · pytest`

**Utpatti Core — self-hostable agent engine** *(private, walkthrough on request)*
A publishing pipeline of twelve interchangeable stages (discovery → gap analysis → research → draft →
claim check → review → SEO/social) with a Protocol behind every seam — provider, planner, tool, memory,
search — so one graph runs on OpenAI, Anthropic, Gemini, OpenRouter or DeepSeek.
`Python · asyncio · Pydantic v2 · FastAPI · httpx`

---

### 🛠️ Stack

**Backend**: Python · Django · DRF · FastAPI · Pydantic v2 · asyncio
**Data**: PostgreSQL · Redis (cache, broker, results) · indexing, N+1 elimination
**Async**: Celery · beat · queue routing · retries with hard time limits
**LLM**: OpenAI · Anthropic · Gemini · OpenRouter · DeepSeek · tool calling · agent evals
**Ops**: Docker · Compose · Nginx · Gunicorn · AWS (EC2, S3) · DigitalOcean · GitHub Actions / GitLab CI

---

### 💼 Experience

**Django Developer** @ **Smilebots — WisdomTree Edutech LLP** (Sep 2022 – Present)
- Django/DRF backends for six client builds: RBAC, admin and analytics dashboards, third-party integrations
- Query analysis, composite indexes and Redis caching: ~40% faster APIs, ~30% lower server load
- Celery for background work and integrations, with retries and hard time limits so failures stay contained

---

### 📊 Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=rahulbiswas24680&show_icons=true&theme=radical)

---

### 📫 Get in Touch

- **Email**: rahulbss16@gmail.com
- **LinkedIn**: [linkedin.com/in/rahul-biswas-79aa4a1a4](https://www.linkedin.com/in/rahul-biswas-79aa4a1a4/)
- **Portfolio**: [portfolio.rahulb.workers.dev](https://portfolio.rahulb.workers.dev/)
- 📍 Kolkata, India | Open to Remote
