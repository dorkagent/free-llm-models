# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-15T14:31:05Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-15 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-15 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-15 |
| `allam-2-7b` | **active** | 343ms | ctx 4k | 2026-10-15 |
| `qwen/qwen3.8-27b` | **active** | 100ms | ctx 131k, tools, reasoning, vision | 2026-10-15 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-15 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-15 |
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-15 |
| `openai/gpt-oss-120b` | **active** | 201ms | ctx 131k, tools, reasoning | 2026-10-15 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-15 |
| `openai/gpt-oss-20b` | **active** | 177ms | ctx 131k, tools, reasoning | 2026-10-15 |

</details>

<details><summary><b>nvidia</b> — 15/81 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-15 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-15 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-15 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-15 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-15 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-15 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-15 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-15 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-15 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-15 |
| `google/deplot` | **dead** | — | — | 2026-10-15 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 405ms | ctx 250k, tools, reasoning, vision | 2026-10-15 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-15 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-15 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-15 |
| `google/gemma-4-31b-it` | **active** | 1536ms | ctx 256k, tools, reasoning, vision | 2026-10-15 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-15 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-15 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-15 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-15 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-15 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-15 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 438ms | ctx 128k, tools, vision | 2026-10-15 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 1436ms | ctx 128k, tools, vision | 2026-10-15 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-15 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-15 |
| `meta/muse-glimmer-30b` | **active** | 827ms | ctx 131k, tools, reasoning, vision | 2026-10-15 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-15 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-15 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-15 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-15 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-15 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-15 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-15 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-15 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-15 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-15 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-15 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-15 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-15 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 408ms | — | 2026-10-15 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-15 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-15 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-15 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-15 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-15 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-15 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-15 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-15 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-15 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-15 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-15 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-15 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-15 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 362ms | — | 2026-10-15 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 663ms | ctx 1000k, tools, reasoning | 2026-10-15 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-15 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 362ms | ctx 262k, tools, reasoning | 2026-10-15 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 246ms | ctx 1048k, tools, reasoning, vision | 2026-10-15 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-15 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-15 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-15 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-15 |
| `nvidia/nemotron-parse-2.0` | **active** | 245ms | — | 2026-10-15 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-15 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-15 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-15 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-15 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 9335ms | — | 2026-10-15 |
| `nvidia/vila` | **dead** | — | — | 2026-10-15 |
| `openai/gpt-oss-20b` | **active** | 218ms | ctx 131k, tools, reasoning | 2026-10-15 |
| `poolside/laguna-xs-2.1` | **active** | 23528ms | ctx 262k, tools, reasoning | 2026-10-15 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-15 |
| `stepfun-ai/step-5-preview` | **active** | 292ms | — | 2026-10-15 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-15 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-15 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-15 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-15 |
| `z-ai/glm-5.3` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-15 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-15 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-15 |

</details>

<details><summary><b>mistral</b> — 12/45 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 1040ms | ctx 256k, tools | 2026-10-15 |
| `codestral-latest` | **active** | 363ms | ctx 256k, tools | 2026-10-15 |
| `mistral-code-latest` | **active** | 336ms | — | 2026-10-15 |
| `mistral-code-fim-latest` | **active** | 373ms | — | 2026-10-15 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-15 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-15 |
| `ministral-14b-2512` | **active** | 424ms | ctx 262k, tools, vision | 2026-10-15 |
| `ministral-14b-latest` | **active** | 652ms | — | 2026-10-15 |
| `ministral-3b-2512` | **active** | 400ms | ctx 131k, tools, vision | 2026-10-15 |
| `ministral-3b-latest` | **active** | 441ms | ctx 131k, tools, vision | 2026-10-15 |
| `ministral-8b-2512` | **active** | 400ms | ctx 262k, tools, vision | 2026-10-15 |
| `ministral-8b-latest` | **active** | 349ms | ctx 262k, tools, vision | 2026-10-15 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-15 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-15 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-15 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-15 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-15 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-15 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-15 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-15 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-15 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-15 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-15 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-15 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-15 |
| `voxtral-small-2507` | **active** | 437ms | ctx 32k, tools | 2026-10-15 |
| `voxtral-small-latest` | **active** | 375ms | ctx 32k, tools | 2026-10-15 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-15 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-15 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-15 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-15 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-15 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-15 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-15 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-15 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-15 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-15 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-15 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-15 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-15 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-15 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-15 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-15 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-15 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-15 |

</details>

