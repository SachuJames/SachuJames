<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0f,50:6366f1,100:8b5cf6&height=200&section=header&text=Sachu%20James&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20Engineer%20%E2%80%A2%20Low-Latency%20Systems%20%E2%80%A2%20FinTech%20Aspirant&descAlignY=58&descAlign=50&descSize=18&descColor=a5b4fc" width="100%"/>
</div>

<br/>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=18&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=750&lines=Backend+engineer+building+low-latency+distributed+systems;Built+price+comparison+engine+with+0.004s+cache+response;FastAPI+%7C+PostgreSQL+%7C+Redis+%7C+Docker+%7C+Playwright;5th+Sem+CSE+%40+APJ+Abdul+Kalam+University+%7C+Grad+2027" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/Open%20to-Backend%20SDE%20Internships-6366f1?style=flat&logo=briefcase&logoColor=white"/>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=SachuJames&label=Profile%20Views&color=6366f1&style=flat"/>
</div>

---

## 🧠 What I Build

Backend-focused engineer with hands-on experience building production-grade systems involving caching layers, async scraping pipelines, NLP-based data processing, and REST API design. I think in terms of latency, throughput, and tradeoffs — not just features.
```
Currently building: ProjectZyra
→ Multi-platform price comparison engine
→ Reduced price-fetch latency from 10s → 4ms using Redis
→ Parallel async scrapers across Amazon, Flipkart, Nykaa
→ NLP deduplication with sentence-transformers (cosine similarity)
→ Deployed behind Nginx reverse proxy with Docker Compose
```

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

## 🚀 ProjectZyra — Production System

<div align="center">
  <a href="https://github.com/SachuJames/ProjectZyra">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=SachuJames&repo=ProjectZyra&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6366f1&icon_color=8b5cf6&text_color=c9d1d9&border_radius=12"/>
  </a>
</div>

<br/>

**Engineering decisions that matter:**

- **Why Redis?** Scraping 3 platforms takes ~10s. Caching results with 15min TTL reduces repeat queries to 4ms — 2,700x improvement
- **Why async scraping?** `asyncio.gather()` runs all platform scrapers in parallel, cutting total scrape time from ~30s to ~10s
- **Why NLP matching?** "iPhone 15 128GB Black" on Amazon ≠ "APPLE iPhone 15 (128 GB) Black" on Flipkart — cosine similarity at 0.92 threshold correctly groups them
- **Why Nginx?** Single entry point for frontend + API. Handles routing, avoids CORS issues in production

**Stack:** `Python 3.11` `FastAPI` `React 18` `PostgreSQL 15` `Redis 7` `Playwright` `sentence-transformers` `Docker` `Nginx` `JWT` `SerpAPI`

---

## 🛠️ Tech Stack

<table align="center">
  <tr>
    <td align="center"><strong>Languages</strong></td>
    <td><img src="https://skillicons.dev/icons?i=python,cpp,js,c,java&theme=dark"/></td>
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

<br/>

**Backend SDE internships • Collaborations • Interesting engineering problems**

</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8b5cf6,50:6366f1,100:0a0a0f&height=120&section=footer&animation=fadeIn" width="100%"/>
</div>
