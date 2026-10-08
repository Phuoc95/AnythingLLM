# AnythingLLM Lab

A local environment setup and testing playground for [AnythingLLM](https://anythingllm.com/) with Docker Compose and embedded chat widgets.

## Overview

- **`docker-compose.yml`**: Docker service configuration running `mintplexlabs/anythingllm:latest` on port `3001` with local storage mapping.
- **`demo_docs/`**: Sample knowledge base documents for testing RAG workspaces (`apalink_project.md`, `kokowa_project.md`).
- **`test_apalink.html` & `test_kokowa.html`**: Landing page prototypes with embedded workspace chat widgets for testing chatbot responses and contextual grounding.
- **`demo_embed.html`**: Workspace chat embed widget preview and test interface.

## Quick Start

### 1. Run AnythingLLM Container

```bash
docker compose up -d
```

Access the AnythingLLM web interface at `http://localhost:3001`.

### 2. Test Embedded Chat Widgets

Open the test HTML files directly in your browser or run a simple HTTP server:

```bash
python3 -m http.server 8080
```
