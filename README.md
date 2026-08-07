<!-- ========================================== -->
<!--             HERO HEADER SECTION            -->
<!-- ========================================== -->

<div align="center">
  <!-- Typing Banner SVG -->
  <a href="https://github.com/alexrivera-dev">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=7AA2F7&center=true&vcenter=true&width=700&lines=Hi+%F0%9F%90%8B+I'm+Alex+Rivera;Senior+Full-Stack+%26+Distributed+Systems+Engineer;Building+Fault-Tolerant+Cloud-Native+Architectures;Open-Source+Contributor+%26+Tech+Writer" alt="Typing Banner" />
  </a>

  <br />

  <!-- Professional Headline -->
  <p align="center">
    <b>Building resilient distributed systems, high-throughput microservices, and agentic AI platforms at scale.</b>
  </p>

  <!-- Visitor Counter & Quick Badges -->
  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=alexrivera-dev&label=PROFILE+VIEWS&color=7aa2f7&style=for-the-badge" alt="Visitor Counter" />
    <img src="https://img.shields.io/github/followers/alexrivera-dev?label=FOLLOWERS&style=for-the-badge&color=2ac3de&logo=github" alt="GitHub Followers" />
    <img src="https://img.shields.io/badge/LOCATION-SAN_FRANCISCO,_CA-7dcfff?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
    <img src="https://img.shields.io/badge/STATUS-OPEN_FOR_PROJECTS-green?style=for-the-badge" alt="Status" />
  </p>

  <!-- Social Media & Contact Links -->
  <p align="center">
    <a href="https://linkedin.com/in/alexrivera-dev">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:alex.rivera.eng@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://alexrivera.dev">
      <img src="https://img.shields.io/badge/Portfolio-7AA2F7?style=for-the-badge&logo=react&logoColor=white" alt="Portfolio" />
    </a>
    <a href="https://twitter.com/alexrivera_dev">
      <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="Twitter" />
    </a>
  </p>
</div>

---

<!-- ========================================== -->
<!--               ABOUT ME SECTION             -->
<!-- ========================================== -->

## 🚀 About Me

<table border="0" width="100%">
  <tr>
    <td width="60%" valign="top">
      <p>I am a <b>Senior Software Engineer</b> with 6+ years of experience architecting cloud-native solutions, event-driven microservices, and AI-assisted automation pipelines. Currently focused on building ultra-low-latency distributed platforms and contributing to high-impact open-source systems.</p>
      
      <ul>
        <li>🎓 <b>Education:</b> B.S. in Computer Science & Engineering — <i>Stanford University</i></li>
        <li>💡 <b>Engineering Philosophy:</b> "Simplicity precedes reliability; trade-offs dictate architecture."</li>
        <li>🎯 <b>Career Focus:</b> Fault-tolerant distributed systems, multi-agent RAG architectures, and web-scale performance engineering.</li>
        <li>🔍 <b>Current Focus:</b> Agentic workflows, eBPF network monitoring, and Rust-based edge runtime environments.</li>
      </ul>
    </td>
    <td width="40%" align="center" valign="middle">
      <img src="https://github-readme-stats.vercel.app/api/wakatime?username=alexrivera&layout=compact&theme=tokyonight&hide_border=true" alt="WakaTime Stats" width="100%" />
    </td>
  </tr>
</table>

---

<!-- ========================================== -->
<!--        COMPETITIVE PROGRAMMING            -->
<!-- ========================================== -->

## 🏆 Competitive Programming & Achievements

<div align="center">

