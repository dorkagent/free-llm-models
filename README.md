# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-27T22:35:01Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `allam-2-7b` | **active** | 272ms | ctx 4k | 2026-11-27 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-27 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-27 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-27 |
| `openai/gpt-oss-20b` | **active** | 269ms | ctx 131k, tools, reasoning | 2026-11-27 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-27 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-27 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-27 |
| `openai/gpt-oss-120b` | **active** | 220ms | ctx 131k, tools, reasoning | 2026-11-27 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-27 |
| `qwen/qwen3.8-27b` | **active** | 204ms | ctx 131k, tools, reasoning, vision | 2026-11-27 |

</details>

<details><summary><b>nvidia</b> — 11/30 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-27 |
| `fastino/gliner2-pii` | **not-chat** | — | — | 2026-11-27 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-27 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-27 |
| `minimaxai/minimax-m3.1-flash` | **active** | 1822ms | ctx 262k, tools, reasoning, vision | 2026-11-27 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 10577ms | ctx 1000k | 2026-11-27 |
| `moonshotai/kimi-k3.1-pro` | **active** | 28317ms | ctx 1048k | 2026-11-27 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-27 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-27 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-27 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 2582ms | — | 2026-11-27 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-27 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-27 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-27 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-27 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 233ms | ctx 256k, tools, reasoning, vision | 2026-11-27 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 416ms | ctx 1000k, tools, reasoning | 2026-11-27 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 290ms | — | 2026-11-27 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-27 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-27 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-27 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 321ms | ctx 262k, tools, reasoning | 2026-11-27 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 330ms | ctx 1048k, tools, reasoning, vision | 2026-11-27 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-27 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-27 |
| `nvidia/riva-translate-4b-instruct-v2` | **dead** | — | — | 2026-11-27 |
| `poolside/laguna-xs-2.1` | **active** | 219ms | ctx 262k, tools, reasoning | 2026-11-27 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-27 |
| `stepfun-ai/step-5-preview` | **active** | 795ms | ctx 1048k, tools, reasoning, vision | 2026-11-27 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-27 |

</details>

<details><summary><b>mistral</b> — 0/51 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **dead** | — | ctx 256k, tools | 2026-11-27 |
| `codestral-latest` | **dead** | — | ctx 256k, tools | 2026-11-27 |
| `mistral-code-latest` | **dead** | — | — | 2026-11-27 |
| `mistral-code-fim-latest` | **dead** | — | — | 2026-11-27 |
| `ministral-14b-2512` | **dead** | — | ctx 262k, tools, vision | 2026-11-27 |
| `ministral-14b-latest` | **dead** | — | ctx 262k, tools, vision | 2026-11-27 |
| `ministral-3b-2512` | **dead** | — | ctx 131k, tools, vision | 2026-11-27 |
| `ministral-3b-latest` | **dead** | — | ctx 131k, tools, vision | 2026-11-27 |
| `ministral-8b-2512` | **dead** | — | ctx 262k, tools, vision | 2026-11-27 |
| `ministral-8b-latest` | **dead** | — | ctx 262k, tools, vision | 2026-11-27 |
| `mistral-medium-latest` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-27 |
| `mistral-medium` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-27 |
| `mistral-medium-3-5` | **dead** | — | — | 2026-11-27 |
| `mistral-medium-3.5` | **dead** | — | — | 2026-11-27 |
| `mistral-medium-3` | **dead** | — | — | 2026-11-27 |
| `mistral-medium-2604` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-27 |
| `mistral-vibe-cli-latest` | **dead** | — | — | 2026-11-27 |
| `mistral-vibe-cli-with-tools` | **dead** | — | — | 2026-11-27 |
| `magistral-medium-latest` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-27 |
| `mistral-small-2603` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-27 |
| `mistral-small-latest` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-27 |
| `mistral-vibe-cli-fast` | **dead** | — | — | 2026-11-27 |
| `magistral-small-latest` | **dead** | — | — | 2026-11-27 |
| `voxtral-small-2507` | **dead** | — | ctx 32k, tools | 2026-11-27 |
| `voxtral-small-latest` | **dead** | — | ctx 32k, tools | 2026-11-27 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-27 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-27 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-27 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-27 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-27 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-27 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-27 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-27 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-27 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-27 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-27 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-27 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 871ms | ctx 200k, tools, reasoning | 2026-11-27 |
| `glm-4.5-flash` | **active** | 661ms | ctx 131k, tools, reasoning | 2026-11-27 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-11-27 |

</details>

<details><summary><b>ollama</b> — 0/25 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `muse-spark-open` | **dead** | — | — | 2026-11-27 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-27 |
| `nemotron-3-ultra` | **dead** | — | — | 2026-11-27 |
| `mistral-large-4` | **dead** | — | ctx 1000k | 2026-11-27 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-27 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-27 |
| `gpt-oss:20b` | **dead** | — | — | 2026-11-27 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-27 |
| `inkling-2-small` | **dead** | — | — | 2026-11-27 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-27 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-27 |
| `glm-5.3` | **dead** | — | — | 2026-11-27 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-27 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-27 |
| `gemma4:31b` | **dead** | — | — | 2026-11-27 |
| `nemotron-3-super` | **dead** | — | — | 2026-11-27 |
| `beam` | **dead** | — | — | 2026-11-27 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-27 |
| `minimax-m3` | **dead** | — | — | 2026-11-27 |
| `clef:27b` | **not-chat** | — | — | 2026-11-27 |
| `glm-5.2` | **dead** | — | — | 2026-11-27 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-27 |
| `hy4` | **dead** | — | — | 2026-11-27 |
| `kimi-k3.1-pro` | **dead** | — | ctx 1048k | 2026-11-27 |
| `gpt-oss:120b` | **dead** | — | — | 2026-11-27 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 186ms | ctx 128k, tools | 2026-11-27 |

