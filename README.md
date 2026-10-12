# Awesome-Real-Time-Personalization-Engine
# Awesome-Real-Time-Personalization-Engine

# Top Real-Time Personalization Engine Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Behavioral Targeting, Adaptive Experiences & Continuous Optimization*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Real-Time Personalization Engines**. These tools analyze user behavior, context, and preferences to deliver individualized experiences — product recommendations, dynamic content, adaptive layouts, and next-best-action suggestions — across web, mobile, email, and other channels.

**Examples** include Salesforce Marketing Cloud Personalization, Dynamic Yield, Bloomreach Personalization, Monetate, Algolia Recommend, Insider, Nosto, Adobe Target, Optimizely Personalization, and Frosmo (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom recommendation models, and transparent personalization logic — ideal for growth engineers, data scientists, and developers building data-sovereign personalization platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Marketing Cloud Personalization](https://www.salesforce.com/)**  
  Enterprise personalization platform with real-time behavioral targeting, AI-powered recommendations, and cross-channel orchestration.

- **[Dynamic Yield](https://www.dynamicyield.com/)**  
  Personalization and experimentation platform for e-commerce and content sites with automated optimization and A/B testing.

- **[Bloomreach Personalization](https://www.bloomreach.com/)**  
  AI-driven personalization for commerce with product recommendations, search, and content optimization.

- **[Monetate](https://www.monetate.com/)**  
  Personalization platform with real-time decisioning, testing, and behavioral targeting for digital experiences.

- **[Algolia Recommend](https://www.algolia.com/)**  
  AI-powered recommendation API with related products, frequently bought together, and trending items based on user behavior.

- **[Insider](https://useinsider.com/)**  
  AI-powered personalization and customer engagement platform with predictive segments and individual-level experiences.

- **[Nosto](https://www.nosto.com/)**  
  E-commerce personalization platform with AI recommendations, behavioral targeting, and onsite content personalization.

- **[Adobe Target](https://business.adobe.com/products/target/adobe-target.html)**  
  Enterprise personalization and experimentation engine with AI-driven auto-targeting and automated personalization.

- **[Optimizely Personalization](https://www.optimizely.com/)**  
  Digital experience platform with personalization, experimentation, and feature flagging capabilities.

- **[Frosmo](https://www.frosmo.com/)**  
  Personalization and optimization platform for e-commerce and media with real-time behavioral targeting.

## Open-Source GitHub Projects

- **[Gorse](https://github.com/gorse-io/gorse)**  
  AI-powered open-source recommender system engine written in Go. Automatically trains models from user-item interaction data to generate personalized recommendations. Features multi-source recommendations (latest, user-to-user, item-to-item, collaborative filtering), multimodal embedding support, GUI dashboard, and RESTful APIs. Apache 2.0 licensed, 9,700+ GitHub stars .

- **[Metarank](https://github.com/metarank/metarank)**  
  Open-source low-code machine learning personalized ranking service for articles, listings, search results, and recommendations. Integrates customer signals (clicks, purchases) into ranking to optimize CTR, tracks visitor profiles for real-time personalization, and supports LLMs for semantic search. Optimized for 10-20ms reranking latency with horizontal scaling via Redis .

- **[EdgePersona](https://github.com/Crynge/EdgePersona)**  
  Python real-time cross-channel personalization engine and edge CDP. Unifies customer identities with deterministic + DBSCAN resolution, builds audience segments with AST-based rule engine, personalizes via multi-armed bandits (Thompson Sampling + UCB1), and runs A/B tests with Bayesian statistics. Redis-backed profile store with <5ms read latency .

- **[GrowthBook](https://github.com/growthbook/growthbook)**  
  Open-source feature flagging and A/B testing platform with advanced targeting, gradual rollouts, and a world-class experiment stats engine (CUPED, Sequential, Bayesian, Bandits). Includes built-in product analytics, warehouse-native queries (BigQuery, Snowflake, Databricks), and MCP server. MIT licensed with enterprise modules available .

- **[Experimently](https://github.com/getexperimently/experimently)**  
  Open-source experimentation platform with A/B testing, feature flags, sequential and Bayesian statistics, and 15 SDKs. Features append-only audit log, role-based access, per-flag safety monitoring with automatic rollback, and compliance modules. Apache-2.0 licensed .

- **[Bucketeer](https://github.com/bucketeer-io/bucketeer)**  
  Enterprise-grade feature management and experimentation platform. No usage limits, deploy anywhere (on-premise, cloud, hybrid), low latency, and all enterprise features included. Apache 2.0 licensed, battle-tested at CyberAgent .

- **[ReflexUI](https://github.com/mmarqueti/reflexui)**  
  Adaptive, explainable screens driven by fast typed-judgment models. A System One model decides what's relevant; your code decides what's allowed. Features headless React hooks, offline replay for hit rate vs default order, and Redis-backed decision store for production .

- **[Too](https://github.com/hjr265/too)**  
  Simple recommendation engine implementation built on top of Redis. Lightweight Go-based solution for basic personalization needs .

### Additional Strong Open-Source Options

- **[Apache Mahout](https://github.com/apache/mahout)** — Scalable machine learning and recommendation library for Java .
- **[python-recsys](https://github.com/ocelma/python-recsys)** — Python library for implementing recommender systems .
- **[Deep Recommender System](https://github.com/chocoluffy/deep-recommender-system)** — Deep learning approaches including BERT4Rec, contrastive learning, and multi-interest networks .
- **Collaborative Filtering Libraries** — Implicit, LightFM, and Surprise for classical recommendation models .
- **Vector Databases** — Qdrant, Weaviate, Milvus, Chroma for semantic recommendation retrieval.
- **Feature Stores** — Feast, Tecton for serving real-time ML features to personalization models.

**Frameworks for building custom systems**: Combine **Gorse** for recommendation serving, **Metarank** for learning-to-rank reranking, **GrowthBook** for experimentation, **EdgePersona** for real-time segment evaluation, and **Redis + PostgreSQL** for low-latency profile storage to build a complete self-hosted personalization stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Real-time personalization engines must comply with data protection regulations (GDPR, CCPA), consent requirements, and ethical AI guidelines .
- Self-hosted open-source solutions require proper security hardening, model monitoring, and infrastructure management.

---

**Made for growth engineers, personalization managers, data scientists, and developers building real-time personalization platforms.**  
Let's make real-time personalization more open, privacy-conscious, and developer-friendly.
