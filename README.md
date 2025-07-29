# LLM Agent Analysis

This repository contains the codebase and experimental setup for the project titled:

**"A Comparative Experimental Analysis of LLM Capabilities in Single-Agent and Multi-Agent Systems"**

##  Overview

This project evaluates modern LLMs like GPT-4, Claude, Mistral, and LLaMA on benchmarks for both:
- Single-agent scenarios (AgentBench, GAIA)
- Multi-agent scenarios (MultiAgentBench, BattleAgentBench)

## 📁 Repository Structure

```
LLM-Agent-Analysis/
├── scripts/               # Scripts to run and evaluate benchmarks
├── configs/               # Model and environment configurations
├── results/
│   └── raw/               # Raw results data
├── docs/                  # Project report, figures, comparison matrix
└── README.md              # This file
```

##  Getting Started

1. Clone the repo:
```bash
git clone https://github.com/riyadadlani02/LLM-Agent-Analysis.git
cd LLM-Agent-Analysis
```

2. Set up the environment:
```bash

conda create -n llm_agents python=3.10
conda activate llm_agents
pip install -r requirements.txt
```

3. Run a benchmark:
```bash
python scripts/run_agentbench.py
```

##  Outputs
- Detailed evaluation logs
- Comparison matrix in `docs/`
- Reproducibility checklist

## 📄 License
MIT License
