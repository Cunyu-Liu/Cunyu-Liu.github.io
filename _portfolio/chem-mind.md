---
title: "ChemMind: Chemistry Domain QA System"
excerpt: "Domain SFT and evaluation pipeline for chemistry QA with Qwen3-8B, QLoRA, MinerU, and LLM-as-a-Judge."
collection: portfolio
---

ChemMind is a chemistry-domain question answering system focused on reducing hallucination and improving domain adaptation for general-purpose LLMs.

**Highlights**

- Built a MinerU-based literature parsing and data cleaning pipeline.
- Designed scientific data mixing across general QA, textbook extraction, paper extraction, and problem-solving pairs.
- Fine-tuned Qwen3-8B with BitsAndBytes 4-bit quantization and QLoRA on a single T4 GPU.
- Built evaluation across THU-Benchmark, SUPERChem chain-of-thought problems, and ablation experiments.
- Compared fine-tuning with stronger base-model prompting and few-shot context learning.

**Tech stack:** PyTorch, Transformers, Llama Factory, BitsAndBytes, vLLM.