</details>

<details><summary><b>openrouter</b> — 2/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `baidu/ernie-5.5-flash-preview:free` | **active** | 1000ms | ctx 1024k, tools, reasoning | 2026-11-27 |
| `liquid/lfm-3-1.7b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-27 |
| `particle-ai/particle-1:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-27 |
| `recursive/flint-v1.0:free` | **active** | 518ms | ctx 262k, tools, reasoning | 2026-11-27 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-27 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-27 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-27 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-27 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-27 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-27 |

</details>

<details><summary><b>llm7</b> — 2/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-27 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-11-27 |
| `codestral-latest` | **active** | 213ms | — | 2026-11-27 |
| `gemma4:31b` | **dead** | — | — | 2026-11-27 |
| `glm-5.2` | **dead** | — | — | 2026-11-27 |
| `gpt-oss:20b` | **active** | 837ms | — | 2026-11-27 |
| `minimax-m2.7` | **not-chat** | — | — | 2026-11-27 |
| `minimax-m3` | **dead** | — | — | 2026-11-27 |
| `mistral-Nemo-Instruct-2407` | **not-chat** | — | — | 2026-11-27 |
| `nemotron-3-nano:30b` | **not-chat** | — | — | 2026-11-27 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `moonshotai/kimi-k3.1-pro` (nvidia) — 1,048,576 tokens
2. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
3. `stepfun-ai/step-5-preview` (nvidia) — 1,048,576 tokens
4. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1,024,000 tokens
5. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 1,000,000 tokens
6. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262,144 tokens
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
9. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
10. `recursive/flint-v1.0:free` (openrouter) — 262,144 tokens
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
12. `glm-4.7-flash` (zai) — 200,000 tokens
13. `openai/gpt-oss-20b` (groq) — 131,072 tokens
14. `openai/gpt-oss-120b` (groq) — 131,072 tokens
15. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
16. `glm-4.5-flash` (zai) — 131,072 tokens
17. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 204ms probe
2. `codestral-latest` (llm7) — 213ms probe
3. `poolside/laguna-xs-2.1` (nvidia) — 219ms probe
4. `openai/gpt-oss-120b` (groq) — 220ms probe
5. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 233ms probe
6. `openai/gpt-oss-20b` (groq) — 269ms probe
7. `allam-2-7b` (groq) — 272ms probe
8. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 290ms probe
9. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 321ms probe
10. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 330ms probe
11. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 416ms probe
12. `recursive/flint-v1.0:free` (openrouter) — 518ms probe
13. `glm-4.5-flash` (zai) — 661ms probe
14. `stepfun-ai/step-5-preview` (nvidia) — 795ms probe
15. `gpt-oss:20b` (llm7) — 837ms probe
16. `glm-4.7-flash` (zai) — 871ms probe
17. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1000ms probe
18. `minimaxai/minimax-m3.1-flash` (nvidia) — 1822ms probe
19. `nvidia/ising-calibration-1.5-31b` (nvidia) — 2582ms probe
20. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 10577ms probe
21. `moonshotai/kimi-k3.1-pro` (nvidia) — 28317ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
8. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
9. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
10. `glm-4.7-flash` (zai) — 200k ctx
11. `openai/gpt-oss-20b` (groq) — 131k ctx
12. `openai/gpt-oss-120b` (groq) — 131k ctx
13. `qwen/qwen3.8-27b` (groq) — 131k ctx
14. `glm-4.5-flash` (zai) — 131k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
8. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
9. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
10. `glm-4.7-flash` (zai) — 200k ctx
11. `openai/gpt-oss-20b` (groq) — 131k ctx
12. `openai/gpt-oss-120b` (groq) — 131k ctx
13. `qwen/qwen3.8-27b` (groq) — 131k ctx
14. `glm-4.5-flash` (zai) — 131k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
4. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
5. `qwen/qwen3.8-27b` (groq) — 131k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Lane quotas (daily snapshot)

Where each lane stands on its free allowance. Quota comes from rate-limit headers captured off the probe responses (zero extra requests), except OpenRouter which needs one daily call to its key endpoint. Keys never leave the private verifier repo; only aggregate remaining counts are published here.

| Lane | Source | Requests remaining | Request limit | Reset / note |
|---|---|---|---|---|
| groq | response-headers | 999 | 1000 | resets in 1m26.4s |
| nvidia | none | — | — | no quota API; dashboard only |
| mistral | response-headers | 0 | 0 |  |
| zai | none | — | — | no quota API; console only |
| ollama | none | — | — | no quota API; settings page only |
| cohere | none | — | — | no documented quota endpoint |
| openrouter | key-endpoint | 100 | 100 | used today: 0 |
| llm7 | none | — | — | no quota endpoint; /v1/models shows tiers only (verified 2026-10-09) |


## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip the official probe, but a shadow probe still runs daily to audit feed accuracy (see above).
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
