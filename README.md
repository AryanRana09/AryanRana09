<h1 align="center">
  Hi, I'm Aryan Rana&nbsp;
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="32" alt="waving hand"/>
</h1>

<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg">
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&pause=1000&color=4A90D9&center=true&vCenter=true&width=650&lines=Python+%2F+Django+Backend+Developer;Async+Pipelines+%26+RAG+Knowledge+Bases;REST+APIs+%7C+Redis+%7C+SSE;Open+to+Fresher+%26+Intern+Roles" alt="Typing animation"/>
  </a>
</p>

<p align="center">
  📍 New Delhi, India
</p>

<p align="center">
  <a href="https://linkedin.com/in/aryan-rana-827b4b40a">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:aryanrana092005@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/AryanRana09">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

## 🚀 About Me

Backend developer (Python / Django) who likes fixing the slow, blocking parts of a system. During a 6-month internship at **Ravan AI** I turned a 10–15 minute sitemap crawl into a 10–30 second async pipeline, built RAG knowledge bases, and QA-tested tool-calling AI agents. On my own time I build APIs with real constraints: caching, spatial indexes, and optimization algorithms.

- 🔭 Currently building an **Intercom-style customer support widget** and a **bare-metal Gemini tool-calling agent** (no frameworks).
- 🌱 Deepening my knowledge of async programming, vector databases, and LLM function-calling.
- 🎓 Pursuing a **BCA at IGNOU** (expected June 2027).
- 💬 Ask me about Django, SSE, RAG pipelines, or wiring up AI agents from scratch.
- 📬 **Looking for:** Python/Django backend fresher or internship roles.

---

## 🛠️ Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/Django%20REST%20Framework-A30000?style=flat-square&logo=django&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Databases & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Neon](https://img.shields.io/badge/Neon%20DB-00E599?style=flat-square&logo=neon&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone%20(Vector%20DB)-000000?style=flat-square&logo=pinecone&logoColor=white)

**AI / LLM**

![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square&logo=databricks&logoColor=white)

**Concepts & Tools**

![SSE](https://img.shields.io/badge/Server--Sent%20Events-4A90D9?style=flat-square&logo=serverfault&logoColor=white)
![Async](https://img.shields.io/badge/Async%20Programming-6DB33F?style=flat-square&logo=asyncapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 💼 Experience

### Backend Development & QA Intern — Ravan AI
`Jan 2026 – Jul 2026`
<!-- TODO: make sure these dates match your LinkedIn role -->

- ⚡ Rewrote a **synchronous sitemap fetcher as async**: crawls of very large sites (~52k sitemaps) dropped from **10–15 minutes to roughly 10–30 seconds**.
- 📡 Replaced a blocking sitemap-discovery API with a **Server-Sent Events (SSE)** endpoint that streams results as they are fetched, cutting **time-to-first-result to ~15 seconds**.
- 🗜️ Stopped the backend from sending tens of thousands of URLs in one response: **gzip-compressed** them, cached them in **Redis** with a short TTL, and streamed them to the UI in configurable chunks (default 500, adjustable from the admin panel).
- 📦 Built **Redis-backed key hashing** for paginated "load more", eliminating frontend memory overload from oversized API responses.
- 🧠 Integrated **Pinecone** to build searchable knowledge bases from scraped content, powering a **RAG-based AI chatbot**.
- 🐛 Root-caused an unreliable AI agent to **context-window overflow** from oversized content chunks, and documented the findings that informed the fix.
- ✅ QA-tested a **tool-calling AI agent** (Gemini Flash Live Preview): dynamic user-defined tools, function-call parsing, and real-time task execution, surfacing bugs before release.

---

## 📌 Featured Projects

### ⛽ Fuel-Efficient Route Planner API
A Django REST API that takes any two US locations and returns the driving route plus the cheapest sequence of fuel stops along it.
- Cleaned, deduped, and geocoded **6,600+ fuel stations offline** (zero external calls during import).
- **SciPy KD-tree** corridor search plus a **greedy lookahead optimizer** (the classic Gas Station Problem) for minimum fuel cost.
- Exactly **one routing call per request**, with LRU caching: **~22 ms** on cached repeats. GeoJSON output for map visualization, **111 tests**.
- **Stack:** `Python` · `Django REST Framework` · `SciPy` · `SQLite` · `Pytest`
- 🔗 [View repo](https://github.com/AryanRana09/fuel-route-assessment)

### 🎧 Intercom Clone — `In Progress`
A customer-support widget platform where businesses sign up, generate an embeddable chat widget for their site, and receive real-time notifications when a visitor sends a message.
- Google OAuth authentication, live messaging UI, and an embeddable widget system.
- Planned AI chatbot for automated first-response support.
- **Stack:** `Django` · `Neon DB (Serverless PostgreSQL)` · `Google OAuth`

### 🤖 Gemini Tool-Calling Agent — `In Progress`
A minimal AI agent built from scratch, with no frameworks and no AI-assisted code, to master the Gemini function-calling loop end to end.
- Parses function-call responses, executes real API calls, and returns results to the model for a final reply.
- Retry logic for malformed tool calls and graceful fallback prompts for failed responses.
- **Stack:** `Python` · `Gemini API (Function Calling)` · `Open-Meteo API`

---

## 🎓 Education

- **Bachelor of Computer Applications (BCA)** — IGNOU · *Expected June 2027*
- **Full Stack Development (Python / Django)** — DUCAT · *Certification Course*

---

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AryanRana09/AryanRana09/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AryanRana09/AryanRana09/output/github-contribution-grid-snake.svg" />
    <img alt="Snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/AryanRana09/AryanRana09/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

<p align="center">
  <i>Open to Python/Django backend roles — let's build something.</i>
</p>
