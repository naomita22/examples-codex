# Free Codex CLI Setup — FHRouter

Point [Codex CLI](https://fhrouter.com/docs/guides/codex) at FHRouter and use free frontier models. One config file.

> **Free tier:** frontier AI models (Grok, DeepSeek, GLM) free on every [FHRouter](https://fhrouter.com) account — no credit card. [Free LLM API](https://fhrouter.com/free-llm-api) · [How free models work](https://fhrouter.com/docs/free-models)

## Setup

1. Edit `~/.codex/config.toml` (see [`config.toml`](config.toml) in this repo).
2. Put your FHRouter key from https://fhrouter.com/token into `~/.codex/auth.json` as `OPENAI_API_KEY` (see [`auth.json`](auth.json)).
3. Run `codex` and send a test message.

Full guide with troubleshooting: [https://fhrouter.com/docs/guides/codex](https://fhrouter.com/docs/guides/codex).

The gateway serves the OpenAI Responses wire API at `https://fhrouter.com/v1`; models like `gpt-5.5` run at up to 50% below list, and the [free tier](https://fhrouter.com/free-llm-api) includes frontier models like `grok-4.6` on every account.

## Links

- [FHRouter](https://fhrouter.com) — the gateway
- [Free LLM API](https://fhrouter.com/free-llm-api) — the free tier
- [Docs](https://fhrouter.com/docs) · [API reference](https://fhrouter.com/docs/api-reference) · [Blog](https://fhrouter.com/blog)
- Setup guides: [Claude Code](https://fhrouter.com/docs/guides/claude-code) · [Codex CLI](https://fhrouter.com/docs/guides/codex) · [Gemini CLI](https://fhrouter.com/docs/guides/gemini)

---

<sub>Examples only — FHRouter itself runs at [fhrouter.com](https://fhrouter.com). Sign up and start calling frontier models for free in minutes.</sub>
