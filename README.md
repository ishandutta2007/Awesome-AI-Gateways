<div align="center">
  <img src="https://raw.githubusercontent.com/Portkey-AI/gateway/main/docs/images/gateway-banner.png" width="100%" alt="Awesome AI Gateway Banner" />

  <h1>🚀 Awesome AI Gateways</h1>

  <p><strong>A curated list of the best AI Gateways, LLM Routers, and Proxies to unify OpenAI, Anthropic, Gemini, and more.</strong></p>

  <p>
    <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" alt="Maintained" />
    <img src="https://img.shields.io/badge/Awesome-Gateways-blueviolet" alt="Awesome" />
    <img src="https://img.shields.io/badge/LLM-Routing-FF69B4" alt="LLM Routing" />
    <img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-AI-Gateways?style=flat&color=yellow" alt="Stars" />
    <img src="https://img.shields.io/github/last-commit/ishandutta2007/Awesome-AI-Gateways" alt="Last Commit" />
  </p>

  <h4>Unified API • Load Balancing • Fallbacks • Cost Tracking • Observability</h4>
</div>

---

## 🌟 Introduction

This repository is an SEO-optimized, curated ecosystem of **SaaS platforms** and **Open-Source projects** for building **AI Gateways**. These intelligent proxies act as a unified bridge to multiple LLM providers, ensuring high availability, performance, and significant cost savings.

### 🔄 How it Works
<div align="center">
  <img src="https://raw.githubusercontent.com/Portkey-AI/gateway/main/docs/images/gateway-demo.gif" width="80%" alt="AI Gateway Routing Demo" />
</div>

---
## 🧭 Which Gateway Should I Use?

Not sure where to start? Use this quick guide:

| Your situation | Recommended option |
|---|---|
| Student or beginner experimenting with LLMs | OpenRouter (free tier, 50 req/day) or LangChain |
| Building a production app and need observability | Portkey or Helicone |
| Want everything self-hosted and private | LiteLLM open-source |
| Need edge performance and global scale | Cloudflare AI Gateway |
| Building AI agents with complex routing logic | LangChain / LangGraph |
| Running local models on your own machine | Ollama + Open WebUI |
| Enterprise with budget management and SSO | LiteLLM Cloud |

---

