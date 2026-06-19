---
title: "Electrolyte Lab: Multi-Agent Platform for Battery Electrolyte Research"
excerpt: "LangGraph multi-agent workflows, scientific RAG, knowledge graph extraction, and closed-loop formulation optimization."
collection: portfolio
---

Built a battery electrolyte research platform at Tsinghua University that connects literature research, knowledge extraction, molecular design, and experimental execution.

## Overview

Electrolyte Lab is an AI research platform for battery electrolyte discovery. The system is designed to support the full loop from literature exploration to knowledge extraction, molecular prediction, formulation optimization, and experimental execution.

## My Role

I worked on the multi-agent workflow, scientific RAG architecture, knowledge graph extraction, and closed-loop optimization modules.

## Key Work

- Built a **LangGraph state-machine workflow** with specialized agents, conditional routing, quality-control checks, workflow persistence, and human-in-the-loop intervention.
- Designed scientific RAG over **180k+ papers** using Milvus, Elasticsearch BM25, RRF fusion, bge-m3 embeddings, and bge-reranker-v2-m3 two-stage reranking.
- Implemented recursive knowledge extraction for battery systems, electrolyte formulas, electrode materials, solvents, salts, additives, and performance metrics.
- Wrapped molecular prediction, formulation optimization, and device-control capabilities as **Skill-based APIs** to reduce hallucination and make agent actions auditable.
- Used BoTorch and GPyTorch for constrained multi-objective Bayesian optimization in high-dimensional formulation spaces.

## Impact

- Improved literature retrieval and citation traceability for domain experts.
- Connected unstructured papers, structured knowledge, molecular tools, and optimization algorithms into a single research workflow.
- Established a reusable agent + Skill API pattern for scientific automation.

## Tech Stack

**Python, LangGraph, Milvus, Elasticsearch, bge-m3, bge-reranker-v2-m3, BoTorch, GPyTorch, RDKit, FastAPI, React, TypeScript**
