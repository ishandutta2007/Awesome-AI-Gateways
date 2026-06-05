# Awesome-AI-Gateways
## Top AI Gateways (OpenRouter Alternatives) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on LLM Routing, Proxy, Load Balancing & Multi-Provider Gateways*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** building **AI Gateways** — intelligent proxies and routers that unify access to multiple LLMs (OpenAI, Anthropic, Groq, Gemini, local models, etc.), handle fallback, load balancing, cost optimization, observability, caching, and rate limiting.

**Examples** include OpenRouter, LiteLLM, Portkey, Glama, and Cloudflare AI Gateway (the category leaders). Tools listed here emphasize **unified API**, model routing, reliability, cost control, and privacy.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local deployment, full customization, and complete data control — ideal for developers and teams wanting sovereign, high-performance LLM gateways.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### Core AI Gateway Platforms

- **[OpenRouter](https://openrouter.ai/)**  
  Leading intelligent router that aggregates dozens of LLMs with smart model routing, fallback, and competitive pricing.

- **[LiteLLM](https://litellm.ai/)** (with hosted options)  
  Popular proxy layer with unified API and advanced routing, logging, and cost management features.

- **[Portkey](https://portkey.ai/)**  
  Full-featured AI gateway with observability, caching, guardrails, and multi-provider routing.

- **[Glama](https://glama.ai/)**  
  Modern AI gateway focused on performance, reliability, and developer-friendly features.

- **[Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway/)**  
  Edge-native gateway with powerful caching, rate limiting, and global performance benefits.

### Advanced & Specialized Platforms

**Other notable mentions**: Helicone, PromptLayer, and various enterprise LLM gateways.

## Open-Source GitHub Projects

### Dedicated AI Gateway & Proxy Solutions

- **[LiteLLM](https://github.com/BerriAI/litellm)**  
  The most popular open-source LLM proxy and gateway. Supports 100+ models with unified OpenAI-compatible API, load balancing, fallback, caching, logging, and cost tracking. Can be self-hosted easily.

- **[Portkey Gateway (Open Source Components)](https://github.com/Portkey-AI/gateway)**  
  Open-source core of Portkey with powerful routing, observability, and guardrails capabilities.

- **[OpenRouter Self-Hosted Alternatives](https://github.com/search?q=openrouter+self+hosted)**  
  Community self-hosted routers inspired by OpenRouter with multi-provider support.

- **[vLLM + FastAPI Gateways](https://github.com/vllm-project/vllm)**  
  High-performance inference server with custom gateway layers for production LLM routing.

- **[Text Generation WebUI (Oobabooga)](https://github.com/oobabooga/text-generation-webui)**  
  Popular local LLM interface with OpenAI-compatible API server, widely used as a self-hosted gateway.

- **[Ollama + Open WebUI](https://github.com/open-webui/open-webui)**  
  Complete local LLM platform with robust API gateway and multi-model routing capabilities.

- **[LocalAI](https://github.com/mudler/LocalAI)**  
  Self-hosted drop-in replacement for OpenAI with support for many backends and gateway features.

- **[FastChat](https://github.com/lm-sys/FastChat)**  
  Open platform for training, serving, and evaluating chatbots with multi-model gateway support.

- **[Aphrodite Engine](https://github.com/PygmalionAI/aphrodite-engine)** (and forks)  
  High-throughput inference engine with strong gateway and proxy capabilities.

### Additional Strong Open-Source Options

- **[LangChain / LangGraph Routers](https://github.com/langchain-ai/langgraph)** — For building intelligent agentic routing logic.
- **[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** — Microsoft’s AI orchestration with gateway-like features.
- **[Haystack](https://github.com/deepset-ai/haystack)** — Production LLM pipelines with routing components.
- **[Dify](https://github.com/langgenius/dify)** — AI app platform with built-in model routing and gateway.
- Many community **FastAPI + LiteLLM** custom gateways for specific use cases (caching, guardrails, logging).
- **Cloudflare Workers + AI Gateway** open-source patterns and templates.

**Frameworks for building custom gateways**: Use **LiteLLM** as the foundation + **FastAPI** + **Redis** (for caching) + **LangGraph** for advanced routing logic. Deploy with Docker for full self-hosting.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Self-hosted open-source gateways require proper security, monitoring, and rate limiting configuration.
- Always respect provider terms when routing through third-party models.

---

**Made for AI engineers, developers, and teams building scalable LLM applications.**  
Let's make LLM access more reliable, private, and cost-effective.