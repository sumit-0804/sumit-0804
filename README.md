<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                       SUMIT GOYAL // README.md                        -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<p align="center">
  <!-- Line 1: Name typed once -->
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=2000&pause=1000&color=A6E22E&center=true&vCenter=true&repeat=false&width=850&lines=SUMIT+GOYAL" alt="Sumit Goyal" />
  <br/>
  <!-- Line 2: Terminal Boot sequence loop -->
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2500&pause=1000&color=66D9EF&center=true&vCenter=true&width=850&lines=%3E+booting+sumit.goyal...;%3E+loading+developer.profile;%3E+initializing+AI+agents...;%3E+systems+online+%E2%9C%93" alt="System initialization" />
</p>

<p align="center">
  <a href="https://github.com/sumit-0804">
    <img src="https://img.shields.io/badge/GitHub-272822?style=for-the-badge&logo=github&logoColor=A6E22E" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/sumit--goyal">
    <img src="https://img.shields.io/badge/LinkedIn-272822?style=for-the-badge&logo=linkedin&logoColor=66D9EF" alt="LinkedIn" />
  </a>
  <a href="mailto:sumitg2004@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-272822?style=for-the-badge&logo=gmail&logoColor=F92672" alt="Email" />
  </a>
  <a href="https://github.com/sumit-0804?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-272822?style=for-the-badge&logo=github&logoColor=FD971F" alt="Repositories" />
  </a>
</p>

<br/>

```json
{
  "identity": {
    "name": "Sumit Goyal",
    "role": "Software Developer",
    "specialization": [
      "AI Agents",
      "Full-Stack Systems",
      "Real-Time Applications"
    ],
    "status": "building"
  },
  "mission": "Turn complex ideas into systems that actually work.",
  "currently": {
    "learning": [
      "Advanced Agentic Architectures",
      "Distributed Systems",
      "ML Engineering"
    ],
    "building": [
      "Multi-Agent Systems",
      "Developer Tools",
      "Data Intelligence Products"
    ]
  }
}
```

---

## `GET /about`

> **I build systems, not just interfaces.**

My work sits at the intersection of **AI agents, backend engineering, and full-stack product development**.

I enjoy taking an idea from:

`problem → architecture → agents → APIs → interface → deployment`

and turning it into something people can actually use.

<table>
<tr>
<td width="33%" valign="top">

### `01 // AGENTS`

Multi-agent systems built with **LangGraph**, including routing, parallel execution, debate, tool use, and self-correction.

</td>
<td width="33%" valign="top">

### `02 // SYSTEMS`

Backend systems with **FastAPI, Node.js, PostgreSQL, MongoDB, WebSockets, and streaming APIs**.

</td>
<td width="33%" valign="top">

### `03 // PRODUCTS`

Full-stack products using **Next.js, React, and TypeScript**, with a focus on real-time experiences and clean UX.

</td>
</tr>
</table>

---

## `GET /projects`

### `01` — AlphaForge AI

<a href="https://github.com/sumit-0804/AlphaForge-AI">
  <h3><b>Autonomous Investment Research & Paper Trading</b></h3>
</a>

```mermaid
flowchart TD
    In[INPUT] --> MD[Market Data]
    
    subgraph Agents [Specialist Agents]
        TA[Technical Agent]
        FA[Fundamental Agent]
        NA[News Agent]
        RA[Risk Agent]
        MD --> TA
        MD --> FA
        MD --> NA
        MD --> RA
    end

    Agents --> Debate
    
    subgraph Debate [Adversarial Framework]
        BULL[BULL] <-->|DEBATE| BEAR[BEAR]
    end

    Debate --> Decision[BUY / HOLD / SELL]
    Decision --> Loop[Portfolio + Learning Loop]

    classDef monokaiGreen fill:#272822,stroke:#A6E22E,color:#A6E22E;
    classDef monokaiPink fill:#272822,stroke:#F92672,color:#F92672;
    classDef monokaiCyan fill:#272822,stroke:#66D9EF,color:#66D9EF;

    class In,MD,Decision,Loop monokaiGreen;
    class TA,FA,NA,RA monokaiCyan;
    class BULL,BEAR monokaiPink;
```

