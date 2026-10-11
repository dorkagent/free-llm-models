# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-11T14:14:28Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-11 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-11 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-11 |
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-11 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-11 |
| `openai/gpt-oss-120b` | **active** | 332ms | ctx 131k, tools, reasoning | 2026-10-11 |
| `openai/gpt-oss-20b` | **active** | 251ms | ctx 131k, tools, reasoning | 2026-10-11 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-11 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-11 |
| `qwen/qwen3.8-27b` | **active** | 81ms | ctx 131k, tools, reasoning, vision | 2026-10-11 |
| `allam-2-7b` | **active** | 297ms | ctx 4k | 2026-10-11 |

</details>

<details><summary><b>nvidia</b> — 10/80 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-11 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-11 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-11 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-11 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-11 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-11 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-11 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-11 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-11 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-11 |
| `google/deplot` | **dead** | — | — | 2026-10-11 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 744ms | ctx 250k, tools, reasoning, vision | 2026-10-11 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-11 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-11 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-11 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-11 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-11 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-11 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-11 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-11 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-11 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-11 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 12225ms | ctx 128k, tools, vision | 2026-10-11 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-11 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-11 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-11 |
| `meta/muse-glimmer-30b` | **active** | 4560ms | ctx 131k, tools, reasoning, vision | 2026-10-11 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-11 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-11 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-11 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-11 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-11 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-11 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-11 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-11 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-11 |
| `moonshotai/kimi-k3` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-11 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-11 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-11 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-11 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-11 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 405ms | — | 2026-10-11 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-11 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-11 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-11 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-11 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-11 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-11 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-11 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-11 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-11 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-11 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-11 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-11 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-11 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 368ms | ctx 262k, tools, reasoning | 2026-10-11 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 520ms | ctx 1000k, tools, reasoning | 2026-10-11 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-11 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 584ms | ctx 262k, tools, reasoning | 2026-10-11 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-11 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-11 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-11 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-11 |
| `nvidia/nemotron-parse-2.0` | **dead** | — | — | 2026-10-11 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-11 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-11 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-11 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-11 |
| `nvidia/riva-translate-4b-instruct-v2` | **dead** | — | — | 2026-10-11 |
| `nvidia/vila` | **dead** | — | — | 2026-10-11 |
| `openai/gpt-oss-20b` | **active** | 190ms | ctx 131k, tools, reasoning | 2026-10-11 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-11 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-11 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-11 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-11 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-11 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-11 |
| `z-ai/glm-5.3` | **active** | 582ms | ctx 1000k, tools, reasoning | 2026-10-11 |
| `z-ai/glm-5.3-flash` | **active** | 15664ms | ctx 1000k, tools, reasoning, vision | 2026-10-11 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-11 |

</details>

<details><summary><b>mistral</b> — 12/46 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 384ms | ctx 256k, tools | 2026-10-11 |
| `codestral-latest` | **active** | 347ms | ctx 256k, tools | 2026-10-11 |
| `mistral-code-latest` | **active** | 352ms | — | 2026-10-11 |
| `mistral-code-fim-latest` | **active** | 371ms | — | 2026-10-11 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-11 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-11 |
| `ministral-14b-2512` | **active** | 309ms | ctx 262k, tools, vision | 2026-10-11 |
| `ministral-14b-latest` | **active** | 359ms | — | 2026-10-11 |
| `ministral-3b-2512` | **active** | 881ms | ctx 131k, tools, vision | 2026-10-11 |
| `ministral-3b-latest` | **active** | 306ms | ctx 131k, tools, vision | 2026-10-11 |
| `ministral-8b-2512` | **active** | 1302ms | ctx 262k, tools, vision | 2026-10-11 |
| `ministral-8b-latest` | **active** | 303ms | ctx 262k, tools, vision | 2026-10-11 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-11 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-11 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-11 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-11 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-11 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-11 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-11 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-11 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-11 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-11 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-11 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-11 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-11 |
| `voxtral-small-2507` | **active** | 324ms | ctx 32k, tools | 2026-10-11 |
| `voxtral-small-latest` | **active** | 330ms | ctx 32k, tools | 2026-10-11 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-11 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-11 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-11 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-11 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-11 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-11 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-11 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-11 |
| `mistral-ocr-4-0` | **not-chat** | — | — | 2026-10-11 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-11 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-11 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-11 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-11 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-11 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-11 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-11 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-11 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-11 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-11 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-10-11 |
| `glm-4.5-flash` | **active** | 998ms | ctx 131k, tools, reasoning | 2026-10-11 |
| `glm-4.6v-flash` | **active** | 2243ms | ctx 128k, tools, reasoning, vision | 2026-10-11 |

</details>

