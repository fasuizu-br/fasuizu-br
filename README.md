# Hi 👋 I'm Fabio Suizu

Building **[Brainiall](https://chat.brainiall.com)** — an OpenAI-compatible AI gateway.

## What is Brainiall?

**104 AI models** through a single OpenAI-compatible API:

- **60+ chat models** — Claude 4.7, GPT-5, Gemini 3 Pro, Llama 4 Maverick, DeepSeek R1, Mistral, Qwen
- **12 image models** — gpt-5-image-2, Flux 2, Seedream 4.5, Imagen 4
- **5 video models** — Seedance 2.0, Veo 3, Kling 2.1
- **6 voice models** — Brainiall TTS, Voice Clone, Whisper

**$5.99/mo flat** (€4.99 EUR · R$29 BRL) — predictable cost, no per-token surprises.

**EU-hosted** (Frankfurt + Madrid) — GDPR Art 28 DPA + AI Act Article 50 compliant.

**Free 7-day Pro trial** — no credit card required.

→ [chat.brainiall.com](https://chat.brainiall.com)

## Quick start (3 lines)

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://api.brainiall.com/v1",
    api_key="brnl-..."  # get yours free at chat.brainiall.com
)

response = client.chat.completions.create(
    model="claude-sonnet-4-7",  # or gpt-5, gemini-3-pro, llama-4-maverick
    messages=[{"role": "user", "content": "Hello"}]
)
```

## Why Brainiall?

| Feature | Brainiall | OpenAI direct | OpenRouter | Vercel AI |
|---|---|---|---|---|
| Pricing | **$5.99/mo flat** | per-token | per-token + 5% fee | $5 free + per-token |
| Models | **104 curated** | OpenAI only | 290+ (incl deprecated) | Multi |
| Multi-modal | **LLM + image + video + voice** | LLM + image | LLM only | LLM only |
| OpenAI-compat | ✓ | ✓ | ✓ | ✓ |
| EU-hosted | **✓ Frankfurt+Madrid** | US | Mixed | US edge |
| Enterprise DPA | **Auto-download** | Contract | No | No |
| Multi-currency | **USD + EUR + BRL** | USD only | Multi | USD |

## Code examples (5 gists)

- 🐍 [Replace OpenAI in 1 line](https://gist.github.com/fasuizu-br/afae5d97a6129b81fa39c9f9903c44a4) — drop-in replacement
- 🇧🇷 [Brainiall em PT-BR](https://gist.github.com/fasuizu-br/538c77b2d9b6e1183ecf3c999138c1ff) — exemplo brasileiro com PIX
- 🎨 [Multi-modal (image + video + voice)](https://gist.github.com/fasuizu-br/49d21ae8d74776bc81e681b317a7b362) — replace 4 subscriptions
- 🦜 [LangChain integration + RAG](https://gist.github.com/fasuizu-br/06c58d30dd37ec156e9e9d068bb41b2f) — ChatOpenAI drop-in, ChromaDB
- 🤖 [Agents + RAG patterns](https://gist.github.com/fasuizu-br/481d4d403b1acb2a24cb948e23712f80) — function calling, vision, multi-step

## Resources

### Public app
- 🌐 **App**: [chat.brainiall.com](https://chat.brainiall.com)
- 🔌 **API base**: [api.brainiall.com](https://api.brainiall.com)
- 💰 **Pricing**: [chat.brainiall.com/pricing](https://chat.brainiall.com/pricing)
- 📚 **Models catalog (104 models)**: [chat.brainiall.com/best-llm-2026](https://chat.brainiall.com/best-llm-2026)

### Use cases by industry (English)
- [/llm-for-startups](https://chat.brainiall.com/llm-for-startups) · [/llm-for-developers](https://chat.brainiall.com/llm-for-developers) · [/llm-for-enterprise](https://chat.brainiall.com/llm-for-enterprise)
- [/llm-for-legal](https://chat.brainiall.com/llm-for-legal) · [/llm-for-finance](https://chat.brainiall.com/llm-for-finance) · [/llm-for-healthcare](https://chat.brainiall.com/llm-for-healthcare)
- [/llm-for-marketing-teams](https://chat.brainiall.com/llm-for-marketing-teams) · [/llm-for-saas-builders](https://chat.brainiall.com/llm-for-saas-builders) · 30+ more verticals

### Use cases (PT-BR — Brasil 🇧🇷)
- [/llm-for-advogados-brasil](https://chat.brainiall.com/llm-for-advogados-brasil) — IA para advogados brasileiros
- [/llm-for-contadores-brasil](https://chat.brainiall.com/llm-for-contadores-brasil) — IA para contadores brasileiros
- [/llm-for-medicos-brasil](https://chat.brainiall.com/llm-for-medicos-brasil) — IA para médicos brasileiros

### i18n
PT-BR · EN · ES · DE · FR · JA · AR (RTL) · IT — 8 locales heptagonal

### Switch from competitors
- [/switch-from-openai](https://chat.brainiall.com/switch-from-openai)
- [/switch-from-anthropic](https://chat.brainiall.com/switch-from-anthropic)
- [/switch-from-gemini](https://chat.brainiall.com/switch-from-gemini)
- [/switch-from-openrouter](https://chat.brainiall.com/switch-from-openrouter)

### Comparisons
- [/alternatives](https://chat.brainiall.com/alternatives) — 36+ AI tool comparisons

## Open source

- [brainiall-llm-gateway](https://github.com/fasuizu-br/brainiall-llm-gateway) — integration docs + cURL examples
- [Latest release v1.0.0](https://github.com/fasuizu-br/brainiall-llm-gateway/releases/tag/v1.0.0) — production ready

## Contributions to AI ecosystem

- PR [#2 12britz/awesome-ai-gateways](https://github.com/12britz/awesome-ai-gateways/pull/2) — Add Brainiall to Managed Services
- PR [#450 tensorchord/Awesome-LLMOps](https://github.com/tensorchord/Awesome-LLMOps/pull/450) — Add Brainiall LLM gateway

## Contact

- Email: fabio@brainiall.com
- App support: support@brainiall.com

---

*Brainiall is independently bootstrapped. Built in 🇧🇷 with 🇪🇺 hosting.*
