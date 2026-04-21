# 📊 LLM Benchmarks Live

<div align="center">
  <img src="https://img.shields.io/badge/Status-Live-success.svg" alt="Status Live" />
  <img src="https://img.shields.io/badge/Updated-Weekly-blue.svg" alt="Updated Weekly" />
  <p><strong>A weekly-updated leaderboard of LLM benchmarks with fully reproducible evaluation scripts.</strong></p>
</div>

## ✨ Overview

Navigating the landscape of Large Language Models (LLMs) requires objective metrics. **LLM Benchmarks Live** is an ongoing, open-source initiative to track the performance of top-tier models (both closed and open-weights) against industry-standard evaluations (MMLU, HumanEval, MT-Bench, etc.).

Unlike static leaderboards, this repository provides the exact Python scripts used to generate the benchmark scores, ensuring 100% transparency and reproducibility for academic and enterprise researchers.

## 🚀 Repro Scripts

Inside the `evals/` directory, you will find scripts for:

*   **HumanEval (Coding)**: Evaluates synthetic code generation and functional correctness.
*   **MMLU (Knowledge)**: Tests multitask language understanding across 57 subjects.
*   **Needle In A Haystack (Context)**: Stress-tests long-context retrieval capabilities.

*Note: You must supply your own API keys for closed models (e.g., OpenAI, Anthropic) via environment variables to run the local eval scripts.*

## 📈 Leaderboard Data

The raw JSON data powering the live leaderboard is stored in `data/leaderboard.json`. Feel free to parse this file for your own analytics dashboards.

## 🤝 Contributing

Have a new model or benchmark to add? Please read our `CONTRIBUTING.md` guidelines for formatting evaluation scripts and submitting pull requests to update the leaderboard.

---

## 🏢 About Stackaura

LLM Benchmarks Live is maintained by **Stackaura**. We specialize in providing top-tier digital solutions, focusing on scalable AI integration, premium branding, and robust software architecture designed to elevate your business.

**Want to build smarter, data-driven applications?**
> Visit us at [**Stackaura.com**](https://www.stackaura.com/) to learn more about our enterprise AI testing, development, and consulting services.

<div align="center">
  <a href="https://www.stackaura.com/">
    <img src="https://img.shields.io/badge/Visit-Stackaura-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Visit Stackaura" />
  </a>
</div>