<details><summary><b>ollama</b> — 6/18 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `mistral-large-4` | **dead** | — | — | 2026-10-11 |
| `nemotron-3-ultra` | **active** | 805ms | — | 2026-10-11 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-11 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-11 |
| `glm-5.3` | **dead** | — | — | 2026-10-11 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-11 |
| `gpt-oss:20b` | **active** | 634ms | — | 2026-10-11 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-11 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-11 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-11 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-11 |
| `gpt-oss:120b` | **active** | 500ms | — | 2026-10-11 |
| `nemotron-3-nano:30b` | **active** | 398ms | — | 2026-10-11 |
| `nemotron-3-super` | **active** | 556ms | — | 2026-10-11 |
| `glm-5.2` | **dead** | — | — | 2026-10-11 |
| `minimax-m3` | **dead** | — | — | 2026-10-11 |
| `gemma4:31b` | **active** | 439ms | — | 2026-10-11 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-11 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 230ms | ctx 128k, tools | 2026-10-11 |

</details>

<details><summary><b>openrouter</b> — 4/15 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `apodex/apodex-1.1-mini:free` | **active** | 853ms | ctx 262k, tools, reasoning | 2026-10-11 |
| `dots-studio/dots-3-note-preview:free` | **active** | 1246ms | ctx 512k, tools, reasoning, vision | 2026-10-11 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-11 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-11 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-11 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-11 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-11 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-11 |
| `cohere/north-mini-code:free` | **active** | 267ms | ctx 256k, tools, reasoning | 2026-10-11 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-11 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-11 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-11 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-11 |
| `google/gemma-4-31b-it:free` | **active** | 520ms | ctx 262k, tools, reasoning, vision | 2026-10-11 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-11 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-11 |
| `GLM-5.3-Flash` | **active** | 6833ms | — | 2026-10-11 |
| `codestral-latest` | **active** | 958ms | — | 2026-10-11 |
| `gemma4:31b` | **dead** | — | — | 2026-10-11 |
| `glm-5.2` | **dead** | — | — | 2026-10-11 |
| `gpt-oss:20b` | **active** | 1007ms | — | 2026-10-11 |
| `minimax-m2.7` | **not-chat** | — | — | 2026-10-11 |
| `minimax-m3` | **dead** | — | — | 2026-10-11 |
| `mistral-Nemo-Instruct-2407` | **active** | 2612ms | — | 2026-10-11 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-10-11 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
2. `z-ai/glm-5.3` (nvidia) — 1,000,000 tokens
3. `z-ai/glm-5.3-flash` (nvidia) — 1,000,000 tokens
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262,144 tokens
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
7. `ministral-14b-2512` (mistral) — 262,144 tokens
8. `ministral-8b-2512` (mistral) — 262,144 tokens
9. `ministral-8b-latest` (mistral) — 262,144 tokens
10. `apodex/apodex-1.1-mini:free` (openrouter) — 262,144 tokens
11. `google/gemma-4-31b-it:free` (openrouter) — 262,144 tokens
12. `codestral-2508` (mistral) — 256,000 tokens
13. `codestral-latest` (mistral) — 256,000 tokens
14. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
15. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
16. `openai/gpt-oss-120b` (groq) — 131,072 tokens
17. `openai/gpt-oss-20b` (groq) — 131,072 tokens
18. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
19. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
20. `ministral-3b-2512` (mistral) — 131,072 tokens
21. `ministral-3b-latest` (mistral) — 131,072 tokens
22. `glm-4.5-flash` (zai) — 131,072 tokens
23. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
24. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
25. `glm-4.6v-flash` (zai) — 128,000 tokens
26. `voxtral-small-2507` (mistral) — 32,768 tokens
27. `voxtral-small-latest` (mistral) — 32,768 tokens
28. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 81ms probe
2. `openai/gpt-oss-20b` (nvidia) — 190ms probe
3. `openai/gpt-oss-20b` (groq) — 251ms probe
4. `cohere/north-mini-code:free` (openrouter) — 267ms probe
5. `allam-2-7b` (groq) — 297ms probe
6. `ministral-8b-latest` (mistral) — 303ms probe
7. `ministral-3b-latest` (mistral) — 306ms probe
8. `ministral-14b-2512` (mistral) — 309ms probe
9. `voxtral-small-2507` (mistral) — 324ms probe
10. `voxtral-small-latest` (mistral) — 330ms probe
11. `openai/gpt-oss-120b` (groq) — 332ms probe
12. `codestral-latest` (mistral) — 347ms probe
13. `mistral-code-latest` (mistral) — 352ms probe
14. `ministral-14b-latest` (mistral) — 359ms probe
15. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 368ms probe
16. `mistral-code-fim-latest` (mistral) — 371ms probe
17. `codestral-2508` (mistral) — 384ms probe
18. `nemotron-3-nano:30b` (ollama) — 398ms probe
19. `nvidia/ising-calibration-1.5-31b` (nvidia) — 405ms probe
20. `gemma4:31b` (ollama) — 439ms probe
21. `gpt-oss:120b` (ollama) — 500ms probe
22. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 520ms probe
23. `google/gemma-4-31b-it:free` (openrouter) — 520ms probe
24. `nemotron-3-super` (ollama) — 556ms probe
25. `z-ai/glm-5.3` (nvidia) — 582ms probe
26. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 584ms probe
27. `gpt-oss:20b` (ollama) — 634ms probe
28. `google/diffusiongemma-26b-a4b-it` (nvidia) — 744ms probe
29. `nemotron-3-ultra` (ollama) — 805ms probe
30. `apodex/apodex-1.1-mini:free` (openrouter) — 853ms probe
31. `ministral-3b-2512` (mistral) — 881ms probe
32. `codestral-latest` (llm7) — 958ms probe
33. `glm-4.5-flash` (zai) — 998ms probe
34. `gpt-oss:20b` (llm7) — 1007ms probe
35. `dots-studio/dots-3-note-preview:free` (openrouter) — 1246ms probe
36. `ministral-8b-2512` (mistral) — 1302ms probe
37. `glm-4.6v-flash` (zai) — 2243ms probe
38. `mistral-Nemo-Instruct-2407` (llm7) — 2612ms probe
39. `meta/muse-glimmer-30b` (nvidia) — 4560ms probe
40. `GLM-5.3-Flash` (llm7) — 6833ms probe
41. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 12225ms probe
42. `z-ai/glm-5.3-flash` (nvidia) — 15664ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
2. `z-ai/glm-5.3` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `ministral-14b-2512` (mistral) — 262k ctx
8. `ministral-8b-2512` (mistral) — 262k ctx
9. `ministral-8b-latest` (mistral) — 262k ctx
10. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
11. `google/gemma-4-31b-it:free` (openrouter) — 262k ctx
12. `codestral-2508` (mistral) — 256k ctx
13. `codestral-latest` (mistral) — 256k ctx
14. `cohere/north-mini-code:free` (openrouter) — 256k ctx
15. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
16. `openai/gpt-oss-120b` (groq) — 131k ctx
17. `openai/gpt-oss-20b` (groq) — 131k ctx
18. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
19. `openai/gpt-oss-20b` (nvidia) — 131k ctx
20. `ministral-3b-2512` (mistral) — 131k ctx
21. `ministral-3b-latest` (mistral) — 131k ctx
22. `glm-4.5-flash` (zai) — 131k ctx
23. `qwen/qwen3.8-27b` (groq) — 131k ctx
24. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
25. `glm-4.6v-flash` (zai) — 128k ctx
26. `voxtral-small-2507` (mistral) — 32k ctx
27. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
2. `z-ai/glm-5.3` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
8. `google/gemma-4-31b-it:free` (openrouter) — 262k ctx
9. `cohere/north-mini-code:free` (openrouter) — 256k ctx
10. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
11. `openai/gpt-oss-120b` (groq) — 131k ctx
12. `openai/gpt-oss-20b` (groq) — 131k ctx
13. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
14. `openai/gpt-oss-20b` (nvidia) — 131k ctx
15. `glm-4.5-flash` (zai) — 131k ctx
16. `qwen/qwen3.8-27b` (groq) — 131k ctx
17. `glm-4.6v-flash` (zai) — 128k ctx

**Vision (image input)** (ranked):
1. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
2. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
3. `ministral-14b-2512` (mistral) — 262k ctx
4. `ministral-8b-2512` (mistral) — 262k ctx
5. `ministral-8b-latest` (mistral) — 262k ctx
6. `google/gemma-4-31b-it:free` (openrouter) — 262k ctx
7. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
8. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
9. `ministral-3b-2512` (mistral) — 131k ctx
10. `ministral-3b-latest` (mistral) — 131k ctx
11. `qwen/qwen3.8-27b` (groq) — 131k ctx
12. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
13. `glm-4.6v-flash` (zai) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (249ms) | 1 day(s) |


## Lane quotas (daily snapshot)

Where each lane stands on its free allowance. Quota comes from rate-limit headers captured off the probe responses (zero extra requests), except OpenRouter which needs one daily call to its key endpoint. Keys never leave the private verifier repo; only aggregate remaining counts are published here.

| Lane | Source | Requests remaining | Request limit | Reset / note |
|---|---|---|---|---|
| groq | response-headers | 6999 | 7000 | resets in 12.342s |
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
