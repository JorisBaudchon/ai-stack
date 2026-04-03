# AI Stack (Ollama + Open WebUI + n8n + Qdrant + OpenClaw)

## 🚀 Overview

This project provides a local AI stack including:
- Ollama (LLM inference)
- Open WebUI (chat interface)
- n8n (automation workflows)
- Qdrant (vector database)
- OpenClaw (agent orchestration)

---

## ⚙️ Requirements

- Docker
- Docker Compose (v2)

---

## 🛠 Setup

```bash
git clone <your-repo>
cd ai-stack

cp .env.example .env
# edit .env if needed

docker compose up -d