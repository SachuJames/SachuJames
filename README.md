<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0f,50:6366f1,100:8b5cf6&height=200&section=header&text=Sachu%20James&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20Engineer%20%E2%80%A2%20Low-Latency%20Systems%20%E2%80%A2%20FinTech%20Aspirant&descAlignY=58&descAlign=50&descSize=18&descColor=a5b4fc" width="100%"/>
</div>

<br/>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=18&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=750&lines=Backend+engineer+building+low-latency+distributed+systems;Shipped+an+API+gateway%3A+Fastify%2C+Redis%2C+Postgres%2C+React;Rust+systems+tooling+%2B+open-source+contributor;5th+Sem+CSE+%40+KTU+%7C+Graduating+2027" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/Open%20to-SDE%20%2F%20Backend%20Roles-6366f1?style=flat&logo=briefcase&logoColor=white"/>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=SachuJames&label=Profile%20Views&color=6366f1&style=flat"/>
</div>

---

## 🧠 What I Build

Backend-focused engineer with hands-on experience building production-grade systems involving caching layers, async pipelines, reverse proxies, and REST API design. I think in terms of latency, throughput, and tradeoffs — not just features.

```
Shipped:
→ ProjectZyra — multi-platform price comparison engine (10s → 4ms via Redis)
→ lightweight-api-gateway — programmable HTTP gateway (Fastify, Redis Lua
  rate limiting, circuit breakers, zero-downtime config reload)
→ linux-digital-detective — Rust forensics toolkit (92 tests, clippy-clean)
```

---

## 🚀 Featured Projects

<div align="center">
  <a href="https://github.com/SachuJames/lightweight-api-gateway">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=SachuJames&repo=lightweight-api-gateway&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6366f1&icon_color=8b5cf6&text_color=c9d1d9&border_radius=12"/>
  </a>
  <a href="https://github.com/SachuJames/linux-digital-detective">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=SachuJames&repo=linux-digital-detective&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6366f1&icon_color=8b5cf6&text_color=c9d1d9&border_radius=12"/>
  </a>
  <a href="https://github.com/SachuJames/ProjectZyra">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=SachuJames&repo=ProjectZyra&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6366f1&icon_color=8b5cf6&text_color=c9d1d9&border_radius=12"/>
  </a>
</div>

---

## 🏗️ System Architecture — ProjectZyra
```
User Request
     │
     ▼
  Nginx (reverse proxy)
     │
     ├──────────────────────┐
     ▼                      ▼
React Frontend         FastAPI Backend
                            │
                    ┌───────┴────────┐
                    ▼                ▼
              Redis Cache      asyncio.gather()
              (TTL: 15min)    (parallel scrapers)
                    │                │
                    │    ┌───────────┼───────────┐
                    │    ▼           ▼           ▼
                    │  Amazon    Flipkart     SerpAPI
                    │    └───────────┼───────────┘
                    ▼                ▼
              PostgreSQL ←── NLP Normalizer
              (products,     (sentence-transformers
              price_history,  cosine similarity > 0.92)
              users, alerts)
```

---

## ⚡ Performance Metrics

| Metric | Value |
|--------|-------|
| Cache hit response time | **4ms** (Redis) |
| Cache miss response time | **~10s** (parallel scrape) |
| Speedup from caching | **2,700x** |
| Platforms scraped in parallel | **3 simultaneous** |
| NLP similarity threshold | **0.92 cosine** |
| Auth method | **JWT + Google OAuth 2.0** |

---

## 🛠️ Tech Stack

<table align="center">
  <tr>
    <td align="center"><strong>Languages</strong></td>
    <td><img src="https://skillicons.dev/icons?i=python,rust,cpp,js,ts,c,java&theme=dark"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Backend</strong></td>
    <td><img src="https://skillicons.dev/icons?i=fastapi,nodejs,express&theme=dark"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Frontend</strong></td>
    <td><img src="https://skillicons.dev/icons?i=react,html,css,tailwind&theme=dark"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Database & Cache</strong></td>
    <td><img src="https://skillicons.dev/icons?i=postgresql,redis&theme=dark"/></td>
  </tr>
  <tr>
    <td align="center"><strong>DevOps</strong></td>
    <td><img src="https://skillicons.dev/icons?i=docker,nginx,linux,git&theme=dark"/></td>
  </tr>
</table>

---

## 🤝 Open Source

Real contributions to Python backend projects:

- [strawberry-graphql/strawberry#4644](https://github.com/strawberry-graphql/strawberry/pull/4644) — Allow passing a dict as the config argument of Schema
- [encode/uvicorn#3172](https://github.com/encode/uvicorn/pull/3172) — Fix TCP_NODELAY not being set on sockets accepted from a pre-bound listener
- [Lumiwealth/lumibot#1182](https://github.com/Lumiwealth/lumibot/pull/1182) — Fix stale daily fills after loading minute data
- [alpacahq/alpaca-py#792](https://github.com/alpacahq/alpaca-py/pull/792) — Add CashInterest model to CreateAccountRequest

---

## 🏆 Certifications

<div align="center">

![Google Cloud](https://img.shields.io/badge/Google%20Cloud-LLM%20%26%20GenAI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Google Cybersecurity](https://img.shields.io/badge/Google-Cybersecurity-34A853?style=for-the-badge&logo=google&logoColor=white)
![GDSC](https://img.shields.io/badge/GDSC-Backend%20Web%20Dev-EA4335?style=for-the-badge&logo=google&logoColor=white)

</div>

---

## 📫 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-SachuJames-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SachuJames)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sachu%20James-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sachu-li)
[![Portfolio](https://img.shields.io/badge/Portfolio-sachu--james.vercel.app-6366f1?style=for-the-badge&logo=vercel&logoColor=white)](https://sachu-james.vercel.app/)

<br/>

**SDE / Backend roles • Collaborations • Interesting engineering problems**

</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8b5cf6,50:6366f1,100:0a0a0f&height=120&section=footer&animation=fadeIn" width="100%"/>
</div>
