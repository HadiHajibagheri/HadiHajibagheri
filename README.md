<div align="center">

# ⚡ Hadi Hajibagheri | HajibagheriLabs

**AI Systems Engineer & Full-Stack Architect**

*Optimizing Large Language Model inference & building high-concurrency, zero-oversell web applications.*

[![GitHub Followers](https://img.shields.io/github/followers/HajibagheriLabs?style=social)](https://github.com/HajibagheriLabs)
[![Portfolio](https://img.shields.io/badge/Profile-HajibagheriLabs-101010?style=flat&logo=github)](https://github.com/HajibagheriLabs)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hadi_Hajibagheri-0A66C2?style=flat&logo=linkedin)](https://linkedin.com)

---

</div>

## 🔭 Overview & Engineering Philosophy

I operate at the intersection of **Hardware-Aware AI Systems Optimization** and **High-Concurrency Full-Stack Architecture**:

- 🚀 **AI & Inference Engineering:** Building custom LLM engines that stream weights layer-by-layer to execute massive models on limited hardware, designing hybrid RAG pipelines (BGE-M3 / Qdrant / RRF), and optimizing sparse MoE architectures.
- ⚡ **Full-Stack Systems:** Constructing production-grade web systems where correctness is enforced at the database layer — using Postgres Row-Level Security (RLS), atomic conditional state updates, and `EXCLUDE USING GIST` constraints to prevent race conditions and double-bookings.

---

## 🛠️ Tools & Technologies

### 🤖 AI / ML & Systems
<p left>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,pytorch,docker,c,cpp,linux,bash&theme=dark" />
  </a>
</p>

### 💻 Full-Stack Web & Databases
<p left>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,react,ts,js,tailwind,django,postgres,mysql,mongodb&theme=dark" />
  </a>
</p>

### 🔧 Development & Environment
<p left>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vscode,github,git,postman,vercel,figma&theme=dark" />
  </a>
</p>

---

## ⚡ Featured Projects

### 🤖 AI Research & Inference Engines

<details open>
<summary><b>System Optimization & Retrieval Systems</b></summary>
<br />

| Project | Description | Key Innovations |
| :--- | :--- | :--- |
| **[RocketLLM](https://github.com/HajibagheriLabs/RocketLLM)** | Local LLM inference engine running models far larger than available VRAM. | Layer-by-layer streaming, hardware profiler, packed 4-bit quant, cyclic layer cache. |
| **[PARSA-RAG](https://github.com/HajibagheriLabs/PARSA-RAG)** | Persian-language multi-expert RAG system for engineering domains. | Docling layout parsing, BGE-M3 dense/sparse hybrid search, Qdrant collection routing. |
| **[Marginalia](https://github.com/HajibagheriLabs/Marginalia)** | AI Document QA portal with grounded citation validation. | Reciprocal Rank Fusion (RRF), server-side citation verification, Evidence Rail UI. |

</details>

### 💻 Production Full-Stack Platforms

<details open>
<summary><b>High-Concurrency Web Infrastructure</b></summary>
<br />

| Project | Description | Core Guarantees |
| :--- | :--- | :--- |
| **[Meridian](https://github.com/HajibagheriLabs/Meridian)** | Multi-tenant SaaS CRM and business dashboard. | Database-level Row-Level Security (RLS) via `SET LOCAL` transactions, Better Auth, Stripe. |
| **[Openings](https://github.com/HajibagheriLabs/Openings)** | Real-time scheduling engine preventing double-booking. | Postgres `EXCLUDE USING GIST` constraints, temporary holds, server-side IANA time math. |
| **[Counter](https://github.com/HajibagheriLabs/Counter)** | E-commerce storefront and merchant admin portal. | Zero-oversell stock guards (conditional atomic updates), Next.js 16 Cache Components. |

</details>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=HajibagheriLabs&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HajibagheriLabs&layout=compact&theme=tokyonight&hide=html,css" />

<br /><br />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=HajibagheriLabs&theme=tokyonight" alt="GitHub Streak" />

</div>

---

<div align="center">

> *"The engine profiles the machine; the database enforces the invariants."*

*Designed and built by Hadi Hajibagheri.*

</div>