**Key Features & Highlights:**
* **Parallel Specialist Agents:** Multi-disciplinary signal extraction across technicals, fundamentals, and news.
* **Adversarial Debate:** Bull vs Bear reasoning framework to evaluate trade resilience before execution.
* **Real-time & Adaptive:** Live streaming execution analysis integrated with vector-search trade memory.
* **Multi-Currency Engine:** Full paper trading simulation supporting global asset allocations.

<p align="left">
  <img src="https://img.shields.io/badge/Python-272822?style=flat-square&logo=python&logoColor=3776AB" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-272822?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI" />
  <img src="https://img.shields.io/badge/LangGraph-272822?style=flat-square&logo=langchain&logoColor=A6E22E" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Gemini-272822?style=flat-square&logo=google-gemini&logoColor=8E75B2" alt="Gemini" />
  <img src="https://img.shields.io/badge/Next.js-272822?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/MongoDB-272822?style=flat-square&logo=mongodb&logoColor=47A248" alt="MongoDB" />
</p>

---

### `02` — OmniQuery

<a href="https://github.com/sumit-0804/omniquery">
  <h3><b>Natural Language → Data Intelligence</b></h3>
</a>

```mermaid
flowchart TD
    Q["What were our top 10 products last quarter?"] --> Router[Router]
    Router --> SQL[SQL Agent]
    SQL --> Val[Validate Query]
    Val --> Table[Table Output]
    Val --> Chart[Chart Visualization]

    classDef monokaiGreen fill:#272822,stroke:#A6E22E,color:#A6E22E;
    classDef monokaiCyan fill:#272822,stroke:#66D9EF,color:#66D9EF;
    classDef monokaiPink fill:#272822,stroke:#F92672,color:#F92672;

    class Q monokaiGreen;
    class Router,SQL,Val monokaiCyan;
    class Table,Chart monokaiPink;
```

Ask questions about **Postgres, CSV, Parquet, and JSON** without writing SQL.

* **Text-to-SQL Generation:** Dynamic query assembly across multiple document types.
* **Safety Sandbox:** Query validation layer featuring strict read-only execution constraints.
* **Self-Correction Engine:** Automated retry loops for database-level visual and syntax fixes.
* **Real-time Pipeline:** Live agent state streaming directly to client interfaces.

<p align="left">
  <img src="https://img.shields.io/badge/Python-272822?style=flat-square&logo=python&logoColor=3776AB" alt="Python" />
  <img src="https://img.shields.io/badge/LangGraph-272822?style=flat-square&logo=langchain&logoColor=A6E22E" alt="LangGraph" />
  <img src="https://img.shields.io/badge/DuckDB-272822?style=flat-square&logo=duckdb&logoColor=FFF000" alt="DuckDB" />
  <img src="https://img.shields.io/badge/React-272822?style=flat-square&logo=react&logoColor=66D9EF" alt="React" />
</p>

---

### `03` — Code-Sentinel

<a href="https://github.com/sumit-0804/Code-Sentinel">
  <h3><b>Multi-Agent Code Review</b></h3>
</a>

```mermaid
flowchart TD
    PR[Pull Request] --> Sec[Security Agent]
    PR --> Log[Logic Agent]
    PR --> Perf[Performance Agent]

    Sec --> Dedup[Deduplication]
    Log --> Dedup
    Perf --> Dedup

    Dedup --> Rank[Severity Rank]
    Rank --> Final[Final Review]

    classDef monokaiGreen fill:#272822,stroke:#A6E22E,color:#A6E22E;
    classDef monokaiCyan fill:#272822,stroke:#66D9EF,color:#66D9EF;
    classDef monokaiOrange fill:#272822,stroke:#FD971F,color:#FD971F;

    class PR monokaiGreen;
    class Sec,Log,Perf monokaiCyan;
    class Dedup,Rank,Final monokaiOrange;
```

Five specialist agents independently review a pull request and merge findings into a unified actionable report.

