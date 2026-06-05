# Hi, I'm Paul Cleenewerck 👋

**Solutions Architect — MongoDB Atlas · real-time data · applied AI & search**

![MongoDB Atlas](https://img.shields.io/badge/MongoDB_Atlas-00ED64?style=flat-square&logo=mongodb&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

I design and build production-oriented systems on MongoDB Atlas: real-time fraud detection, CDC streaming pipelines, vector/semantic search, RAG, and full-stack data applications. The repositories below are **sanitized public versions of real-world prototypes** — client names, credentials, and internal infrastructure have been removed, and every project is environment-driven (`.env.example`).

### 👀 Start here

Short on time? These three show the most depth:

1. **[realtime-fraud-detection-atlas](https://github.com/pcleene/realtime-fraud-detection-atlas)** — sub-50ms scoring; the clearest "Atlas replaces Redis + Oracle" story.
2. **[retail-customer-360-demo](https://github.com/pcleene/retail-customer-360-demo)** — one cluster running Search + Vector + Streams + agent memory end-to-end.
3. **[semantic-vector-router](https://github.com/pcleene/semantic-vector-router)** — a full async Python SDK; the deepest single codebase here.

---

## 🚀 Featured work

### ⚡ Real-time & streaming
| Project | What it demonstrates | Highlights |
|---------|----------------------|-----------|
| [realtime-fraud-detection-atlas](https://github.com/pcleene/realtime-fraud-detection-atlas) | Sub-50ms transaction scoring; Atlas as a replacement for Redis + Oracle | **<50ms · ~26K TPS · 50M customers** |
| [fuel-retail-tfw-platform](https://github.com/pcleene/fuel-retail-tfw-platform) | Fraud + analytics chatbot + name screening on one Atlas data model | ASP · Change Streams · LangGraph · MCP |
| [streaming-billing-intelligence-demo](https://github.com/pcleene/streaming-billing-intelligence-demo) | MSK → Atlas Stream Processing → Atlas billing pipeline | Kafka · ASP · full-stack |
| [crm-msk-cdc-infrastructure](https://github.com/pcleene/crm-msk-cdc-infrastructure) | Debezium CDC from a relational CRM into a sharded Atlas collection | **1.47M docs sharded** · Atlas Search |

### 🔎 Search, vector & applied AI
| Project | What it demonstrates | Highlights |
|---------|----------------------|-----------|
| [semantic-vector-router](https://github.com/pcleene/semantic-vector-router) | *(experimental)* Python SDK that partitions & routes Atlas Vector Search at scale | SDK design · lifecycle · zero-downtime repartition |
| [banking-rag-atlas-vs-aurora](https://github.com/pcleene/banking-rag-atlas-vs-aurora) | Honest side-by-side RAG benchmark: Atlas vs. Aurora + OpenSearch | nested vs. flat metadata · hybrid search |
| [pension-fund-officer-dashboard](https://github.com/pcleene/pension-fund-officer-dashboard) | Dual-mode text + vector search at national-pension-fund scale | **10M members · 650K employers** |
| [negative-list-search-platform](https://github.com/pcleene/negative-list-search-platform) | Sanctions/name screening — search + vectors on a single collection | fuzzy matching · X.509 auth |

### 🧱 Full-stack data platforms
| Project | What it demonstrates | Highlights |
|---------|----------------------|-----------|
| [retail-customer-360-demo](https://github.com/pcleene/retail-customer-360-demo) | One Atlas cluster powering an entire Customer-360 + AI stack | Search · Vector · Streams · agent memory |
| [utility-mobile-atlas-demo](https://github.com/pcleene/utility-mobile-atlas-demo) | Sharding, time series, geospatial, and auto-embedding in one app | breadth of Atlas features |
| [manufacturing-mes-dashboard](https://github.com/pcleene/manufacturing-mes-dashboard) | Time-series telemetry, quality views, ML anomaly detection | manufacturing · anomaly detection |
| [industrial-stream-health-demo](https://github.com/pcleene/industrial-stream-health-demo) | Equipment-health telemetry streamed through MSK + ASP | IoT · stream processing |

> More projects (Atlas Search pagination patterns, dealer portal, CDC reference guide) are on my [repositories](https://github.com/pcleene?tab=repositories) tab.

---

## 🧰 Tech I work with

**Data platform:** MongoDB Atlas — Atlas Search · Vector Search · Stream Processing · Time Series · Sharding · Change Streams
**Backend:** Python · FastAPI · async PyMongo
**Frontend:** SvelteKit · TypeScript · Tailwind
**Streaming & CDC:** Apache Kafka · Amazon MSK · Debezium
**AI / retrieval:** LangGraph · LangChain · Voyage AI · OpenAI · Cohere · MongoDB MCP Server
**Cloud:** AWS (MSK, Aurora, OpenSearch, EC2, PrivateLink)

---

## 📌 About these repositories

Every public repo here is an **anonymized portfolio version** of real work. Client identities, credentials, and internal endpoints have been removed; configuration is environment-driven. Projects marked *experimental* are research prototypes whose APIs may change.

## 📫 Reach me

- GitHub: [@pcleene](https://github.com/pcleene)
- LinkedIn: _add your profile URL here_ <!-- e.g. https://www.linkedin.com/in/your-handle -->
