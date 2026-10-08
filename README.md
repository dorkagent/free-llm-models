# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-08T21:09:09Z_

## Models

| Lane | Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|---|
| groq | `qwen/qwen3.8-27b` | **active** | 222ms | ctx 131k, tools, reasoning | 2026-10-08 |
| nvidia | `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 4491ms | ctx 262k, tools, reasoning | 2026-10-08 |
| mistral | `ministral-8b-latest` | **active** | 397ms | ctx 262k, tools | 2026-10-08 |
| zai | `glm-4.7-flash` | **active** | 1565ms | ctx 200k, tools, reasoning | 2026-10-08 |
| ollama | `gpt-oss:120b` | **active** | 570ms | — | 2026-10-08 |
| cohere | `command-r7b-12-2024` | **deprecated** | 310ms | ctx 128k, tools | 2026-10-08 |
| openrouter | `apodex/apodex-1.1-mini:free` | **active** | 1234ms | ctx 262k, tools, reasoning | 2026-10-08 |

## Right model for the right job (verified-active only)

- **Largest context**: `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
- **Fastest response**: `qwen/qwen3.8-27b` (groq) — 222ms probe
- **Tool calling**: `qwen/qwen3.8-27b` (groq), `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia), `ministral-8b-latest` (mistral), `glm-4.7-flash` (zai), `apodex/apodex-1.1-mini:free` (openrouter)
- **Reasoning**: `qwen/qwen3.8-27b` (groq), `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia), `glm-4.7-flash` (zai), `apodex/apodex-1.1-mini:free` (openrouter)

## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip probing — no point calling a corpse.
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
