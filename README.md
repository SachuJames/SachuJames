<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0f,50:0e7490,100:22d3ee&height=200&section=header&text=Sachu%20James&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20Engineer%20%E2%80%A2%20Low-Latency%20Systems%20%E2%80%A2%20FinTech%20Aspirant&descAlignY=58&descAlign=50&descSize=18&descColor=99f6e4" width="100%"/>
</div>

<br/>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=18&duration=3000&pause=1000&color=22D3EE&center=true&vCenter=true&width=750&lines=Backend+engineer+building+low-latency+distributed+systems;Shipped+an+API+gateway%3A+Fastify%2C+Redis%2C+Postgres%2C+React;Rust+systems+tooling+%2B+open-source+contributor;5th+Sem+CSE+%40+KTU+%7C+Graduating+2027" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/Open%20to-SDE%20%2F%20Backend%20Roles-0ea5e9?style=flat&logo=briefcase&logoColor=white"/>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=SachuJames&label=Profile%20Views&color=22d3ee&style=flat"/>
</div>

---

## 🧠 What I Build

Backend-focused engineer with hands-on experience building production-grade systems involving reverse proxies, caching layers, async pipelines, and REST API design. I think in terms of latency, throughput, and tradeoffs — not just features.

```
Shipped:
→ lightweight-api-gateway — programmable HTTP gateway (Fastify, Redis Lua
  rate limiting, circuit breakers, zero-downtime config reload)
→ linux-digital-detective — Rust forensics toolkit (92 tests, clippy-clean)
```

---

## 🚀 Featured Projects

<div align="center">
  <a href="https://github.com/SachuJames/lightweight-api-gateway">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=SachuJames&repo=lightweight-api-gateway&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=2dd4bf&text_color=c9d1d9&border_radius=12"/>
  </a>
  <a href="https://github.com/SachuJames/linux-digital-detective">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=SachuJames&repo=linux-digital-detective&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=2dd4bf&text_color=c9d1d9&border_radius=12"/>
  </a>
</div>

---

## ⚙️ How the Gateway Works

```
Client request
     │
     ▼
Fastify (HTTP/HTTPS) — request ID + structured JSON logs
     │
     ▼
Routing engine — compiled regexes, priority then specificity
     │
     ▼
Middleware chain — JWT auth + RBAC → plugin hooks →
│   Redis Lua token-bucket rate limiting → circuit breaker
     │
     ▼
Reverse proxy (undici) — streaming, per-route timeouts
     │
     ▼
Upstream service

Config plane (zero restarts):
PostgreSQL (source of truth) → versioned snapshots →
│   Redis pub/sub → every instance swaps atomically
```

---

## 📊 Measured, Not Claimed

| Metric | Value |
|--------|-------|
| Proxy overhead (p50) | **+1.9ms** vs direct upstream |
| Route matching | **~1.2k matches/sec** over 2,000 routes |
| Rate-limit checks | **~4.4k/sec** via Redis Lua |
| Tests | **196 passing** (unit + integration/e2e + UI) |
| Config reload | **zero-downtime**, versioned, audited |

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
[![Portfolio](https://img.shields.io/badge/Portfolio-sachu--james.vercel.app-14b8a6?style=for-the-badge&logo=vercel&logoColor=white)](https://sachu-james.vercel.app/)

<br/>

**SDE / Backend roles • Collaborations • Interesting engineering problems**

</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:22d3ee,50:0e7490,100:0a0a0f&height=120&section=footer&animation=fadeIn" width="100%"/>
</div>
