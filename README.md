# Hi 👋 I'm Fabio Suizu

Building **[Brainiall](https://chat.brainiall.com)** — an OpenAI-compatible AI gateway.

## What is Brainiall?

**104 AI models** through a single OpenAI-compatible API:

- **60+ chat models** — Claude 4.7, GPT-5, Gemini 3 Pro, Llama 4 Maverick, DeepSeek R1, Mistral, Qwen
- **12 image models** — gpt-5-image-2, Flux 2, Seedream 4.5, Imagen 4
- **5 video models** — Seedance 2.0, Veo 3, Kling 2.1
- **6 voice models** — Brainiall TTS, Voice Clone, Whisper

**$5.99/mo flat** — predictable cost, no per-token surprises.

**EU-hosted** (Frankfurt + Madrid) — GDPR Art 28 DPA + AI Act Article 50 compliant.

**Free 7-day Pro trial** — no credit card required.

→ [chat.brainiall.com](https://chat.brainiall.com)

## Quick start

Drop-in OpenAI SDK replacement (1 line):

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
| Payment Brasil | **PIX + Boleto + Card** | Card only | Card only | Card only |

## Resources

- 🌐 **App**: [chat.brainiall.com](https://chat.brainiall.com)
- 🔌 **API**: [api.brainiall.com](https://api.brainiall.com)
- 💰 **Pricing**: [chat.brainiall.com/pricing](https://chat.brainiall.com/pricing)
- 📚 **Models catalog**: [chat.brainiall.com/best-llm-2026](https://chat.brainiall.com/best-llm-2026)
- 🎨 **Use cases by industry**: [chat.brainiall.com/llm-for-developers](https://chat.brainiall.com/llm-for-developers), [/llm-for-startups](https://chat.brainiall.com/llm-for-startups), [/llm-for-legal](https://chat.brainiall.com/llm-for-legal)
- 🌍 **i18n**: PT-BR · EN · ES · DE · FR · JA · AR (RTL)

## Open source

- [brainiall-llm-gateway](https://github.com/fasuizu-br/brainiall-llm-gateway) — gateway integration docs + cURL examples

## Contact

- Email: fabio@brainiall.com
- App support: support@brainiall.com

---

*Brainiall is independently bootstrapped. Built in 🇧🇷 with 🇪🇺 hosting.*
