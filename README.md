# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-08T21:30:53Z_

## Models

| Lane | Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|---|
| groq | `qwen/qwen3.8-27b` | **active** | 171ms | ctx 131k, tools, reasoning | 2026-10-08 |
| nvidia | `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 250ms | ctx 262k, tools, reasoning | 2026-10-08 |
| mistral | `ministral-8b-latest` | **active** | 382ms | ctx 262k, tools | 2026-10-08 |
| zai | `glm-4.7-flash` | **dead** | — | ctx 200k, tools, reasoning | 2026-10-08 |
| ollama | `gpt-oss:120b` | **active** | 360ms | — | 2026-10-08 |
| cohere | `command-r7b-12-2024` | **deprecated** | 216ms | ctx 128k, tools | 2026-10-08 |
| openrouter | `apodex/apodex-1.1-mini:free` | **active** | 1092ms | ctx 262k, tools, reasoning | 2026-10-08 |

## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
2. `ministral-8b-latest` (mistral) — 262,144 tokens
3. `apodex/apodex-1.1-mini:free` (openrouter) — 262,144 tokens
4. `qwen/qwen3.8-27b` (groq) — 131,042 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 171ms probe
2. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 250ms probe
3. `gpt-oss:120b` (ollama) — 360ms probe
4. `ministral-8b-latest` (mistral) — 382ms probe
5. `apodex/apodex-1.1-mini:free` (openrouter) — 1092ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
2. `ministral-8b-latest` (mistral) — 262k ctx
3. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
4. `qwen/qwen3.8-27b` (groq) — 131k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
2. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
3. `qwen/qwen3.8-27b` (groq) — 131k ctx

**Vision (image input)** (ranked):
1. `ministral-8b-latest` (mistral) — 262k ctx
2. `qwen/qwen3.8-27b` (groq) — 131k ctx

_Not covered by any current lane: video generation, audio generation, embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip probing — no point calling a corpse.
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
