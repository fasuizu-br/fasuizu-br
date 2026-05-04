# Hi, I'm Fabio Suizu 👋

Indie hacker building **[Brainiall](https://chat.brainiall.com)** — an AI gateway with 104 models for $5.99/mo flat. EU-hosted (Frankfurt + Madrid). GDPR + AI Act compliant.

## 🚀 What I'm Building

### [Brainiall LLM Gateway](https://github.com/fasuizu-br/brainiall-llm-gateway) ⭐

[![Models](https://img.shields.io/badge/AI%20Models-104-blue)](https://chat.brainiall.com/v1/models)
[![Pricing](https://img.shields.io/badge/Pricing-%245.99%2Fmo%20flat-green)](https://chat.brainiall.com/pricing)
[![EU Hosted](https://img.shields.io/badge/EU%20Hosted-Frankfurt%20%2B%20Madrid-blueviolet)](https://chat.brainiall.com)
[![GDPR](https://img.shields.io/badge/GDPR-compliant-success)](https://chat.brainiall.com/dpa)
[![OpenAI Compatible](https://img.shields.io/badge/OpenAI%20SDK-compatible-orange)](https://chat.brainiall.com/openai-compatible-providers)

Drop-in OpenAI SDK replacement. Single API key for Claude 4.7, GPT-5, Gemini 3 Pro, Llama 4, DeepSeek R1 + 99 more models.

→ **[Free 7-day Pro trial at chat.brainiall.com](https://chat.brainiall.com)**

```python
from openai import OpenAI
client = OpenAI(
    base_url="https://api.brainiall.com/v1",
    api_key="brnl-..."
)
response = client.chat.completions.create(
    model="claude-sonnet-4-7",
    messages=[{"role": "user", "content": "Hello!"}],
)
```

## 📚 Brainiall Documentation

### Comprehensive Guides

- 🗺️ **[Roadmap Q2-Q3 2026 + Use Cases](https://github.com/fasuizu-br/brainiall-llm-gateway/issues/1)**
- ❓ **[FAQ — Brainiall vs OpenRouter / Cloudflare](https://github.com/fasuizu-br/brainiall-llm-gateway/issues/2)**
- 🔌 **[Integration Examples — LangChain, LlamaIndex, Vercel AI SDK, n8n](https://github.com/fasuizu-br/brainiall-llm-gateway/issues/3)**
- 🚀 **[Migration Guide — From OpenAI / Anthropic / OpenRouter](https://github.com/fasuizu-br/brainiall-llm-gateway/issues/4)**
- ⚡ **[Performance & Latency — Real Production Numbers](https://github.com/fasuizu-br/brainiall-llm-gateway/issues/5)**
- 💰 **[Pricing Calculator — Break-even Analysis](https://github.com/fasuizu-br/brainiall-llm-gateway/issues/6)**

### Code Tutorials (Public Gists)

- 🐍 **[Python Tutorial](https://gist.github.com/fasuizu-br/fd1b2bd91dd616516456e8d84257fd31)** (12 examples — chat, streaming, tools, vision, JSON, embeddings, RAG, STT, TTS, image gen, agent loop, model comparison)
- 🌐 **[TypeScript / Node.js Tutorial](https://gist.github.com/fasuizu-br/ab61e67356d7df9bbc3c32362ff9417e)** (12 examples + Vercel AI SDK + Cloudflare Workers)
- 🐚 **[Bash / curl CLI](https://gist.github.com/fasuizu-br/52e4f74701c87817dfa17df181184e7e)** (13 patterns + CI/CD health gate)
- 🔄 **[n8n Workflow JSON](https://gist.github.com/fasuizu-br/46e94a944348e98723f24150c19d4483)** (importable: chat + embeddings + TTS)
- ⚙️ **[Go Client](https://gist.github.com/fasuizu-br/49834336ac65c712f8579e6c33c93b3a)** (dependency-free `net/http` + K8s sidecar)

## 🎯 Why Brainiall?

| Feature | Brainiall | Per-token providers |
|---|---|---|
| **Models** | 104 (Claude/GPT/Gemini/Llama/DeepSeek) | 1 per provider |
| **Pricing** | $5.99/mo flat | per-token (surprises) |
| **Hosting** | EU (Frankfurt + Madrid) | US-primary |
| **Compliance** | GDPR + AI Act Article 50 | DPA only |
| **Multi-currency** | USD/EUR/BRL native | USD-only |
| **Bundled** | chat + embeddings + speech + vision + image | extra accounts |
| **Drop-in** | OpenAI SDK compatible | proprietary SDK |

## 📊 Honest Building-in-Public

Brainiall is bootstrapped (no VC). Currently:

- **23 users** total
- **0 paying customers**
- **104 AI models** integrated
- **8 locales** (PT-BR, EN, ES, DE, FR, IT, AR, JA)
- **Sub-second P95 latency** (real benchmarks: see [Issue #5](https://github.com/fasuizu-br/brainiall-llm-gateway/issues/5))
- **Compliance ready** (DPA, AI Act, subprocessors)

Lessons-learned > fluff. Real metrics, real progress.

## 🌍 Compliance + Trust

- 🛡️ [GDPR Article 28 DPA](https://chat.brainiall.com/dpa)
- 📋 [AI Act Article 50 Transparency](https://chat.brainiall.com/ai-disclosure)
- 📜 [Subprocessors](https://chat.brainiall.com/subprocessors)
- 🔒 [Security Disclosure (RFC 9116)](https://chat.brainiall.com/.well-known/security.txt)
- 📈 [SLA](https://chat.brainiall.com/sla) · [Status](https://chat.brainiall.com/status)

## 🤝 Connect

- 🌐 **Website**: [chat.brainiall.com](https://chat.brainiall.com)
- 📧 **Email**: support@brainiall.com
- 🐦 **Twitter/X**: @fabiosuizu (coming soon)
- 💼 **LinkedIn**: [in/fabiosuizu](https://linkedin.com/in/fabiosuizu)
- 📚 **Blog**: [chat.brainiall.com/blog](https://chat.brainiall.com/blog)

## 🛠️ Tech Stack

- **Backend**: FastAPI + Python · PostgreSQL · Redis
- **Frontend**: Vanilla JS · Caddy reverse proxy · HTTP/2 + HTTP/3
- **AI Models**: 104 models curated (Claude, GPT, Gemini, Llama, DeepSeek, Mistral, Cohere)
- **Infrastructure**: Latitude.sh bare-metal (Frankfurt + Madrid)
- **Stripe**: Multi-currency LIVE (USD/EUR/BRL)
- **Compliance**: GDPR + AI Act + LGPD ready

---

⭐ Star [brainiall-llm-gateway](https://github.com/fasuizu-br/brainiall-llm-gateway) if you find it useful.
