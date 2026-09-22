# ML Systems Engineering

Putting ML models behind production-grade infrastructure — Spring Boot, Kafka, Elasticsearch — the same stack I've used to ship systems processing millions of daily transactions, now applied to ML serving, streaming feature pipelines, and search/retrieval.

Most ML portfolios stop at the notebook. This one doesn't — every project here is a real, deployable service, not a model that only runs in Jupyter.

---

## Planned projects (in build order)

- [ ] **Anomaly-detection service (Project A)** — A statistical/DL anomaly detector (generalized from production pipeline-monitoring work) trained on a public time-series dataset (Numenta Anomaly Benchmark or similar), wrapped in a Spring Boot REST API with proper versioning, health checks, and OpenAPI/Swagger docs.
- [ ] **Real-time feature pipeline (Project B)** — Kafka producer/consumer pipeline streaming events, computing features in real time, feeding a model for online inference.
- [ ] **Semantic search service (Project C)** — Elasticsearch-backed search combining keyword and embedding-based semantic retrieval over a document set, exposed via Spring Boot.
- [ ] **End-to-end MLOps deployment (Project D)** — CI/CD (GitHub Actions), Docker containerization, cloud deployment, and basic monitoring for one of the above services — the full path from trained model to running, observable production service.

## Why this repo exists

Applied/Research Scientist roles at companies like Google and Amazon aren't pure research positions — they require shipping models into real systems: serving infrastructure, monitoring, scaling, and integration with existing data pipelines. This repo demonstrates that end of the work explicitly, using the same tools (Spring Boot, Kafka, Elasticsearch, PostgreSQL) I've used in 15 years of production engineering.

## Stack

Java, Spring Boot/WebFlux, Kafka, Elasticsearch, Docker, GitHub Actions, PostgreSQL

## Status

🚧 Early build phase — first project (anomaly-detection service) in progress.

---

*Part of a three-lane portfolio — see [ml-dl-research](https://github.com/awaneeshtiwari1988/ml-dl-research) for research-style DL/NLP/RL work, and [quantum-ml](https://github.com/awaneeshtiwari1988/quantum-ml) for quantum machine learning.*
