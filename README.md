# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-24T23:25:39Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-24 |
| `openai/gpt-oss-120b` | **active** | 235ms | ctx 131k, tools, reasoning | 2026-11-24 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-24 |
| `allam-2-7b` | **active** | 252ms | ctx 4k | 2026-11-24 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-24 |
| `qwen/qwen3.8-27b` | **active** | 223ms | ctx 131k, tools, reasoning, vision | 2026-11-24 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-24 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-24 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-24 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-24 |
| `openai/gpt-oss-20b` | **active** | 194ms | ctx 131k, tools, reasoning | 2026-11-24 |

</details>

<details><summary><b>nvidia</b> — 9/30 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-24 |
| `fastino/gliner2-pii` | **not-chat** | — | — | 2026-11-24 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-24 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-24 |
| `minimaxai/minimax-m3.1-flash` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-24 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 529ms | ctx 1000k | 2026-11-24 |
| `moonshotai/kimi-k3.1-pro` | **active** | 20912ms | ctx 1048k, tools, reasoning, vision | 2026-11-24 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-24 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-24 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-24 |
| `nvidia/ising-calibration-1.5-31b` | **dead** | — | — | 2026-11-24 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-24 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-24 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-24 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-24 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 130ms | ctx 256k, tools, reasoning, vision | 2026-11-24 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 415ms | ctx 1000k, tools, reasoning | 2026-11-24 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 241ms | — | 2026-11-24 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-24 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-24 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-24 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 116ms | ctx 262k, tools, reasoning | 2026-11-24 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 17546ms | ctx 1048k, tools, reasoning, vision | 2026-11-24 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-24 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-24 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 9666ms | — | 2026-11-24 |
| `poolside/laguna-xs-2.1` | **active** | 77ms | ctx 262k, tools, reasoning | 2026-11-24 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-24 |
| `stepfun-ai/step-5-preview` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-24 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-24 |

</details>

<details><summary><b>mistral</b> — 10/51 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 338ms | ctx 256k, tools | 2026-11-24 |
| `codestral-latest` | **active** | 318ms | ctx 256k, tools | 2026-11-24 |
| `mistral-code-latest` | **rate-limited** | — | — | 2026-11-24 |
| `mistral-code-fim-latest` | **rate-limited** | — | — | 2026-11-24 |
| `ministral-14b-2512` | **active** | 310ms | ctx 262k, tools, vision | 2026-11-24 |
| `ministral-14b-latest` | **active** | 305ms | ctx 262k, tools, vision | 2026-11-24 |
| `ministral-3b-2512` | **active** | 304ms | ctx 131k, tools, vision | 2026-11-24 |
| `ministral-3b-latest` | **active** | 444ms | ctx 131k, tools, vision | 2026-11-24 |
| `ministral-8b-2512` | **active** | 379ms | ctx 262k, tools, vision | 2026-11-24 |
| `ministral-8b-latest` | **active** | 359ms | ctx 262k, tools, vision | 2026-11-24 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-24 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-24 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-24 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-24 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-24 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-24 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-24 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-24 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-24 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-24 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-24 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-24 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-24 |
| `voxtral-small-2507` | **active** | 311ms | ctx 32k, tools | 2026-11-24 |
| `voxtral-small-latest` | **active** | 523ms | ctx 32k, tools | 2026-11-24 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-24 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-24 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-24 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-24 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-24 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-24 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-24 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-24 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-24 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-24 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-24 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-24 |

</details>

<details><summary><b>zai</b> — 0/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-11-24 |
| `glm-4.5-flash` | **rate-limited** | — | ctx 131k, tools, reasoning | 2026-11-24 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-11-24 |

</details>

<details><summary><b>ollama</b> — 0/25 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-24 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-24 |
| `gpt-oss:120b` | **dead** | — | — | 2026-11-24 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-24 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-24 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-24 |
| `nemotron-3-ultra` | **dead** | — | — | 2026-11-24 |
| `muse-spark-open` | **dead** | — | — | 2026-11-24 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-24 |
| `nemotron-3-super` | **dead** | — | — | 2026-11-24 |
| `beam` | **dead** | — | — | 2026-11-24 |
| `gpt-oss:20b` | **dead** | — | — | 2026-11-24 |
| `glm-5.3` | **dead** | — | — | 2026-11-24 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-24 |
| `inkling-2-small` | **dead** | — | — | 2026-11-24 |
| `minimax-m3` | **dead** | — | — | 2026-11-24 |
| `kimi-k3.1-pro` | **dead** | — | ctx 1048k | 2026-11-24 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-24 |
| `gemma4:31b` | **dead** | — | — | 2026-11-24 |
| `mistral-large-4` | **dead** | — | ctx 1000k | 2026-11-24 |
| `clef:27b` | **not-chat** | — | — | 2026-11-24 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-24 |
| `glm-5.2` | **dead** | — | — | 2026-11-24 |
| `hy4` | **dead** | — | — | 2026-11-24 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-24 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 216ms | ctx 128k, tools | 2026-11-24 |

</details>

<details><summary><b>openrouter</b> — 2/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `inclusionai/ling-3.2-flash:free` | **rate-limited** | — | ctx 1048k, tools, reasoning, vision | 2026-11-24 |
| `baidu/ernie-5.5-flash-preview:free` | **active** | 1966ms | ctx 1024k, tools, reasoning | 2026-11-24 |
| `liquid/lfm-3-1.7b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-24 |
| `particle-ai/particle-1:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-24 |
| `recursive/flint-v1.0:free` | **active** | 277ms | ctx 262k, tools, reasoning | 2026-11-24 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-24 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-24 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-24 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-24 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-24 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-24 |

</details>

