# Dimiter Milushev

**AI agent security · ML for cyber security · PhD in computer science (noninterference)**

I build open-source defences for LLM agents and measure them the way a security team would: on held-out data, at fixed false-positive budgets, with the limits written down.

## Projects

| Layer | Project | What it does |
| --- | --- | --- |
| **Detect** | [ShieldLM](https://github.com/dvm81/shieldlm) · [model](https://huggingface.co/dmilush/shieldlm-deberta-base) · [dataset](https://huggingface.co/datasets/dmilush/shieldlm-prompt-injection) | DeBERTa-v3 prompt-injection classifier trained on 54k examples from 11 public sources. 96.1% recall at 0.1% false-positive rate. |
| **Scan** | [shieldlm-mcp](https://github.com/dvm81/shieldlm-mcp) · [model](https://huggingface.co/dmilush/shieldlm-deberta-mcp-tools) | Static security scanner for MCP server configs: poisoned tool descriptions, over-privileged servers, leaked secrets, typosquatted packages. Its fine-tuned model reads tool descriptions in nine languages and catches 89% of attacks from benchmarks it never trained on, at 1% false positives. |

## Writing

On [Medium](https://medium.com/@dimiter.milushev).

## Background

A decade of machine learning for cyber security and GenAI in banking, including founding and leading a cyber-security AI team. PhD from KU Leuven on [hyperproperties](http://milushev.github.io/pdf/ThesisMilushev.pdf), the logic behind noninterference. CISSP, GCFA.

[Hugging Face](https://huggingface.co/dmilush) · [Medium](https://medium.com/@dimiter.milushev) · [LinkedIn](https://www.linkedin.com/in/dimiter-milushev-phd) · [Google Scholar](https://scholar.google.com/citations?user=-VlKMUoAAAAJ&hl=en)