<p align="left">
  <img src="https://img.shields.io/badge/TypeScript-272822?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-272822?style=flat-square&logo=nodedotjs&logoColor=339933" alt="Node.js" />
  <img src="https://img.shields.io/badge/LangGraph-272822?style=flat-square&logo=langchain&logoColor=A6E22E" alt="LangGraph" />
  <img src="https://img.shields.io/badge/GitHub_Actions-272822?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions" />
</p>

---

### `04` — Scribly

<a href="https://github.com/sumit-0804/Scribly">
  <h3><b>Real-Time Collaborative Editor</b></h3>
</a>

```mermaid
flowchart LR
    UserA[User A] --> YjsA[Yjs Client]
    UserB[User B] --> YjsB[Yjs Client]
    
    YjsA <-->|WebSocket| Sync((CRDT Sync / AWS Infrastructure))
    YjsB <-->|WebSocket| Sync

    classDef monokaiGreen fill:#272822,stroke:#A6E22E,color:#A6E22E;
    classDef monokaiCyan fill:#272822,stroke:#66D9EF,color:#66D9EF;
    classDef monokaiPink fill:#272822,stroke:#F92672,color:#F92672;

    class UserA,UserB monokaiGreen;
    class YjsA,YjsB monokaiCyan;
    class Sync monokaiPink;
```

Built around **Yjs CRDTs** for conflict-free collaboration with live presence tracking, version history, offline editing, role-based sharing, and cloud scalability powered by AWS.

<p align="left">
  <img src="https://img.shields.io/badge/TypeScript-272822?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Next.js-272822?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/AWS-272822?style=flat-square&logo=amazonwebservices&logoColor=FF9900" alt="AWS" />
  <img src="https://img.shields.io/badge/Bun-272822?style=flat-square&logo=bun&logoColor=FBF0DF" alt="Bun" />
  <img src="https://img.shields.io/badge/PostgreSQL-272822?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
</p>

---

### `05` — Campus Vault

<a href="https://github.com/sumit-0804/campus-vault">
  <h3><b>University Marketplace + Lost & Found</b></h3>
</a>

A campus-focused platform combining marketplace functionality, real-time messaging, and AI-powered content protection.

* **Real-Time Communication:** Instant messaging via Pusher with offer negotiation logic.
* **Safety First:** Automated PII detection and trust/karma calculation on user interactions.
* **AI Visual Search:** Multi-modal image tagging for precise inventory and lost item indexing.

<p align="left">
  <img src="https://img.shields.io/badge/Next.js-272822?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Prisma-272822?style=flat-square&logo=prisma&logoColor=2D3748" alt="Prisma" />
  <img src="https://img.shields.io/badge/Pusher-272822?style=flat-square&logo=pusher&logoColor=30B22C" alt="Pusher" />
  <img src="https://img.shields.io/badge/Gemini-272822?style=flat-square&logo=google-gemini&logoColor=8E75B2" alt="Gemini" />
</p>

---

## `GET /stack`

### `01 // LANGUAGES`
<p align="left">
  <img src="https://img.shields.io/badge/Python-272822?style=for-the-badge&logo=python&logoColor=A6E22E" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-272822?style=for-the-badge&logo=typescript&logoColor=66D9EF" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-272822?style=for-the-badge&logo=javascript&logoColor=E6DB74" alt="JavaScript" />
</p>

### `02 // FRONTEND`
<p align="left">
  <img src="https://img.shields.io/badge/React-272822?style=for-the-badge&logo=react&logoColor=66D9EF" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-272822?style=for-the-badge&logo=nextdotjs&logoColor=F8F8F2" alt="Next.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-272822?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Vite-272822?style=for-the-badge&logo=vite&logoColor=AE81FF" alt="Vite" />
</p>

### `03 // BACKEND`
<p align="left">
  <img src="https://img.shields.io/badge/FastAPI-272822?style=for-the-badge&logo=fastapi&logoColor=A6E22E" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Node.js-272822?style=for-the-badge&logo=nodedotjs&logoColor=A6E22E" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-272822?style=for-the-badge&logo=express&logoColor=F8F8F2" alt="Express" />
  <img src="https://img.shields.io/badge/Bun-272822?style=for-the-badge&logo=bun&logoColor=E6DB74" alt="Bun" />
