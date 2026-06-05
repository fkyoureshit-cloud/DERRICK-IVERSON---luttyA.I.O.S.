# Elastic Workflows Integration

> Curated collection of high-efficiency workflows for luttyA.I.O.S from Elastic's workflow library

## 📋 Overview

This directory contains **integrated workflows** from Elastic, organized by category and optimized for efficiency:

- **Utilities** (4 workflows) - Core building blocks for task execution
- **AI Agents** (2 workflows) - Intelligent automation and alert triage
- **Firebase** (2 workflows) - Authentication and token management  
- **Search** (2 workflows) - Web search and semantic knowledge base queries

**Total: 11 high-efficiency workflows**

---

## 📂 Directory Structure

```
workflows/
├── README.md                           # This file
├── SETUP.md                            # Setup and configuration guide
├── utilities/                          # Core utility workflows
│   ├── get-time.yaml                   # UTC and timezone-aware time retrieval
│   ├── execute.yaml                    # Command execution on endpoints
│   ├── get-action-status.yaml          # Action status polling
│   └── invoke-other-workflows.yaml     # Workflow orchestration
├── ai-agents/                          # AI-powered automation
│   ├── invoke-an-agent.yaml            # Manual/alert-triggered agent invocation
│   └── call-subagent-workflow.yaml     # Subagent interaction
├── integrations/
│   └── firebase/                       # Firebase authentication
│       ├── grant-firebase-bearer-token.yaml
│       └── grant-and-fetch-firebase-bearer-token.yaml
└── search/                             # Search and query workflows
    ├── web-search.yaml                 # Brave Search API integration
    └── semantic-knowledge-search.yaml  # Semantic knowledge base queries
```

---

## 🚀 Quick Start

### 1. Prerequisites

Before using these workflows, ensure you have:
- Kibana/Elasticsearch deployment access
- API keys for external services (if using integrations)
- Proper permissions in your Kibana environment

### 2. Import Workflows

**Via Kibana UI:**
1. Navigate to **Management → Workflows**
2. Click **Create workflow**
3. Copy YAML content from any workflow file
4. Update constants/placeholders for your environment
5. Save and test

### 3. Configuration

See [SETUP.md](./SETUP.md) for detailed configuration instructions for each workflow category.

---

## 📊 Workflow Categories

### ⚙️ Utilities (4 workflows)

Core building blocks for automation

### 🤖 AI Agents (2 workflows)

Intelligent automation with AI

### 🔐 Firebase (2 workflows)

Authentication and token management

### 🔎 Search (2 workflows)

Search and knowledge queries

---

## 📄 License

These workflows are derived from Elastic's public workflow library.
- **Source:** [elastic/workflows](https://github.com/elastic/workflows)
- **License:** Apache 2.0