---
title: "ChemMind: Chemistry Domain QA System"
excerpt: "Domain SFT and evaluation pipeline for chemistry QA with Qwen3-8B, QLoRA, MinerU, and LLM-as-a-Judge."
collection: portfolio
---

<div class="project-detail" markdown="1">

ChemMind is a chemistry-domain question answering system focused on reducing hallucination and improving domain adaptation for general-purpose LLMs.

## Overview

ChemMind explores how to adapt a general LLM to chemistry tasks under limited compute. The project covers data engineering, lightweight fine-tuning, benchmark construction, and model comparison.

## My Role

I led the chemistry-domain data pipeline, QLoRA fine-tuning setup, and evaluation design.

## Key Work

- Built a **MinerU-based literature parsing pipeline** with multi-stage cleaning, token distribution analysis, and sequence-length filtering.
- Designed a data mixture across general QA, textbook extraction, paper extraction, DeepSeek-distilled content, and chemistry problem pairs.
- Fine-tuned Qwen3-8B using **BitsAndBytes 4-bit quantization + QLoRA** on a single T4 GPU.
- Configured Llama Factory training with mixed precision, gradient accumulation, warmup, train/test split, and dynamic shuffling.
- Built a three-part evaluation system covering objective QA, chain-of-thought chemistry problems, and ablation studies.

## Lessons

- Fine-tuning improved domain behavior, but gains were bounded by base-model reasoning ability.
- For resource-limited scenarios, stronger base models plus careful prompting and few-shot context can sometimes iterate faster than full fine-tuning.

## Tech Stack

**PyTorch, Transformers, Llama Factory, BitsAndBytes, QLoRA, vLLM, MinerU, LLM-as-a-Judge**

</div>