## 📑 Table of Contents
- [🌐 SaaS Products](#-saas-products)
- [🏗️ Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚖️ Disclaimer](#-disclaimer)

---

## 🌐 SaaS Products

### 📊 Core AI Gateway Comparison

| SaaS Product | Pricing Model | Free Tier Limit | Key Features |
| :--- | :--- | :--- | :--- |
| **[OpenRouter](https://openrouter.ai/)** | Pay-as-you-go | 50 req/day (Free models) | Aggregates 100+ LLMs; smart routing & fallback. |
| **[Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway/)** | Usage-based | 100,000 logs/month | Edge-native; unlimited requests; caching & rate limiting. |
| **[Portkey](https://portkey.ai/)** | Pay-as-you-go | 10,000 logs/month | Observability, caching, guardrails, and multi-provider routing. |
| **[Helicone](https://helicone.ai/)** | Usage-based | 10,000 requests/month | LLM observability, custom properties, and cost tracking. |
| **[PromptLayer](https://promptlayer.com/)** | Usage-based | 2,500 requests/month | Prompt management, versioning, and evaluation middleware. |
| **[LiteLLM Cloud](https://litellm.ai/)** | Enterprise ($250/mo+) | 7-30 day trial | Managed proxy with RBAC, budget management, and SSO. |
| **[Glama](https://glama.ai/)** | Pay-as-you-go | Free MCP hosting | Performance-focused gateway and MCP server hosting. |

### 🛠️ Platform Details

- **[OpenRouter](https://openrouter.ai/)** 🚀  
  Leading intelligent router that aggregates dozens of LLMs with smart model routing, fallback, and competitive pricing.
- **[LiteLLM](https://litellm.ai/)** 🛡️  
  Popular proxy layer with unified API and advanced routing, logging, and cost management features.
- **[Portkey](https://portkey.ai/)** 🔑  
  Full-featured AI gateway with observability, caching, guardrails, and multi-provider routing.
- **[Glama](https://glama.ai/)** 💎  
  Modern AI gateway focused on performance, reliability, and developer-friendly features.
- **[Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway/)** ☁️  
  Edge-native gateway with powerful caching, rate limiting, and global performance benefits.
- **[Helicone](https://helicone.ai/)** 🔦  
  Popular observability platform for LLMs with easy integration via proxy or SDK.
- **[PromptLayer](https://promptlayer.com/)** 📑  
  Specialized platform for prompt engineering, management, and tracking production LLM usage.

---

## 🏗️ Open-Source GitHub Projects

### 🛠️ Dedicated AI Gateway & Proxy Solutions

- **[LiteLLM](https://github.com/BerriAI/litellm)** ⭐  
  The most popular open-source LLM proxy and gateway. Supports 100+ models with unified OpenAI-compatible API, load balancing, fallback, caching, logging, and cost tracking.

- **[Portkey Gateway](https://github.com/Portkey-AI/gateway)** 🧩  
  Open-source core of Portkey with powerful routing, observability, and guardrails capabilities.

- **[OpenRouter Self-Hosted](https://github.com/search?q=openrouter+self+hosted)** 🏠  
  Community self-hosted routers inspired by OpenRouter with multi-provider support.

- **[vLLM + FastAPI Gateways](https://github.com/vllm-project/vllm)** ⚡  
  High-performance inference server with custom gateway layers for production LLM routing.

- **[Ollama + Open WebUI](https://github.com/open-webui/open-webui)** 🐳  
  Complete local LLM platform with robust API gateway and multi-model routing capabilities.

- **[LocalAI](https://github.com/mudler/LocalAI)** 🤖  
  Self-hosted drop-in replacement for OpenAI with support for many backends and gateway features.

- **[FastChat](https://github.com/lm-sys/FastChat)** 💬  
  Open platform for training, serving, and evaluating chatbots with multi-model gateway support.

### 📦 Additional Strong Open-Source Options

- [LangChain](https://github.com/langchain-ai/langchain) is an open-source framework 
for building LLM-powered applications with built-in support for routing between 
multiple providers including OpenAI, Anthropic, Google Gemini, and more. 
- [LangGraph](https://github.com/langchain-ai/langgraph) extends this with stateful, 
multi-agent orchestration and conditional routing logic.

**Best for:** Developers building AI agents, RAG pipelines, and multi-step 
reasoning applications that need flexible, code-driven model routing.

**Key features:**
- Unified interface across 50+ LLM providers
- Built-in memory, tool calling, and agent frameworks
- LangGraph enables complex conditional routing between models
- Active community and extensive documentation

**Quick start:**
```python
from langchain_anthropic import ChatAnthropic
from langchain_openai import ChatOpenAI

# Switch providers with one line — same interface
model = ChatAnthropic(model="claude-sonnet-4-20250514")
model = ChatOpenAI(model="gpt-4o")
```
- **[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** — Microsoft’s AI orchestration with gateway-like features.
- **[Dify](https://github.com/langgenius/dify)** — AI app platform with built-in model routing and gateway.

---

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

---

## ⚖️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Self-hosted open-source gateways require proper security, monitoring, and rate limiting configuration.

---

## 📈 Star History

<div align="center">
	<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-AI-Gateways&type=date&legend=bottom-right">
	 <picture>
	   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Gateways&type=date&theme=dark&legend=bottom-right" />
	   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Gateways&type=date&legend=bottom-right" />
	   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Gateways&type=date&legend=bottom-right" />
	 </picture>
	</a>
</div>

---

**Made for AI engineers, developers, and teams building scalable LLM applications.**  
Let's make LLM access more reliable, private, and cost-effective.
