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

## 🚀 Discover More from Stackaura

If you found this tool useful, check out our other high-performance web utilities and follow **Ahmar Hussain** for more open-source excellence.

### 🌟 Featured Projects
- **[Free LLM APIs](https://github.com/RanaAhmar/free-llm-apis)** - A curated list of zero-cost AI endpoints.
- **[Awesome MCP Servers](https://github.com/RanaAhmar/awesome-mcp-servers)** - The ultimate collection of Model Context Protocol implementations.
- **[System Design Cheatsheet](https://github.com/RanaAhmar/system-design-cheatsheet)** - Master complex architectures in minutes.
- **[Next.js SaaS Starter](https://github.com/RanaAhmar/nextjs-saas-starter)** - The fastest way to launch your next product.

### 🔗 Stay Connected
- **Website:** [stackaura.com](https://www.stackaura.com/)
- **Author:** [Ahmar Hussain](https://github.com/RanaAhmar)

---