</p>

### `04 // DATA & STORAGE`
<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-272822?style=for-the-badge&logo=postgresql&logoColor=66D9EF" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-272822?style=for-the-badge&logo=mongodb&logoColor=A6E22E" alt="MongoDB" />
  <img src="https://img.shields.io/badge/DuckDB-272822?style=for-the-badge&logo=duckdb&logoColor=E6DB74" alt="DuckDB" />
  <img src="https://img.shields.io/badge/Prisma-272822?style=for-the-badge&logo=prisma&logoColor=F8F8F2" alt="Prisma" />
</p>

### `05 // AI & LLM ARCHITECTURES`
<p align="left">
  <img src="https://img.shields.io/badge/LangGraph-272822?style=for-the-badge&logo=langchain&logoColor=A6E22E" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Google_Gemini-272822?style=for-the-badge&logo=google-gemini&logoColor=AE81FF" alt="Gemini" />
  <img src="https://img.shields.io/badge/RAG_Architectures-272822?style=for-the-badge&logo=openai&logoColor=FD971F" alt="RAG" />
</p>

### `06 // REAL-TIME & COLLABORATION`
<p align="left">
  <img src="https://img.shields.io/badge/WebSockets-272822?style=for-the-badge&logo=socketdotio&logoColor=F8F8F2" alt="WebSockets" />
  <img src="https://img.shields.io/badge/Yjs_CRDTs-272822?style=for-the-badge&logo=yaml&logoColor=F92672" alt="Yjs CRDTs" />
  <img src="https://img.shields.io/badge/Pusher-272822?style=for-the-badge&logo=pusher&logoColor=F92672" alt="Pusher" />
</p>

### `07 // INFRASTRUCTURE & DEVOPS`
<p align="left">
  <img src="https://img.shields.io/badge/AWS-272822?style=for-the-badge&logo=amazonwebservices&logoColor=FD971F" alt="AWS" />
  <img src="https://img.shields.io/badge/Google_Cloud-272822?style=for-the-badge&logo=googlecloud&logoColor=66D9EF" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/Docker-272822?style=for-the-badge&logo=docker&logoColor=66D9EF" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-272822?style=for-the-badge&logo=githubactions&logoColor=66D9EF" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Linux-272822?style=for-the-badge&logo=linux&logoColor=E6DB74" alt="Linux" />
</p>

---

## `GET /github`

<p align="center">
  <img
    height="170"
    src="https://github-readme-stats-fast.vercel.app/api?username=sumit-0804&show_icons=true&hide_border=true&theme=monokai&bg_color=272822&title_color=A6E22E&icon_color=66D9EF&text_color=F8F8F2&count_private=true"
    alt="GitHub statistics"
  />
  <img
    height="170"
    src="https://streak-stats.demolab.com?user=sumit-0804&theme=monokai&hide_border=true&background=272822&ring=A6E22E&fire=66D9EF&currStreakLabel=A6E22E"
    alt="GitHub streak"
  />
  <img
    height="170"
    src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=sumit-0804&layout=compact&langs_count=8&hide_border=true&theme=monokai&bg_color=272822&title_color=A6E22E&text_color=F8F8F2"
    alt="Top languages"
  />
</p>

---

## `GET /connect`

```json
{
  "open_to": [
    "Software Engineering Internships",
    "AI Engineering Roles",
    "Open Source",
    "Interesting Collaborations"
  ],
  "contact": {
    "github": "sumit-0804",
    "email": "sumitg2004@gmail.com",
    "linkedin": "https://www.linkedin.com/in/sumit--goyal/"
  },
  "availability": true
}
```

<br/>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=3500&pause=1400&color=66D9EF&center=true&vCenter=true&width=650&lines=%3E+request+completed+%E2%80%94+200+OK;%3E+system.ready();%3E+see+you+in+the+next+commit+%F0%9F%91%8B"
    alt="System ready"
  />
</p>

<p align="center">
  <sub>Built with curiosity. Shipped with code.</sub>
</p>