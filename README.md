# Jishnu Prasad

+91 98447 78936 | [thisisjishnuprasad888@gmail.com](mailto:thisisjishnuprasad888@gmail.com) | [linkedin.com/in/jishnu-prasad-ba90a9328](https://linkedin.com/in/jishnu-prasad-ba90a9328) | [github.com/Jishnu-Prasad888](https://github.com/Jishnu-Prasad888) | [jishnu-prasad.vercel.app](https://jishnu-prasad.vercel.app)

---

## Education

**National Institute of Technology Karnataka** — *Surathkal, India*
B.Tech in Electrical and Electronics Engineering, CGPA: **7.18/10**
*Sep. 2024 – Present*

---

## Experience

**SPIRE (Signal Processing, Interpretation and REpresentation) Lab** — *IISC*
Research Intern | *RAG, Python, React, Agentic AI*
*May 2026 – July 2026*

- Built a **multilingual (English & Kannada) multimodal RAG system** for SBI banking forms and documentation, integrating **OCR**, automated web scraping, document ingestion, embedding generation, and **Elasticsearch-based indexing** to enable hybrid vector and keyword search with metadata filtering for accurate and contextually relevant retrieval across digital and scanned documents.
- Architected a **multi-agent retrieval framework** with specialized agents for PDF, Markdown, Excel, and HTML documents, dynamically routing queries to the most relevant knowledge source for improved retrieval accuracy and contextual grounding.
- Designed and implemented a **Knowledge-Augmented Generation (KAG)** architecture to overcome limitations of traditional RAG on complex banking queries, enhancing multi-hop reasoning, contextual understanding, and answer completeness.
- Fine-tuned a **Qwen3-8B-Instruct** model on a custom evaluation dataset to act as an answer-quality critic, scoring responses on *Accuracy*, *Answer Relevancy*, and *Faithfulness* and enabling a **DeepThink feedback loop** that triggered iterative retrieval-generation cycles; benchmarked RAG, Multi-Agent RAG, GPT-4o, and KAG using an **LLM-as-a-Judge** evaluation framework.

**HALE (Healthcare Analytics and Language Engineering) Lab** — *NITK*
Research Intern | *Kubernetes, Redis, LangChain, RAG, Ansible*
*Jan 2026 – Present*

- Engineered a **multi-node Raspberry Pi k3s cluster** with **MetalLB** and **NGINX Ingress**, enabling load-balanced, TLS-secured service delivery.
- Built a full observability stack using **Prometheus**, **Grafana**, **Loki**, and **Promtail** for centralized monitoring and log aggregation.
- Deployed distributed **MinIO** storage, Flask/React applications, and **JupyterHub**, addressing multi-node storage, image distribution, and service discovery challenges.
- Automated provisioning and orchestration with **Ansible** to support reproducible edge inference workloads on a **Raspberry Pi 5** Kubernetes cluster.

**Urban Records** — *Remote*
Freelance Full-Stack Engineer | *Django REST Framework, React, TailwindCSS, Docker, PostgreSQL*
*Sep. 2025 – Nov. 2025*

- Architected and developed a **containerized full-stack document management platform** for tax, passport, and visa processing workflows using Django REST Framework, React, PostgreSQL, and Docker.
- Optimized document processing pipelines to **reduce manual intervention from days to just hours**.
- Deployed a production-grade system supporting **500+ active users** with high reliability.

**SENA NGO** — *Surathkal, India*
Backend Engineering Intern | *Python, Django, SQL, Docker*
*May 2025 – Jul. 2025*

- Developed and integrated a secure **donations pipeline** using the **Cashfree Python SDK**, enabling reliable online payment processing and transaction tracking.
- Built form-driven publishing workflows allowing non-technical contributors to create and publish content without developer intervention, reducing operational dependency on the engineering team.

---

## Projects

**Memora — Redis-like In-Memory Database** | *Go, Python, TCP, Concurrent Systems*
[github.com/Jishnu-Prasad888/Memora](https://github.com/Jishnu-Prasad888/Memora)

- Engineered a **Redis-compatible in-memory key-value database** in Go with full **RESP protocol** support and concurrent TCP client handling.
- Implemented custom **hash-table storage**, **TTL expiration**, background cleanup, and **RDB-style snapshot persistence** for durable in-memory data management.
- Built **CLI** and **Python GUI** clients for database administration, monitoring, and interactive command execution.
- Achieved **226K+ operations/sec** with **1M benchmarked operations**, **39µs P50 latency**, and **2.0ms P99 latency** under concurrent workloads.
- Designed **goroutine-based request processing** and non-blocking I/O architecture to support scalable multi-client access.

**ATLAS & Beacon — Distributed Fleet Management and Observability Platform** | *ReactJS, Django, NATS JetStream, RAG, GraphQL, Aurora PostgreSQL, Redis, Docker, Cloudflare, Vercel*
[github.com/Jishnu-Prasad888/ATLAS](https://github.com/Jishnu-Prasad888/ATLAS)

- Engineered and deployed distributed control-plane architecture comprising centralized **ATLAS** services and lightweight **Beacon** agents, enabling **scalable fleet orchestration** and **remote operations**.
- Built a high-throughput observability pipeline collecting **CPU, memory, disk, network, process, Docker, and Kubernetes telemetry**, storing historical metrics in **Aurora PostgreSQL** and **Redis**, with real-time aggregation, log indexing, and **WebSocket-based streaming dashboards**.
- Implemented fault-tolerant agent communication over **NATS JetStream** using **durable consumers**, **message replay**, **offline buffering**, **dead-letter queues**, and **mTLS**-based authentication for reliable distributed messaging.
- Developed a multi-tenant operations platform featuring **RBAC**, **immutable audit logging**, **fleet-wide diagnostics**, **process and container lifecycle management**, **AI-assisted log/telemetry analysis**, and containerized deployment via **Docker**, **Cloudflare Tunnel**, **Nginx**, and **Vercel**.

**RescueMind** | *FastAPI, Go, gRPC, RAG, Redis, WebSockets*
*IET NITK Project Expo 2026* · [github.com/Jishnu-Prasad888/RescueMind](https://github.com/Jishnu-Prasad888/RescueMind)

- Built an **AI-powered disaster intelligence platform** for real-time satellite and aerial imagery analysis using **CNN-generated grid heatmaps** across **5 disaster categories**.
- Engineered a distributed backend using FastAPI, Go, gRPC, Redis, and WebSockets to process live RSS feeds and **AIS ship-tracking streams** with end-to-end response latencies of **~50–200 ms**.
- Designed **low-latency event-driven system architecture** supporting concurrent multimodal data ingestion, inference, and real-time dashboard updates.
- Built an **autonomous rover prototype** using **YOLO-based vision** and sensor fusion with a hardware safety override.

**PacketLens** | *C++, Qt6, Python, Linux Networking, MCP (Model Context Protocol)*
[github.com/Jishnu-Prasad888/PacketLens](https://github.com/Jishnu-Prasad888/PacketLens)

- Built a **real-time network monitoring tool** with packet capture, flow aggregation, and process-level attribution on Linux.
- Designed a **dual-interface system** with flow tables and interactive graphs for network visualization.
- Highlighted high-bandwidth processes using node scaling and protocol-based color coding.
- Mapped live network connections to originating processes for system-level visibility into traffic behavior.
- Exposed a lightweight **HTTP API** and **MCP integration** for natural-language querying of network activity.

**Browser-RAG — Local Browser History Retrieval-Augmented Generation** | *Python, FastAPI, React, TypeScript, ChromaDB, Ollama, LLaMA 3.2*
[github.com/Jishnu-Prasad888/Browser-RAG](https://github.com/Jishnu-Prasad888/Browser-RAG)

- Built a **local-first RAG system** that extracts and processes browser history from Chrome, Firefox, and Edge across Windows and Linux.
- Designed a content pipeline to download, chunk, and embed visited web pages into **ChromaDB** for efficient semantic retrieval.
- Implemented a **FastAPI** backend with **Ollama**-powered **LLaMA 3.2** for context-aware question answering over personal browsing data.
- Developed a **React + TypeScript** chat interface with conversation history, markdown rendering, and responsive UI.
- Integrated smart filtering, deduplication, and domain blocking to optimize storage and retrieval quality.

---

## Technical Skills

- **Languages:** Python, C++, Go, JavaScript/TypeScript · *Familiar:* Java, Bash, GraphQL, MATLAB, R
- **Frameworks:** FastAPI, Django, React, Next.js
- **ML & CV:** LangChain, MCP (Model Context Protocol), ADK (Agent Development Kit), PyTorch, TensorFlow, OpenCV
- **Tools:** Linux, Docker, Kubernetes, PostgreSQL, Redis, Git

---

## Leadership & Activities

**Top 10 — Caterpillar Autonomy Challenge** — *IIT Madras*
Team Member, *NITK CATERBOTS*

- Designed and built an **autonomous Mars-terrain rover** capable of crater detection, sand berm construction, and **NLOS navigation** out of **1,922 competing teams**.

**IET NITK Student Chapter** — *NITK Surathkal*
Project Lead — RescueMind & *Web Team Member*

- Led a team building **RescueMind**, a disaster response system with routing, CNN-based classification, and RAG-based advisories.

**Amateur Astronomy Club (AAC) & SMILE Club** — *NITK Surathkal*
Chief Technical Coordinator in AAC and *Events & Publicity Coordinator* in SMILE

- Co-led **Arduino-based astronomy projects** including stellar mass estimation and **ML-based multi-camera video stitching**.
- Organized technical events, secured sponsorships, and managed sub-teams for structured event delivery.