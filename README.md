# 🤖 OpenAI-Agent-SDK

This repository contains a curated Jupyter Notebook featuring **multiple hands-on projects** built with the [OpenAI Agents SDK](https://openai.com/blog/function-calling-and-tools). Each project demonstrates a specific concept or capability—ranging from hosted tools and function tools to agent handoffs and hierarchical agent systems.

Ideal for developers, researchers, and AI enthusiasts exploring **generative AI**, **tool-augmented agents**, and **multi-agent collaboration**.

---

## 📘 What's Inside

Each section of the notebook introduces a concept followed by a working project:

| Topic | Description |
|-------|-------------|
| **Hosted Tools** | Use OpenAI-provided tools like web search in agent workflows |
| **Function Tools** | Integrate custom Python functions (e.g. weather APIs) |
| **Agents as Tools** | Build hierarchical systems with agents calling other agents |
| **Handoff Architecture** | Route conversations to specialized agents dynamically |
| **Weekend Planner** | A modular agent system for planning activities, food, and transport |
| **Budget & Weather-Aware Planning** | Extend agents with real-time data and constraints |
| **Customer Support Simulation** | Multi-agent triage system for sales, returns, and tech support |

---

## 🚀 Getting Started

1. Clone the repository  
2. Add your API keys to a `.env` file (e.g. OpenAI, OpenWeatherMap)  
3. Launch the notebook in Jupyter or VS Code  
4. Run each section interactively to explore agent behavior

---

## 📦 Requirements

- Python 3.9+
- `openai-agents`
- `requests`
- `python-dotenv`
- Jupyter Notebook

Install dependencies:

```bash
pip install -r requirements.txt
