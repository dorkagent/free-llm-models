# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-08T20:57:57Z_

## Models

| Lane | Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|---|
| groq | `qwen/qwen3.8-27b` | **active** | 185ms | — | 2026-10-08 |
| nvidia | `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 253ms | — | 2026-10-08 |
| mistral | `ministral-8b-latest` | **active** | 349ms | — | 2026-10-08 |
| zai | `glm-4.7-flash` | **dead** | — | — | 2026-10-08 |
| ollama | `gpt-oss:120b` | **active** | 428ms | — | 2026-10-08 |
| cohere | `command-r7b-12-2024` | **deprecated** | 255ms | modality=['text'], context_window=128000, max_output_tokens=4000, open_weight=True, status=ga | 2026-10-08 |
| openrouter | `apodex/apodex-1.1-mini:free` | **active** | 699ms | — | 2026-10-08 |

## Capability leaders (among verified-active models)

_No active models with capability data right now._

## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip probing — no point calling a corpse.
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