| Platform | Rating / Global Rank | Solved Problems | Profile Link |
| :--- | :---: | :---: | :--- |
| **LeetCode** | Knight (2,184 Peak) | 950+ Hard/Medium | [<img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" height="22"/>](https://leetcode.com/alexrivera) |
| **Codeforces** | Candidate Master (1,920) | 600+ Division 1/2 | [<img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white" height="22"/>](https://codeforces.com/profile/alexrivera) |
| **HackerRank** | 6★ Problem Solving | 300+ Challenges | [<img src="https://img.shields.io/badge/HackerRank-00EA64?style=flat-square&logo=hackerrank&logoColor=black" height="22"/>](https://hackerrank.com/alexrivera) |

</div>

<br/>

> 🏅 **Key Achievements:**
> - **1st Place** — Global Cloud Native Hackathon 2025 (*Built an eBPF-based zero-trust network observability agent*).
> - **AWS Certified Solutions Architect – Professional** (*SAP-C02*).
> - Maintainer of 3 popular npm/crates repositories with **100k+ total downloads**.

---

<!-- ========================================== -->
<!--             FEATURED PROJECTS              -->
<!-- ========================================== -->

## 💼 Featured Projects

### ⚡ 1. PulseGrid — High-Throughput Event Streaming Engine

<table width="100%">
  <tr>
    <td>
      <p><b>Business Problem:</b> Legacy message brokers experienced 400ms+ tail latency spikes during peak load spikes (>100k req/sec).</p>
      <p><b>Solution Architecture:</b> Built a custom distributed pub/sub broker in Rust utilizing zero-copy I/O (`io_uring`), Raft consensus mechanism, and Apache Arrow in-memory processing.</p>
      <p><b>Tech Stack:</b> <code>Rust</code> • <code>Tokio</code> • <code>Raft</code> • <code>Docker</code> • <code>Prometheus</code> • <code>gRPC</code></p>
      <ul>
        <li><b>Performance:</b> Reduced p99 message distribution latency from 420ms to 4.2ms.</li>
        <li><b>Scalability:</b> Tested up to 500k concurrent WebSocket connections with zero message drop under network partition simulation.</li>
        <li><b>Security:</b> End-to-end mTLS authentication with automated secret rotation via HashiCorp Vault.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/alexrivera-dev/pulse-grid"><b>[ View Source Code ]</b></a>
      </p>
    </td>
  </tr>
</table>

### 🤖 2. OrchestraAI — Autonomous Multi-Agent Systems Framework

<table width="100%">
  <tr>
    <td>
      <p><b>Business Problem:</b> Monolithic LLM pipelines lacked dynamic tool execution, causing context overflow and execution failures on complex enterprise workflows.</p>
      <p><b>Solution Architecture:</b> Designed a DAG-based multi-agent orchestration platform integrating ChromaDB vector stores with asynchronous Python task workers.</p>
      <p><b>Tech Stack:</b> <code>Python</code> • <code>FastAPI</code> • <code>LangChain</code> • <code>ChromaDB</code> • <code>Redis</code> • <code>React</code></p>
      <ul>
        <li><b>Key Feature:</b> Dynamic context slicing with automated prompt compression reducing API token consumption by 38%.</li>
        <li><b>Production Ready:</b> Deployed on Kubernetes (EKS) with horizontal pod autoscaling based on queue depth.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/alexrivera-dev/orchestra-ai"><b>[ View Source Code ]</b></a>
      </p>
    </td>
  </tr>
</table>

---

<!-- ========================================== -->
<!--             ENGINEERING STACK              -->
<!-- ========================================== -->

## ⚡ Engineering Stack

<div align="center">

### 💻 Languages & Runtimes
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### ⚙️ Backend & Architecture
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=grpc&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

### 🎨 Frontend Systems
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)

### 🗄️ Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC00?style=for-the-badge&logo=clickhouse&logoColor=black)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)

### ☁️ Cloud, DevOps & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

---

<!-- ========================================== -->
<!--           ENGINEERING EXPERIENCE           -->
<!-- ========================================== -->

## 🏗️ Engineering Capabilities

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>⚡ Backend & Distributed Systems</h4>
      <ul>
        <li><b>Architectures:</b> CQRS, Event Sourcing, Saga Pattern, Microservices.</li>
        <li><b>Protocols:</b> RESTful APIs, gRPC, WebSockets, HTTP/3, WebRTC.</li>
        <li><b>Reliability:</b> Rate limiting, circuit breakers, distributed locking, idempotent APIs.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🤖 AI, Data & Security</h4>
      <ul>
        <li><b>AI Systems:</b> Agentic workflows, Multi-Agent Orchestration, RAG with Vector DBs.</li>
        <li><b>Data Pipeline:</b> Stream processing with Apache Kafka & Spark.</li>
        <li><b>Security:</b> OAuth2/OIDC, JWT, Zero-Trust Architecture, HashiCorp Vault.</li>
      </ul>
    </td>
  </tr>
</table>

---

<!-- ========================================== -->
<!--            GITHUB METRICS & CARDS          -->
<!-- ========================================== -->

## 📈 GitHub Metrics

<div align="center">
  <!-- GitHub Stats Card -->
  <img src="https://github-readme-stats.vercel.app/api?username=alexrivera-dev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" width="49%" />
  <!-- Top Languages Card -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=alexrivera-dev&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" width="49%" />
</div>

<br/>

<div align="center">
  <!-- Streak Stats Card -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=alexrivera-dev&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="98%" />
</div>

<br/>

<!-- GitHub Trophies -->
<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=alexrivera-dev&theme=tokyonight&no-bg=true&column=6&margin-w=15" alt="GitHub Trophies" />
</div>

<br/>

<!-- Contribution Snake Animation -->
<div align="center">
  <h3>🐍 Contribution Snake</h3>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/alexrivera-dev/alexrivera-dev/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/alexrivera-dev/alexrivera-dev/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/alexrivera-dev/alexrivera-dev/output/github-contribution-grid-snake.svg" width="100%">
  </picture>
</div>

---

<!-- ========================================== -->
<!--             CURRENTLY EXPLORING            -->
<!-- ========================================== -->

## 🌱 Currently Exploring

<div align="center">
  
| Domain | Focus Topic | Target Application |
| :--- | :--- | :--- |
| **Agentic AI Systems** | AutoGen & CrewAI Frameworks | Automated Code Auditing Agents |
| **Kernel Engineering** | eBPF & Linux Kernel Modules | High-Speed Microservice Observability |
| **Edge Computing** | WebAssembly (Wasm) Runtimes | Sub-millisecond Edge Function Execution |

</div>

---

<!-- ========================================== -->
<!--                 LET'S CONNECT              -->
<!-- ========================================== -->

## 🤝 Let's Connect

<div align="center">

<a href="https://linkedin.com/in/alexrivera-dev">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:alex.rivera.eng@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
</a>
<a href="https://twitter.com/alexrivera_dev">
  <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
</a>
<a href="https://alexrivera.dev">
  <img src="https://img.shields.io/badge/Website-7AA2F7?style=for-the-badge&logo=firefox&logoColor=white" alt="Website" />
</a>

</div>

---

<!-- ========================================== -->
<!--               SIGNATURE QUOTE              -->
<!-- ========================================== -->

<div align="center">
  <br/>
  <blockquote align="center">
    <i>"Premature optimization is the root of all evil. But neglecting scalability in core design is an architect's quiet bankruptcy."</i>
  </blockquote>
  <br/>
  
  <p align="center">
    <sub>Designed with 💙 using Tokyo Night Theme • Built for Engineers</sub>
  </p>
</div>
