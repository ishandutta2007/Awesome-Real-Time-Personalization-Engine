# Awesome Real-Time Personalization Engine ⚡🎯

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Real-Time-Personalization-Engine/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Real-Time-Personalization-Engine?style=flat-square&logo=github&color=gold" alt="GitHub Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Real-Time-Personalization-Engine/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Real-Time-Personalization-Engine?style=flat-square&logo=github&color=blue" alt="Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Real-Time-Personalization-Engine/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Real-Time-Personalization-Engine/pulls"><img src="https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"/></a>
</p>

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Real-Time Personalization Engine Banner" width="100%" />
</p>

---

## 🧭 Table of Contents
- [📖 Overview](#-overview)
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [🏢 SaaS & Hosted Personalization Platforms](#-saas--hosted-personalization-platforms)
- [💻 Open-Source Recommender & Personalization Engines](#-open-source-recommender--personalization-engines)
- [🏗️ Reference Modern Real-Time Stack Architecture](#️-reference-modern-real-time-stack-architecture)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 📖 Overview

The **Awesome Real-Time Personalization Engine** repository is a curated catalog of enterprise SaaS products and production-grade open-source tools powering real-time behavioral targeting, continuous machine learning optimization, and dynamic content experiences.

Personalization engines monitor instant stream events (clicks, dwell time, purchases, geo-context, search intent) to calculate sub-50ms predictions and adapt:
- 🛍️ **E-Commerce & Merchandising**: Dynamic product grids, 1-to-1 cross-sells, bundle recommendations, and localized promotions.
- 📰 **Media, Streaming & Publishing**: Adaptive feeds, article carousels, next-video auto-play, and personalized search re-ranking.
- 🎯 **Marketing Automation & Product Growth**: Dynamic on-site modals, contextual notifications, next-best-action (NBA) workflows, and contextual multi-armed bandits.

---

## 📊 Sector Overview & Market Dynamics

The global hyper-personalization and real-time customer personalization software sector represents an estimated **$18.7B to $21.7B market in 2025–2026**, on pace to exceed **$80B+ by the mid-2030s** at an 18%+ CAGR. 

The industry displays a **hybrid competitive structure**: it is **concentrated at the enterprise cloud core** (dominated by conglomerate titans like Salesforce, Adobe, and Mastercard/Dynamic Yield embedding cross-cloud CDPs), but **highly fragmented across the mid-market, e-commerce, and open-source infrastructure tiers**, where specialized vendors, low-latency API ranking engines, and vector-native decision systems innovate rapidly.

---

## 🏢 SaaS & Hosted Personalization Platforms

The following hosted platforms provide fully managed multi-channel real-time personalization, predictive AI scoring, and experimentation. Tiers are sorted in descending order by company valuation/market capitalization.

| Company / Product | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Free Trial Limits | Key Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Salesforce Marketing Cloud Personalization](https://www.salesforce.com/)** | **~$280B Market Cap** (~$35B ARR) | **~$8,000 / month** (billed annually as enterprise add-on) | **No free tier**; No self-service trial (Custom guided PoC demo available upon sales consultation) | Real-time omnichannel interaction management, Einstein AI behavioral recommendations, sub-second profile hydration across Data Cloud. |
| **[Adobe Target](https://business.adobe.com/products/target/adobe-target.html)** | **~$220B Market Cap** (~$21B ARR) | **~$3,300 / month** (~$40,000 / year billed annually) | **No free tier**; No self-service trial (Enterprise evaluation only via Adobe Experience Cloud sales team) | AI Auto-Target, automated multivariate experimentation, cross-channel rule decisioning integrated with Adobe Experience Platform. |
| **[Dynamic Yield](https://www.dynamicyield.com/)** *(by Mastercard)* | **~$440B Parent Cap** ($300M+ acquisition) | **~$2,900 / month** (~$35,000 / year base contract) | **No free tier**; No self-serve trial (Custom POC pilot available for qualified enterprise retailers) | Multi-armed bandit testing, deep-learning recommendation algorithms, real-time customer behavioral segmenting, and visual experience builder. |
| **[Optimizely Personalization](https://www.optimizely.com/)** | **~$1.2B Valuation** (~$400M ARR) | **~$3,000 / month** (~$36,000 / year billed annually) | **No free tier**; No open free trial (Guided sandbox evaluation available for qualified mid-market/enterprise teams) | Experimentation-first personalization, 1-to-1 content delivery, real-time visitor profiling, feature flag orchestration. |
| **[Algolia Recommend](https://www.algolia.com/)** | **~$2.25B Valuation** (~$200M ARR) | **$0 / month** (Pay-as-you-go starting tier; Grow tier adds $0.60 per 1,000 recommendations over quota) | **Free Forever Tier**: 5,000 recommendation requests/month + 10,000 search requests/month + 50,000 index records | High-throughput sub-10ms REST/GraphQL recommendation APIs, "Frequently Bought Together", "Related Items", and NeuralSearch embeddings. |
| **[Bloomreach Personalization](https://www.bloomreach.com/)** | **~$2.2B Valuation** (~$150M ARR) | **~$5,000 / month** (~$60,000 / year base platform tier) | **No free tier**; No self-service free trial (Discovery consultation & tailored proof-of-concept for qualified brands) | Commerce-specialized AI search, customer data engine (CDP), personalized merchandising grids, and automated 1-to-1 email/SMS triggers. |
| **[Insider](https://useinsider.com/)** | **~$2.0B Valuation** (~$150M ARR) | **~$4,800 / month** (base package for ~100k MTUs) | **No free tier**; No public self-service trial (Custom product walkthrough & 14-day assisted pilot for qualified enterprise accounts) | Cross-channel customer engagement, Sirius AI predictive behavior scoring, real-time messaging (Web, App, WhatsApp, RCS). |
| **[Nosto](https://www.nosto.com/)** | **~$300M Valuation** (~$40M ARR) | **~$500 / month** (modular entry pricing + variable GMV tier) | **No free tier**; Structured Proof of Concept (PoC) available with live store catalog synchronization via app store onboarding | Commerce experience platform, automated visual merchandising, user-generated content (UGC) personalization, and dynamic category sorting. |
| **[Monetate](https://www.monetate.com/)** | **~$100M Valuation** (~$35M ARR) | **~$2,500 / month** (~$30,000 / year custom contract) | **No free tier**; No self-service trial (Interactive demo & custom sandbox POC available on request) | Real-time decisioning engine, Symphony personalization suite, automated multi-page testing, behavioral audience segmentation. |
| **[Frosmo](https://www.frosmo.com/)** | **~$30M Valuation** (~$10M ARR) | **~$800 / month** (Quick Start platform package) | **30-Day Free Trial**: Full access to Quick Start AI recommendation strategies & A/B testing suite with no upfront credit card required | Fast client-side JavaScript personalization engine, contextual AI recommendations, targeted layout modifications, tailored for iGaming & e-commerce. |

---

## 💻 Open-Source Recommender & Personalization Engines

High-performance open-source libraries, microservices, and platforms for self-hosting custom recommendation pipelines, multi-armed bandits, and real-time re-ranking. Sorted in descending order by GitHub stars.

| Repository | GitHub Stars | Description & Architecture Highlights | Primary Stack |
| :--- | :--- | :--- | :--- |
| **[Milvus](https://github.com/milvus-io/milvus)** | [![Milvus Stars](https://img.shields.io/github/stars/milvus-io/milvus?style=social&color=white)](https://github.com/milvus-io/milvus/stargazers) | Cloud-native, distributed vector database engineered for billion-scale similarity search, powering modern semantic recommendation retrievals and real-time multimodal personalization. | Go, C++, Python |
| **[Qdrant](https://github.com/qdrant/qdrant)** | [![Qdrant Stars](https://img.shields.io/github/stars/qdrant/qdrant?style=social&color=white)](https://github.com/qdrant/qdrant/stargazers) | High-performance vector similarity search engine with extended payload filtering, ideal for real-time recommendation filtering by stock, category, and user attributes. | Rust |
| **[Chroma](https://github.com/chroma-core/chroma)** | [![Chroma Stars](https://img.shields.io/github/stars/chroma-core/chroma?style=social&color=white)](https://github.com/chroma-core/chroma/stargazers) | Open-source embedding database for AI native applications, powering lightweight semantic recommendation candidates and personalized retrieval. | Python, TypeScript |
| **[Microsoft Recommenders](https://github.com/recommenders-team/recommenders)** | [![Recommenders Stars](https://img.shields.io/github/stars/recommenders-team/recommenders?style=social&color=white)](https://github.com/recommenders-team/recommenders/stargazers) | Comprehensive production recipes and best practices for building recommender systems with state-of-the-art algorithms (SAR, LightGCN, VAE, NCF, DKN, BPR). | Python, PyTorch, TensorFlow |
| **[Weaviate](https://github.com/weaviate/weaviate)** | [![Weaviate Stars](https://img.shields.io/github/stars/weaviate/weaviate?style=social&color=white)](https://github.com/weaviate/weaviate/stargazers) | Open-source vector database that combines vector search with structured filtering and neural search modules for real-time recommendations. | Go, Python |
| **[Gorse](https://github.com/gorse-io/gorse)** | [![Gorse Stars](https://img.shields.io/github/stars/gorse-io/gorse?style=social&color=white)](https://github.com/gorse-io/gorse/stargazers) | Turnkey AI recommender engine written in Go. Automatically ingests user-item interactions, trains offline models, serves sub-10ms RESTful online recommendations with multimodal embeddings and admin GUI. | Go |
| **[GrowthBook](https://github.com/growthbook/growthbook)** | [![GrowthBook Stars](https://img.shields.io/github/stars/growthbook/growthbook?style=social&color=white)](https://github.com/growthbook/growthbook/stargazers) | Feature flagging and A/B experimentation platform with Bayesian and sequential statistical engines, CUPED variance reduction, and warehouse-native queries. | TypeScript, React, Go |
| **[Feast](https://github.com/feast-dev/feast)** | [![Feast Stars](https://img.shields.io/github/stars/feast-dev/feast?style=social&color=white)](https://github.com/feast-dev/feast/stargazers) | Open-source feature store for machine learning, bridging offline feature pipelines to ultra-low-latency online stores (Redis, DynamoDB) for real-time inference. | Python, Go |
| **[Surprise](https://github.com/NicolasHug/Surprise)** | [![Surprise Stars](https://img.shields.io/github/stars/NicolasHug/Surprise?style=social&color=white)](https://github.com/NicolasHug/Surprise/stargazers) | Scikit for building and analyzing collaborative filtering recommender systems with explicit rating datasets and matrix factorization (SVD, SVD++, NMF). | Python, Cython |
| **[LightFM](https://github.com/lyst/lightfm)** | [![LightFM Stars](https://img.shields.io/github/stars/lyst/lightfm?style=social&color=white)](https://github.com/lyst/lightfm/stargazers) | Hybrid matrix factorization recommendation model incorporating both user/item interaction metadata and implicit feedback signals. | Python, C |
| **[Implicit](https://github.com/benfred/implicit)** | [![Implicit Stars](https://img.shields.io/github/stars/benfred/implicit?style=social&color=white)](https://github.com/benfred/implicit/stargazers) | Ultra-fast GPU-accelerated collaborative filtering library for implicit feedback datasets using Alternating Least Squares (ALS) and Bayesian Personalized Ranking (BPR). | Python, Cython, CUDA |
| **[TorchRec](https://github.com/meta-pytorch/torchrec)** | [![TorchRec Stars](https://img.shields.io/github/stars/meta-pytorch/torchrec?style=social&color=white)](https://github.com/meta-pytorch/torchrec/stargazers) | PyTorch domain library created by Meta for building massive, high-throughput recommendation systems with distributed embedding parallelism. | Python, PyTorch, C++ |
| **[Metarank](https://github.com/metarank/metarank)** | [![Metarank Stars](https://img.shields.io/github/stars/metarank/metarank?style=social&color=white)](https://github.com/metarank/metarank/stargazers) | Real-time Learning-to-Rank (LTR) secondary re-ranking service. Combines clicks, purchases, and contextual signals into personalized orderings in 10–20ms. | Scala, Java |
| **[Apache Mahout](https://github.com/apache/mahout)** | [![Mahout Stars](https://img.shields.io/github/stars/apache/mahout?style=social&color=white)](https://github.com/apache/mahout/stargazers) | Distributed linear algebra framework and mathematically expressive system for scalable recommendation and classification workflows. | Java, Scala |
| **[python-recsys](https://github.com/ocelma/python-recsys)** | [![python-recsys Stars](https://img.shields.io/github/stars/ocelma/python-recsys?style=social&color=white)](https://github.com/ocelma/python-recsys/stargazers) | Classical Python library for computing user-item affinity, Singular Value Decomposition (SVD), and neighborhood recommendation baselines. | Python |
| **[Deep Recommender System](https://github.com/chocoluffy/deep-recommender-system)** | [![Deep Recsys Stars](https://img.shields.io/github/stars/chocoluffy/deep-recommender-system?style=social&color=white)](https://github.com/chocoluffy/deep-recommender-system/stargazers) | Implementation benchmark of deep neural recommendation models including BERT4Rec, SASRec, Multi-Interest Networks (MIND), and Contrastive Learning. | Python, PyTorch |
| **[Bucketeer](https://github.com/bucketeer-io/bucketeer)** | [![Bucketeer Stars](https://img.shields.io/github/stars/bucketeer-io/bucketeer?style=social&color=white)](https://github.com/bucketeer-io/bucketeer/stargazers) | Enterprise-grade feature management and continuous experimentation engine created and battle-tested at CyberAgent with real-time targeting rules. | Go, TypeScript |
| **[Too](https://github.com/FurqanSoftware/too)** | [![Too Stars](https://img.shields.io/github/stars/FurqanSoftware/too?style=social&color=white)](https://github.com/FurqanSoftware/too/stargazers) | Lightweight Go microservice implementing item-to-item collaborative filtering using Redis sets and sorted sets for low-overhead setups. | Go, Redis |
| **[EdgePersona](https://github.com/Crynge/EdgePersona)** | [![EdgePersona Stars](https://img.shields.io/github/stars/Crynge/EdgePersona?style=social&color=white)](https://github.com/Crynge/EdgePersona/stargazers) | Python real-time cross-channel edge Customer Data Platform (CDP) featuring Thompson Sampling bandits, DBSCAN identity resolution, and <5ms reads. | Python, Redis |
| **[Experimently](https://github.com/getexperimently/experimently)** | [![Experimently Stars](https://img.shields.io/github/stars/getexperimently/experimently?style=social&color=white)](https://github.com/getexperimently/experimently/stargazers) | Self-hosted experimentation engine offering 15 client/server SDKs, automated rollbacks, and sequential statistical hypothesis validation. | TypeScript, Go |
| **[ReflexUI](https://github.com/mmarqueti/reflexui)** | [![ReflexUI Stars](https://img.shields.io/github/stars/mmarqueti/reflexui?style=social&color=white)](https://github.com/mmarqueti/reflexui/stargazers) | Adaptive UI screen layout engine driven by typed-judgment models, separating relevance ranking from application business safety policies. | TypeScript, React |

---

## 🏗️ Reference Modern Real-Time Stack Architecture

To build a sovereign, cost-effective, real-time personalization platform entirely from open-source technologies:

```
┌────────────────────────────────────────────────────────────────────────┐
│                        User Touchpoints (Web / App / API)              │
└────────────────────────────────────┬───────────────────────────────────┘
                                     │ Event Stream (<10ms)
                                     ▼
┌────────────────────────────────────────────────────────────────────────┐
│  Real-Time Profile & Identity: Redis / EdgePersona                     │
├────────────────────────────────────────────────────────────────────────┤
│  Feature Store: Feast (Online user & item feature retrieval)           │
├────────────────────────────────────────────────────────────────────────┤
│  1. Candidate Retrieval: Qdrant / Milvus (Approximate Nearest Neighbors)│
│  2. Collaborative Scoring: Gorse / Implicit                            │
│  3. Re-Ranking (Learning to Rank): Metarank                            │
│  4. Continuous Exploration: Multi-Armed Bandits (Thompson Sampling)   │
├────────────────────────────────────────────────────────────────────────┤
│  Experimentation & Delivery Guardrails: GrowthBook / Bucketeer         │
└────────────────────────────────────┬───────────────────────────────────┘
                                     │ Ranked Personalization Payload
                                     ▼
                        Personalized User Experience
```

---

## 🤝 How to Contribute

We welcome additions, corrections, and benchmark submissions! 🚀

1. 🍴 **Fork** this repository.
2. 🌿 **Create a branch** for your updates (`git checkout -b add-my-personalization-tool`).
3. 📝 **Edit `README.md`**:
   - Provide accurate links and descriptions.
   - For SaaS tools: include verified starting tier pricing, explicit free tier / trial limits, and company size.
   - For Open-Source tools: include official star badge with link to stargazers.
4. 📬 **Submit a Pull Request** with a concise summary of the addition.

---

## ⚖️ Disclaimer

- This is a community-maintained curated educational resource and does not constitute financial or software endorsement.
- Real-time personalization engines process personal data and must adhere to applicable regulatory frameworks including **GDPR, CCPA/CPRA, and privacy best practices** (consent modes, pseudonymization, and data minimization).

---

<p align="center">
  <b>🌟 Star this repository if you find it helpful for your personalization architecture!</b>
</p>