<details><summary><b>zai</b> — 1/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-10-15 |
| `glm-4.5-flash` | **active** | 10348ms | ctx 131k, tools, reasoning | 2026-10-15 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-15 |

</details>

<details><summary><b>ollama</b> — 6/18 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `mistral-large-4` | **dead** | — | — | 2026-10-15 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-15 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-15 |
| `gpt-oss:20b` | **active** | 503ms | — | 2026-10-15 |
| `nemotron-3-super` | **active** | 1370ms | — | 2026-10-15 |
| `nemotron-3-ultra` | **active** | 3368ms | — | 2026-10-15 |
| `glm-5.2` | **dead** | — | — | 2026-10-15 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-15 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-15 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-15 |
| `nemotron-3-nano:30b` | **active** | 355ms | — | 2026-10-15 |
| `gemma4:31b` | **active** | 602ms | — | 2026-10-15 |
| `glm-5.3` | **dead** | — | — | 2026-10-15 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-15 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-15 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-15 |
| `gpt-oss:120b` | **active** | 507ms | — | 2026-10-15 |
| `minimax-m3` | **dead** | — | — | 2026-10-15 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 251ms | ctx 128k, tools | 2026-10-15 |

</details>

<details><summary><b>openrouter</b> — 3/14 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `dots-studio/dots-3-note-preview:free` | **active** | 5515ms | ctx 512k, tools, reasoning, vision | 2026-10-15 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-15 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-15 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-15 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-15 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-15 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-15 |
| `cohere/north-mini-code:free` | **active** | 542ms | ctx 256k, tools, reasoning | 2026-10-15 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-15 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-15 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-15 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-15 |
| `google/gemma-4-31b-it:free` | **active** | 592ms | ctx 262k, tools, reasoning, vision | 2026-10-15 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-15 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-15 |
| `GLM-5.3-Flash` | **active** | 303ms | — | 2026-10-15 |
| `codestral-latest` | **active** | 414ms | — | 2026-10-15 |
| `gemma4:31b` | **dead** | — | — | 2026-10-15 |
| `glm-5.2` | **dead** | — | — | 2026-10-15 |
| `gpt-oss:20b` | **active** | 427ms | — | 2026-10-15 |
| `minimax-m2.7` | **active** | 1965ms | — | 2026-10-15 |
| `minimax-m3` | **dead** | — | — | 2026-10-15 |
| `mistral-Nemo-Instruct-2407` | **rate-limited** | — | — | 2026-10-15 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-10-15 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
4. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
5. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
6. `ministral-14b-2512` (mistral) — 262,144 tokens
7. `ministral-8b-2512` (mistral) — 262,144 tokens
8. `ministral-8b-latest` (mistral) — 262,144 tokens
9. `google/gemma-4-31b-it:free` (openrouter) — 262,144 tokens
10. `google/gemma-4-31b-it` (nvidia) — 256,000 tokens
11. `codestral-2508` (mistral) — 256,000 tokens
12. `codestral-latest` (mistral) — 256,000 tokens
13. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
14. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
15. `openai/gpt-oss-120b` (groq) — 131,072 tokens
16. `openai/gpt-oss-20b` (groq) — 131,072 tokens
17. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
18. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
19. `ministral-3b-2512` (mistral) — 131,072 tokens
20. `ministral-3b-latest` (mistral) — 131,072 tokens
21. `glm-4.5-flash` (zai) — 131,072 tokens
22. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
23. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
24. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
25. `voxtral-small-2507` (mistral) — 32,768 tokens
26. `voxtral-small-latest` (mistral) — 32,768 tokens
27. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 100ms probe
2. `openai/gpt-oss-20b` (groq) — 177ms probe
3. `openai/gpt-oss-120b` (groq) — 201ms probe
4. `openai/gpt-oss-20b` (nvidia) — 218ms probe
5. `nvidia/nemotron-parse-2.0` (nvidia) — 245ms probe
6. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 246ms probe
7. `stepfun-ai/step-5-preview` (nvidia) — 292ms probe
8. `GLM-5.3-Flash` (llm7) — 303ms probe
9. `mistral-code-latest` (mistral) — 336ms probe
10. `allam-2-7b` (groq) — 343ms probe
11. `ministral-8b-latest` (mistral) — 349ms probe
12. `nemotron-3-nano:30b` (ollama) — 355ms probe
13. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 362ms probe
14. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 362ms probe
15. `codestral-latest` (mistral) — 363ms probe
16. `mistral-code-fim-latest` (mistral) — 373ms probe
17. `voxtral-small-latest` (mistral) — 375ms probe
18. `ministral-3b-2512` (mistral) — 400ms probe
19. `ministral-8b-2512` (mistral) — 400ms probe
20. `google/diffusiongemma-26b-a4b-it` (nvidia) — 405ms probe
21. `nvidia/ising-calibration-1.5-31b` (nvidia) — 408ms probe
22. `codestral-latest` (llm7) — 414ms probe
23. `ministral-14b-2512` (mistral) — 424ms probe
24. `gpt-oss:20b` (llm7) — 427ms probe
25. `voxtral-small-2507` (mistral) — 437ms probe
26. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 438ms probe
27. `ministral-3b-latest` (mistral) — 441ms probe
28. `gpt-oss:20b` (ollama) — 503ms probe
29. `gpt-oss:120b` (ollama) — 507ms probe
30. `cohere/north-mini-code:free` (openrouter) — 542ms probe
31. `google/gemma-4-31b-it:free` (openrouter) — 592ms probe
32. `gemma4:31b` (ollama) — 602ms probe
33. `ministral-14b-latest` (mistral) — 652ms probe
34. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 663ms probe
35. `meta/muse-glimmer-30b` (nvidia) — 827ms probe
36. `codestral-2508` (mistral) — 1040ms probe
37. `nemotron-3-super` (ollama) — 1370ms probe
38. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 1436ms probe
39. `google/gemma-4-31b-it` (nvidia) — 1536ms probe
40. `minimax-m2.7` (llm7) — 1965ms probe
41. `nemotron-3-ultra` (ollama) — 3368ms probe
42. `dots-studio/dots-3-note-preview:free` (openrouter) — 5515ms probe
43. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 9335ms probe
44. `glm-4.5-flash` (zai) — 10348ms probe
45. `poolside/laguna-xs-2.1` (nvidia) — 23528ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
5. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
6. `ministral-14b-2512` (mistral) — 262k ctx
7. `ministral-8b-2512` (mistral) — 262k ctx
8. `ministral-8b-latest` (mistral) — 262k ctx
9. `google/gemma-4-31b-it:free` (openrouter) — 262k ctx
10. `google/gemma-4-31b-it` (nvidia) — 256k ctx
11. `codestral-2508` (mistral) — 256k ctx
12. `codestral-latest` (mistral) — 256k ctx
13. `cohere/north-mini-code:free` (openrouter) — 256k ctx
14. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
15. `openai/gpt-oss-120b` (groq) — 131k ctx
16. `openai/gpt-oss-20b` (groq) — 131k ctx
17. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
18. `openai/gpt-oss-20b` (nvidia) — 131k ctx
19. `ministral-3b-2512` (mistral) — 131k ctx
20. `ministral-3b-latest` (mistral) — 131k ctx
21. `glm-4.5-flash` (zai) — 131k ctx
22. `qwen/qwen3.8-27b` (groq) — 131k ctx
23. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
24. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
25. `voxtral-small-2507` (mistral) — 32k ctx
26. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
5. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
6. `google/gemma-4-31b-it:free` (openrouter) — 262k ctx
7. `google/gemma-4-31b-it` (nvidia) — 256k ctx
8. `cohere/north-mini-code:free` (openrouter) — 256k ctx
9. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
10. `openai/gpt-oss-120b` (groq) — 131k ctx
11. `openai/gpt-oss-20b` (groq) — 131k ctx
12. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
13. `openai/gpt-oss-20b` (nvidia) — 131k ctx
14. `glm-4.5-flash` (zai) — 131k ctx
15. `qwen/qwen3.8-27b` (groq) — 131k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
3. `ministral-14b-2512` (mistral) — 262k ctx
4. `ministral-8b-2512` (mistral) — 262k ctx
5. `ministral-8b-latest` (mistral) — 262k ctx
6. `google/gemma-4-31b-it:free` (openrouter) — 262k ctx
7. `google/gemma-4-31b-it` (nvidia) — 256k ctx
8. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
9. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
10. `ministral-3b-2512` (mistral) — 131k ctx
11. `ministral-3b-latest` (mistral) — 131k ctx
12. `qwen/qwen3.8-27b` (groq) — 131k ctx
13. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
14. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (286ms) | 1 day(s) |


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
| llm7 | response-headers | — | — |  |


## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip the official probe, but a shadow probe still runs daily to audit feed accuracy (see above).
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
