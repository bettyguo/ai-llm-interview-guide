# llm-interview-prep

[![Live demo](https://img.shields.io/badge/live%20demo-bettyguo.github.io%2Fllm--interview--prep-6f4e37?logo=githubpages&logoColor=white)](https://bettyguo.github.io/llm-interview-prep/)
[![License: content CC-BY-4.0 / tooling MIT](https://img.shields.io/badge/license-CC--BY--4.0%20%2F%20MIT-blue.svg)](LICENSE)
[![Last updated](https://img.shields.io/github/last-commit/bettyguo/llm-interview-prep?label=last%20updated)](https://github.com/bettyguo/llm-interview-prep/commits/main)
[![Stars](https://img.shields.io/github/stars/bettyguo/llm-interview-prep?style=social)](https://github.com/bettyguo/llm-interview-prep/stargazers)

> **Everything you need to walk into an AI, LLM, or ML engineering interview prepared** — concepts, questions, worked answers, system-design drills, and a time-boxed study plan, curated by an active AI researcher.

Hiring loops for AI/ML/LLM roles in 2026 test a wider stack than any one blog post or repo covers — classical ML, deep-learning fundamentals, transformer internals, training and fine-tuning, inference and serving, retrieval and RAG, agents and harnesses, evaluation, ML system design, coding, behavioral. This repo unifies all of it.

Every non-trivial answer carries an **authoritative reference** to the original paper, primary docs, or a widely-cited textbook. The validator refuses to ship entries without one. That's the contract: an answer in this repo is one you can defend in an interview.

---

## The topic spine

<!-- BUILD:TOPICS:START -->

- [01 — ML & DL Fundamentals](prep/01-ml-dl-fundamentals/)
- [02 — Transformers & LLM Internals](prep/02-transformers-llm-internals/)
- [03 — Training & Fine-Tuning](prep/03-training-fine-tuning/)
- [04 — Inference & Serving](prep/04-inference-serving/)
- [05 — Retrieval & RAG](prep/05-retrieval-rag/)
- [06 — Agents & Harnesses](prep/06-agents-harnesses/)
- [07 — Evaluation & Calibration](prep/07-evaluation-calibration/)
- [08 — ML System Design](prep/08-ml-system-design/)
- [09 — ML / AI Coding Questions](prep/09-coding/)
- [10 — Research Discussion & Paper Deep-Dives](prep/10-research-discussion/)
- [11 — Behavioral & Communication](prep/11-behavioral/)

<!-- BUILD:TOPICS:END -->

### Stats

<!-- BUILD:STATS:START -->

**Total questions:** 501

| # | Topic | Questions |
|---|-------|-----------|
| 1 | 01 — ML & DL Fundamentals | 62 |
| 2 | 02 — Transformers & LLM Internals | 63 |
| 3 | 03 — Training & Fine-Tuning | 61 |
| 4 | 04 — Inference & Serving | 63 |
| 5 | 05 — Retrieval & RAG | 55 |
| 6 | 06 — Agents & Harnesses | 49 |
| 7 | 07 — Evaluation & Calibration | 48 |
| 8 | 08 — ML System Design | 10 |
| 9 | 09 — ML / AI Coding Questions | 42 |
| 10 | 10 — Research Discussion & Paper Deep-Dives | 23 |
| 11 | 11 — Behavioral & Communication | 25 |

<!-- BUILD:STATS:END -->

---

## What's in scope (and what isn't)

Everything an interview loop for an AI/ML/LLM engineering role actually tests: classical ML fundamentals, deep-learning fundamentals, transformer & LLM internals, training & fine-tuning (SFT, RLHF, DPO, GRPO, LoRA/QLoRA), inference & serving (KV cache, paged attention, speculative decoding, quantization), retrieval & RAG, agents & harnesses, evaluation & calibration, ML system design drills (10 worked), ML/AI coding (NumPy/PyTorch implementations), research discussion, behavioral.

---

## How this is kept correct

Every non-trivial answer must cite an authoritative source — the original paper, primary framework docs (PyTorch / HuggingFace / OpenAI / Anthropic), or a widely-cited textbook (Murphy, Goodfellow, Speech & Language Processing). The `tools/validate_entries.py` step in CI refuses to merge entries that lack a `References` block.

Contested or version-dependent facts (e.g. "FlashAttention is X× faster") are stated as tradeoffs, not absolutes. Where the field has revised a popular result (Kaplan → Chinchilla scaling), the revised view is the primary one, with the older one shown for context.

**See a wrong answer?** Open a [wrong-answer issue](.github/ISSUE_TEMPLATE/wrong-answer.md) — wrong answers are the highest-priority bug in this repo.


ling: [MIT](LICENSE).

