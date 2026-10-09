# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-09T03:08:38Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-09 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-09 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-09 |
| `openai/gpt-oss-120b` | **active** | 301ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-09 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-09 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-09 |
| `qwen/qwen3.8-27b` | **active** | 127ms | ctx 131k, tools, reasoning, vision | 2026-10-09 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-09 |
| `openai/gpt-oss-20b` | **active** | 149ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `allam-2-7b` | **active** | 249ms | ctx 4k | 2026-10-09 |

</details>

<details><summary><b>nvidia</b> — 12/80 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-09 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-09 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-09 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-09 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-09 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-09 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-09 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-09 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-09 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-09 |
| `google/deplot` | **dead** | — | — | 2026-10-09 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 143ms | ctx 250k, tools, reasoning, vision | 2026-10-09 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-09 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-09 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-09 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-09 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-09 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-09 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-09 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-09 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-09 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-09 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 295ms | ctx 128k, tools, vision | 2026-10-09 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 1802ms | ctx 128k, tools, vision | 2026-10-09 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-09 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-09 |
| `meta/muse-glimmer-30b` | **active** | 630ms | ctx 131k, tools, reasoning, vision | 2026-10-09 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-09 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-09 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-09 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-09 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-09 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-09 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-09 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-09 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `moonshotai/kimi-k3` | **active** | 513ms | ctx 1048k, tools, reasoning, vision | 2026-10-09 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-09 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-09 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-09 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 191ms | — | 2026-10-09 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-09 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-09 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-09 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-09 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-09 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-09 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-09 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 287ms | ctx 262k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 1730ms | ctx 1000k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-09 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 201ms | ctx 262k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/nemotron-parse-2.0` | **active** | 128ms | — | 2026-10-09 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-09 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-09 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-09 |
| `nvidia/riva-translate-4b-instruct-v2` | **dead** | — | — | 2026-10-09 |
| `nvidia/vila` | **dead** | — | — | 2026-10-09 |
| `openai/gpt-oss-20b` | **active** | 528ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-09 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-09 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-09 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-09 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-09 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-09 |
| `z-ai/glm-5.3` | **active** | 617ms | ctx 1000k, tools, reasoning | 2026-10-09 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-09 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-09 |

</details>

<details><summary><b>mistral</b> — 12/46 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 279ms | ctx 256k, tools | 2026-10-09 |
| `codestral-latest` | **active** | 259ms | ctx 256k, tools | 2026-10-09 |
| `mistral-code-latest` | **active** | 270ms | — | 2026-10-09 |
| `mistral-code-fim-latest` | **active** | 316ms | — | 2026-10-09 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `ministral-14b-2512` | **active** | 374ms | ctx 262k, tools, vision | 2026-10-09 |
| `ministral-14b-latest` | **active** | 415ms | — | 2026-10-09 |
| `ministral-3b-2512` | **active** | 811ms | ctx 131k, tools, vision | 2026-10-09 |
| `ministral-3b-latest` | **active** | 253ms | ctx 131k, tools, vision | 2026-10-09 |
| `ministral-8b-2512` | **active** | 292ms | ctx 262k, tools, vision | 2026-10-09 |
| `ministral-8b-latest` | **active** | 289ms | ctx 262k, tools, vision | 2026-10-09 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-09 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-09 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-09 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-09 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-09 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-09 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-09 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-09 |
| `voxtral-small-2507` | **active** | 280ms | ctx 32k, tools | 2026-10-09 |
| `voxtral-small-latest` | **active** | 276ms | ctx 32k, tools | 2026-10-09 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-09 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-09 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-09 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-09 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-4-0` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-09 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-10-09 |
| `glm-4.5-flash` | **active** | 810ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `glm-4.6v-flash` | **active** | 946ms | ctx 128k, tools, reasoning, vision | 2026-10-09 |

</details>

