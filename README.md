---
title: Agent Critiq Global
description: The intelligence layer for 500+ verified AI agents, software reviews, comparison matrices, Methodology v3.0 benchmarks, and MCP Server.
tags:
  - ai-agents
  - software-reviews
  - methodology-v3
  - mcp
  - huggingface-dataset
  - react
  - typescript
  - vite
license: mit
app_name: agent-critiq
website: https://agentcritiq.com
repository: https://github.com/dobby-aidev/agent-critiq
---

# 🚀 Agent Critiq — AI Tools & Agents Intelligence Platform

[![Live Site](https://img.shields.io/badge/Platform-agentcritiq.com-cyan.svg)](https://agentcritiq.com)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-130%2B_Downloads-yellow.svg)](https://huggingface.co/datasets/dobbyb-aidev/agent-critiq-ai-reviews)
[![MCP Server](https://img.shields.io/badge/MCP_Server-v3.6.0-indigo.svg)](./mcp-server/README.md)
[![Methodology v3.0](https://img.shields.io/badge/Protocol-Methodology_v3.0-violet.svg)](https://agentcritiq.com/about)
[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](https://opensource.org/licenses/MIT)

**Agent Critiq** is an independent AI tools intelligence and discovery matrix indexing 100+ state-of-the-art AI agents, LLMs, developer coding assistants, and generative engines with deep technical reviews, live SLA telemetries, and objective 4-phase benchmark scorecards.

- 🌐 **Live Platform:** [https://agentcritiq.com](https://agentcritiq.com)
- 🤗 **Hugging Face Dataset:** [dobbyb-aidev/agent-critiq-ai-reviews](https://huggingface.co/datasets/dobbyb-aidev/agent-critiq-ai-reviews)
- 🔌 **Official MCP Server:** [`mcp-server/`](./mcp-server)

---

## 🌟 Key Features / Temel Yetenekler

- 📊 **Metodoloji v3.0 (4-Phase Protocol):** 
  - **Phase 1 (25%):** Ecosystem & Community Pulse (GitHub activity, open-source adoption)
  - **Phase 2 (25%):** Laboratory Stress Engine & SLA (Context window, latency, uptime resilience)
  - **Phase 3 (20%):** Security & Data Privacy (Zero-data retention, shadow-training audit)
  - **Phase 4 (30%):** Expert Human Field Test (40+ hours hands-on testing by senior engineers)
- ⚡ **Official MCP Server (v3.6.0):** 7 comprehensive tools (`search_ai_tools`, `get_tool_detail`, `get_methodology_audit`, `get_agent_telemetry`, `list_categories`, `get_top_rated`, `compare_tools`) for Cursor, Windsurf, and Claude Desktop.
- ⏱️ **Live Agent SLA Telemetry:** Modeled response latency (ms), uptime SLA (%), and token throughput.
- 🌍 **Tri-lingual SEO & GEO Engine:** Native English, Turkish, and Spanish routes with AI-search (Perplexity, SearchGPT, Claude) structured data and `/llms.txt`.
- 🧮 **Interactive AI Tools:** Real-time B2B ROI Calculator, Compatibility Match Quiz, and Visual Output Gallery.

---

## 🔌 MCP Server Quickstart / MCP Sunucu Başlatma

The official MCP server is located in [`mcp-server`](./mcp-server):

```bash
cd mcp-server
npm install
node index.mjs
```

### Claude Desktop Configuration (`claude_desktop_config.json`):

```json
{
  "mcpServers": {
    "agent-critiq": {
      "command": "node",
      "args": ["<PATH_TO_PROJECT>/mcp-server/index.mjs"]
    }
  }
}
```

See [`mcp-server/README.md`](./mcp-server/README.md) for full tool signatures and prompts.

---

## 🤗 Hugging Face Dataset Integration

Our complete 2026 AI tool landscape is published on Hugging Face:

```python
from datasets import load_dataset

dataset = load_dataset("dobbyb-aidev/agent-critiq-ai-reviews")
print(dataset['train'][0])
```

---

## 📄 License

MIT © [Agent Critiq](https://agentcritiq.com)
