<!-- Shubhang S — GitHub profile README · Tokyo Night -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:414868,100:7aa2f7&height=190&section=header&text=Shubhang%20S&fontSize=56&fontColor=c0caf5&animation=fadeIn&fontAlignY=36&desc=Backend%20%E2%80%A2%20Systems%20%E2%80%A2%20AI%20Infra&descSize=18&descAlignY=58&descColor=7aa2f7" alt="Shubhang S"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=1000&color=7AA2F7&center=true&vCenter=true&width=700&lines=Backend+%26+Systems+Engineer;Low-latency+Go+services;Streaming+RAG+%26+vector+search;Co-founder+%40+Devsper" alt="Typing intro"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ServerCrash358&label=Profile%20Views&color=7aa2f7&style=for-the-badge" alt="Profile views"/>
  &nbsp;
  <a href="https://github.com/ServerCrash358?tab=followers">
    <img src="https://img.shields.io/github/followers/ServerCrash358?label=Followers&style=for-the-badge&color=7aa2f7&logo=github&logoColor=white&labelColor=1a1b27" alt="Followers"/>
  </a>
</p>

## About

Final-year CSE student at PES University, Bengaluru, and co-founding engineer at **Devsper**, an AI automation platform for software consultancies. I like systems that stay predictable under load and fail in ways you can see.

## What I've been building

- **[rtb-engine](https://github.com/ServerCrash358/rtb-engine)**: Go auction core. Parallel gRPC fan-out to bidders under a hard latency budget, load shedding and partial results. Load-tested with k6 against mock bidders (about 1,850 req/s on one dev box).
- **[Lumina-RAG](https://github.com/ServerCrash358/Lumina-RAG)**: async RAG API with pgvector HNSW, cross-encoder reranking, Redis cache, Kubernetes/ArgoCD deployment, and an automated eval pipeline.
- **[FreshDex](https://github.com/ServerCrash358/Freshdex)**: streaming RAG that keeps the vector index in sync with Postgres through CDC (Debezium → Redpanda → embedding worker).
- **[Mnemosyne](https://github.com/ServerCrash358/Mnemosyne)**: reference implementation of a deterministic record/replay and consensus layer for multi-agent LLM runs, with a hash-chained ledger.
- **StockLedger**: FastAPI/Postgres inventory service with row-level locking and idempotent sagas. 1,000 concurrent purchases against 100 units gave exactly 100 successes.
- **Lattice**: designing a C++ vector database (disk-resident Vamana-style graph index). Design stage, not built yet.
- **RISC-V / FPGA**: PicoRV32-based SoC with a KNN core on an Artix-7, plus a UART bootloader in assembly.

## Tech

<div align="center">

<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Verilog-RISC--V-283272?style=flat-square&logo=riscv&logoColor=white"/>
<br/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/gRPC-2D8CFF?style=flat-square&logo=grpc&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Kafka%20%2F%20Redpanda-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white"/>
<img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
<img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white"/>

</div>

## GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=ServerCrash358&theme=tokyonight&hide_border=true&background=1a1b27" alt="GitHub streak"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ServerCrash358&theme=tokyo-night&hide_border=true&bg_color=1a1b27&area=true" alt="Contribution activity"/>
</p>

## Current focus

| Area | What I'm working on |
|------|---------------------|
| **Low-latency services** | Go concurrency, deadlines, load shedding, load testing |
| **Retrieval & vector search** | HNSW/Vamana indexes, reranking, CDC-driven freshness |
| **Reliable agent systems** | Deterministic replay, consensus, auditable logs |
| **Hardware** | RISC-V soft cores and FPGA accelerators |

## Connect

<p align="center">
  <a href="https://github.com/ServerCrash358">
    <img src="https://img.shields.io/badge/GitHub-ServerCrash358-1a1b27?style=for-the-badge&logo=github&logoColor=7aa2f7" alt="GitHub"/>
  </a>
  <!-- Add yours, then uncomment:
  <a href="https://www.linkedin.com/in/YOUR-HANDLE">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-1a1b27?style=for-the-badge&logo=linkedin&logoColor=7aa2f7" alt="LinkedIn"/>
  </a>
  -->
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:414868,100:1a1b27&height=120&section=footer" alt=""/>
</p>