<details><summary><b>ollama</b> — 6/18 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `nemotron-3-ultra` | **active** | 3954ms | — | 2026-10-09 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-09 |
| `gpt-oss:20b` | **active** | 435ms | — | 2026-10-09 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-09 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-09 |
| `mistral-large-4` | **dead** | — | — | 2026-10-09 |
| `gpt-oss:120b` | **active** | 324ms | — | 2026-10-09 |
| `gemma4:31b` | **active** | 327ms | — | 2026-10-09 |
| `glm-5.3` | **dead** | — | — | 2026-10-09 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-09 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-09 |
| `glm-5.2` | **dead** | — | — | 2026-10-09 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-09 |
| `nemotron-3-nano:30b` | **active** | 544ms | — | 2026-10-09 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-09 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-09 |
| `minimax-m3` | **dead** | — | — | 2026-10-09 |
| `nemotron-3-super` | **active** | 501ms | — | 2026-10-09 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 222ms | ctx 128k, tools | 2026-10-09 |

</details>

<details><summary><b>openrouter</b> — 2/15 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `apodex/apodex-1.1-mini:free` | **rate-limited** | — | ctx 262k, tools, reasoning | 2026-10-09 |
| `dots-studio/dots-3-note-preview:free` | **active** | 788ms | ctx 512k, tools, reasoning, vision | 2026-10-09 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-09 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-09 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-09 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-09 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-09 |
| `cohere/north-mini-code:free` | **active** | 11404ms | ctx 256k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-09 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-09 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-09 |

</details>

<details><summary><b>llm7</b> — 5/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-09 |
| `GLM-5.3-Flash` | **active** | 2777ms | — | 2026-10-09 |
| `codestral-latest` | **active** | 392ms | — | 2026-10-09 |
| `gemma4:31b` | **active** | 990ms | — | 2026-10-09 |
| `glm-5.2` | **active** | 761ms | — | 2026-10-09 |
| `gpt-oss:20b` | **active** | 734ms | — | 2026-10-09 |
| `minimax-m2.7` | **rate-limited** | — | — | 2026-10-09 |
| `minimax-m3` | **rate-limited** | — | — | 2026-10-09 |
| `mistral-Nemo-Instruct-2407` | **rate-limited** | — | — | 2026-10-09 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-10-09 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1,048,576 tokens
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
3. `z-ai/glm-5.3` (nvidia) — 1,000,000 tokens
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262,144 tokens
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
7. `ministral-14b-2512` (mistral) — 262,144 tokens
8. `ministral-8b-2512` (mistral) — 262,144 tokens
9. `ministral-8b-latest` (mistral) — 262,144 tokens
10. `codestral-2508` (mistral) — 256,000 tokens
11. `codestral-latest` (mistral) — 256,000 tokens
12. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
13. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
14. `openai/gpt-oss-120b` (groq) — 131,072 tokens
15. `openai/gpt-oss-20b` (groq) — 131,072 tokens
16. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
17. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
18. `ministral-3b-2512` (mistral) — 131,072 tokens
19. `ministral-3b-latest` (mistral) — 131,072 tokens
20. `glm-4.5-flash` (zai) — 131,072 tokens
21. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
22. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
23. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
24. `glm-4.6v-flash` (zai) — 128,000 tokens
25. `voxtral-small-2507` (mistral) — 32,768 tokens
26. `voxtral-small-latest` (mistral) — 32,768 tokens
27. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 127ms probe
2. `nvidia/nemotron-parse-2.0` (nvidia) — 128ms probe
3. `google/diffusiongemma-26b-a4b-it` (nvidia) — 143ms probe
4. `openai/gpt-oss-20b` (groq) — 149ms probe
5. `nvidia/ising-calibration-1.5-31b` (nvidia) — 191ms probe
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 201ms probe
7. `allam-2-7b` (groq) — 249ms probe
8. `ministral-3b-latest` (mistral) — 253ms probe
9. `codestral-latest` (mistral) — 259ms probe
10. `mistral-code-latest` (mistral) — 270ms probe
11. `voxtral-small-latest` (mistral) — 276ms probe
12. `codestral-2508` (mistral) — 279ms probe
13. `voxtral-small-2507` (mistral) — 280ms probe
14. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 287ms probe
15. `ministral-8b-latest` (mistral) — 289ms probe
16. `ministral-8b-2512` (mistral) — 292ms probe
17. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 295ms probe
18. `openai/gpt-oss-120b` (groq) — 301ms probe
19. `mistral-code-fim-latest` (mistral) — 316ms probe
20. `gpt-oss:120b` (ollama) — 324ms probe
21. `gemma4:31b` (ollama) — 327ms probe
22. `ministral-14b-2512` (mistral) — 374ms probe
23. `codestral-latest` (llm7) — 392ms probe
24. `ministral-14b-latest` (mistral) — 415ms probe
25. `gpt-oss:20b` (ollama) — 435ms probe
26. `nemotron-3-super` (ollama) — 501ms probe
27. `moonshotai/kimi-k3` (nvidia) — 513ms probe
28. `openai/gpt-oss-20b` (nvidia) — 528ms probe
29. `nemotron-3-nano:30b` (ollama) — 544ms probe
30. `z-ai/glm-5.3` (nvidia) — 617ms probe
31. `meta/muse-glimmer-30b` (nvidia) — 630ms probe
32. `gpt-oss:20b` (llm7) — 734ms probe
33. `glm-5.2` (llm7) — 761ms probe
34. `dots-studio/dots-3-note-preview:free` (openrouter) — 788ms probe
35. `glm-4.5-flash` (zai) — 810ms probe
36. `ministral-3b-2512` (mistral) — 811ms probe
37. `glm-4.6v-flash` (zai) — 946ms probe
38. `gemma4:31b` (llm7) — 990ms probe
39. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1730ms probe
40. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 1802ms probe
41. `GLM-5.3-Flash` (llm7) — 2777ms probe
42. `nemotron-3-ultra` (ollama) — 3954ms probe
43. `cohere/north-mini-code:free` (openrouter) — 11404ms probe