<details><summary><b>llm7</b> — 3/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-24 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-11-24 |
| `codestral-latest` | **active** | 426ms | — | 2026-11-24 |
| `gemma4:31b` | **dead** | — | — | 2026-11-24 |
| `glm-5.2` | **dead** | — | — | 2026-11-24 |
| `gpt-oss:20b` | **active** | 907ms | — | 2026-11-24 |
| `minimax-m2.7` | **not-chat** | — | — | 2026-11-24 |
| `minimax-m3` | **dead** | — | — | 2026-11-24 |
| `mistral-Nemo-Instruct-2407` | **active** | 296ms | — | 2026-11-24 |
| `nemotron-3-nano:30b` | **not-chat** | — | — | 2026-11-24 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `moonshotai/kimi-k3.1-pro` (nvidia) — 1,048,576 tokens
2. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1,024,000 tokens
4. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 1,000,000 tokens
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
7. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
8. `ministral-14b-2512` (mistral) — 262,144 tokens
9. `ministral-14b-latest` (mistral) — 262,144 tokens
10. `ministral-8b-2512` (mistral) — 262,144 tokens
11. `ministral-8b-latest` (mistral) — 262,144 tokens
12. `recursive/flint-v1.0:free` (openrouter) — 262,144 tokens
13. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
14. `codestral-2508` (mistral) — 256,000 tokens
15. `codestral-latest` (mistral) — 256,000 tokens
16. `openai/gpt-oss-120b` (groq) — 131,072 tokens
17. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
18. `openai/gpt-oss-20b` (groq) — 131,072 tokens
19. `ministral-3b-2512` (mistral) — 131,072 tokens
20. `ministral-3b-latest` (mistral) — 131,072 tokens
21. `voxtral-small-2507` (mistral) — 32,768 tokens
22. `voxtral-small-latest` (mistral) — 32,768 tokens
23. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `poolside/laguna-xs-2.1` (nvidia) — 77ms probe
2. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 116ms probe
3. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 130ms probe
4. `openai/gpt-oss-20b` (groq) — 194ms probe
5. `qwen/qwen3.8-27b` (groq) — 223ms probe
6. `openai/gpt-oss-120b` (groq) — 235ms probe
7. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 241ms probe
8. `allam-2-7b` (groq) — 252ms probe
9. `recursive/flint-v1.0:free` (openrouter) — 277ms probe
10. `mistral-Nemo-Instruct-2407` (llm7) — 296ms probe
11. `ministral-3b-2512` (mistral) — 304ms probe
12. `ministral-14b-latest` (mistral) — 305ms probe
13. `ministral-14b-2512` (mistral) — 310ms probe
14. `voxtral-small-2507` (mistral) — 311ms probe
15. `codestral-latest` (mistral) — 318ms probe
16. `codestral-2508` (mistral) — 338ms probe
17. `ministral-8b-latest` (mistral) — 359ms probe
18. `ministral-8b-2512` (mistral) — 379ms probe
19. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 415ms probe
20. `codestral-latest` (llm7) — 426ms probe
21. `ministral-3b-latest` (mistral) — 444ms probe
22. `voxtral-small-latest` (mistral) — 523ms probe
23. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 529ms probe
24. `gpt-oss:20b` (llm7) — 907ms probe
25. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1966ms probe
26. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 9666ms probe
27. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 17546ms probe
28. `moonshotai/kimi-k3.1-pro` (nvidia) — 20912ms probe

**Tool calling** (ranked):
1. `moonshotai/kimi-k3.1-pro` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
6. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
7. `ministral-14b-2512` (mistral) — 262k ctx
8. `ministral-14b-latest` (mistral) — 262k ctx
9. `ministral-8b-2512` (mistral) — 262k ctx
10. `ministral-8b-latest` (mistral) — 262k ctx
11. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
13. `codestral-2508` (mistral) — 256k ctx
14. `codestral-latest` (mistral) — 256k ctx
15. `openai/gpt-oss-120b` (groq) — 131k ctx
16. `qwen/qwen3.8-27b` (groq) — 131k ctx
17. `openai/gpt-oss-20b` (groq) — 131k ctx
18. `ministral-3b-2512` (mistral) — 131k ctx
19. `ministral-3b-latest` (mistral) — 131k ctx
20. `voxtral-small-2507` (mistral) — 32k ctx
21. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `moonshotai/kimi-k3.1-pro` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
6. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
7. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
8. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
9. `openai/gpt-oss-120b` (groq) — 131k ctx
10. `qwen/qwen3.8-27b` (groq) — 131k ctx
11. `openai/gpt-oss-20b` (groq) — 131k ctx

**Vision (image input)** (ranked):
1. `moonshotai/kimi-k3.1-pro` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
3. `ministral-14b-2512` (mistral) — 262k ctx
4. `ministral-14b-latest` (mistral) — 262k ctx
5. `ministral-8b-2512` (mistral) — 262k ctx
6. `ministral-8b-latest` (mistral) — 262k ctx
7. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
8. `qwen/qwen3.8-27b` (groq) — 131k ctx
9. `ministral-3b-2512` (mistral) — 131k ctx
10. `ministral-3b-latest` (mistral) — 131k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Lane quotas (daily snapshot)

Where each lane stands on its free allowance. Quota comes from rate-limit headers captured off the probe responses (zero extra requests), except OpenRouter which needs one daily call to its key endpoint. Keys never leave the private verifier repo; only aggregate remaining counts are published here.

| Lane | Source | Requests remaining | Request limit | Reset / note |
|---|---|---|---|---|
| groq | response-headers | 999 | 1000 | resets in 1m26.4s |
| nvidia | none | — | — | no quota API; dashboard only |
| mistral | response-headers | 58 | 60 |  |
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