**Tool calling** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3` (nvidia) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `ministral-14b-2512` (mistral) — 262k ctx
8. `ministral-8b-2512` (mistral) — 262k ctx
9. `ministral-8b-latest` (mistral) — 262k ctx
10. `codestral-2508` (mistral) — 256k ctx
11. `codestral-latest` (mistral) — 256k ctx
12. `cohere/north-mini-code:free` (openrouter) — 256k ctx
13. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
14. `openai/gpt-oss-120b` (groq) — 131k ctx
15. `openai/gpt-oss-20b` (groq) — 131k ctx
16. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
17. `openai/gpt-oss-20b` (nvidia) — 131k ctx
18. `ministral-3b-2512` (mistral) — 131k ctx
19. `ministral-3b-latest` (mistral) — 131k ctx
20. `glm-4.5-flash` (zai) — 131k ctx
21. `qwen/qwen3.8-27b` (groq) — 131k ctx
22. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
23. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
24. `glm-4.6v-flash` (zai) — 128k ctx
25. `voxtral-small-2507` (mistral) — 32k ctx
26. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3` (nvidia) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `cohere/north-mini-code:free` (openrouter) — 256k ctx
8. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
9. `openai/gpt-oss-120b` (groq) — 131k ctx
10. `openai/gpt-oss-20b` (groq) — 131k ctx
11. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
12. `openai/gpt-oss-20b` (nvidia) — 131k ctx
13. `glm-4.5-flash` (zai) — 131k ctx
14. `qwen/qwen3.8-27b` (groq) — 131k ctx
15. `glm-4.6v-flash` (zai) — 128k ctx

**Vision (image input)** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
2. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
3. `ministral-14b-2512` (mistral) — 262k ctx
4. `ministral-8b-2512` (mistral) — 262k ctx
5. `ministral-8b-latest` (mistral) — 262k ctx
6. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
7. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
8. `ministral-3b-2512` (mistral) — 131k ctx
9. `ministral-3b-latest` (mistral) — 131k ctx
10. `qwen/qwen3.8-27b` (groq) — 131k ctx
11. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
12. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
13. `glm-4.6v-flash` (zai) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip probing — no point calling a corpse.
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
