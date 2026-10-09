# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-09T04:38:23Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-09 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-09 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-09 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-09 |
| `openai/gpt-oss-20b` | **active** | 289ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `qwen/qwen3.8-27b` | **active** | 115ms | ctx 131k, tools, reasoning, vision | 2026-10-09 |
| `openai/gpt-oss-120b` | **active** | 239ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `allam-2-7b` | **active** | 258ms | ctx 4k | 2026-10-09 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-09 |
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-09 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-09 |

</details>

<details><summary><b>nvidia</b> — 13/80 active</summary>

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
| `google/diffusiongemma-26b-a4b-it` | **active** | 523ms | ctx 250k, tools, reasoning, vision | 2026-10-09 |
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
| `meta/llama-3.2-11b-vision-instruct` | **active** | 1202ms | ctx 128k, tools, vision | 2026-10-09 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 872ms | ctx 128k, tools, vision | 2026-10-09 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-09 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-09 |
| `meta/muse-glimmer-30b` | **active** | 4751ms | ctx 131k, tools, reasoning, vision | 2026-10-09 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-09 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-09 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-09 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-09 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-09 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-09 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-09 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-09 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `moonshotai/kimi-k3` | **active** | 518ms | ctx 1048k, tools, reasoning, vision | 2026-10-09 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-09 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-09 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-09 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 227ms | — | 2026-10-09 |
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
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 4505ms | ctx 256k, tools, reasoning, vision | 2026-10-09 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 2041ms | ctx 262k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 1673ms | ctx 1000k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-09 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 2053ms | ctx 262k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/nemotron-parse-2.0` | **active** | 213ms | — | 2026-10-09 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-09 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-09 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-09 |
| `nvidia/riva-translate-4b-instruct-v2` | **dead** | — | — | 2026-10-09 |
| `nvidia/vila` | **dead** | — | — | 2026-10-09 |
| `openai/gpt-oss-20b` | **active** | 637ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-09 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-09 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-09 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-09 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-09 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-09 |
| `z-ai/glm-5.3` | **active** | 281ms | ctx 1000k, tools, reasoning | 2026-10-09 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-09 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-09 |

</details>

<details><summary><b>mistral</b> — 12/46 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 354ms | ctx 256k, tools | 2026-10-09 |
| `codestral-latest` | **active** | 316ms | ctx 256k, tools | 2026-10-09 |
| `mistral-code-latest` | **active** | 295ms | — | 2026-10-09 |
| `mistral-code-fim-latest` | **active** | 364ms | — | 2026-10-09 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `ministral-14b-2512` | **active** | 771ms | ctx 262k, tools, vision | 2026-10-09 |
| `ministral-14b-latest` | **active** | 345ms | — | 2026-10-09 |
| `ministral-3b-2512` | **active** | 295ms | ctx 131k, tools, vision | 2026-10-09 |
| `ministral-3b-latest` | **active** | 282ms | ctx 131k, tools, vision | 2026-10-09 |
| `ministral-8b-2512` | **active** | 368ms | ctx 262k, tools, vision | 2026-10-09 |
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
| `voxtral-small-2507` | **active** | 306ms | ctx 32k, tools | 2026-10-09 |
| `voxtral-small-latest` | **active** | 300ms | ctx 32k, tools | 2026-10-09 |
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
| `glm-4.7-flash` | **active** | 1252ms | ctx 200k, tools, reasoning | 2026-10-09 |
| `glm-4.5-flash` | **active** | 873ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-09 |

</details>

<details><summary><b>ollama</b> — 6/18 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-09 |
| `gpt-oss:20b` | **active** | 1680ms | — | 2026-10-09 |
| `glm-5.3` | **dead** | — | — | 2026-10-09 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-09 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-09 |
| `mistral-large-4` | **dead** | — | — | 2026-10-09 |
| `gemma4:31b` | **active** | 438ms | — | 2026-10-09 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-09 |
| `minimax-m3` | **dead** | — | — | 2026-10-09 |
| `nemotron-3-ultra` | **active** | 3815ms | — | 2026-10-09 |
| `gpt-oss:120b` | **active** | 426ms | — | 2026-10-09 |
| `nemotron-3-nano:30b` | **active** | 337ms | — | 2026-10-09 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-09 |
| `glm-5.2` | **dead** | — | — | 2026-10-09 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-09 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-09 |
| `nemotron-3-super` | **active** | 579ms | — | 2026-10-09 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-09 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 239ms | ctx 128k, tools | 2026-10-09 |

</details>

<details><summary><b>openrouter</b> — 3/15 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `apodex/apodex-1.1-mini:free` | **active** | 679ms | ctx 262k, tools, reasoning | 2026-10-09 |
| `dots-studio/dots-3-note-preview:free` | **active** | 12004ms | ctx 512k, tools, reasoning, vision | 2026-10-09 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-09 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-09 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-09 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-09 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-09 |
| `cohere/north-mini-code:free` | **active** | 5972ms | ctx 256k, tools, reasoning | 2026-10-09 |
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
| `GLM-5.3-Flash` | **dead** | — | — | 2026-10-09 |
| `codestral-latest` | **active** | 1351ms | — | 2026-10-09 |
| `gemma4:31b` | **active** | 210ms | — | 2026-10-09 |
| `glm-5.2` | **active** | 819ms | — | 2026-10-09 |
| `gpt-oss:20b` | **rate-limited** | — | — | 2026-10-09 |
| `minimax-m2.7` | **rate-limited** | — | — | 2026-10-09 |
| `minimax-m3` | **active** | 3319ms | — | 2026-10-09 |
| `mistral-Nemo-Instruct-2407` | **active** | 650ms | — | 2026-10-09 |
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
10. `apodex/apodex-1.1-mini:free` (openrouter) — 262,144 tokens
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
12. `codestral-2508` (mistral) — 256,000 tokens
13. `codestral-latest` (mistral) — 256,000 tokens
14. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
15. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
16. `glm-4.7-flash` (zai) — 200,000 tokens
17. `openai/gpt-oss-20b` (groq) — 131,072 tokens
18. `openai/gpt-oss-120b` (groq) — 131,072 tokens
19. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
20. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
21. `ministral-3b-2512` (mistral) — 131,072 tokens
22. `ministral-3b-latest` (mistral) — 131,072 tokens
23. `glm-4.5-flash` (zai) — 131,072 tokens
24. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
25. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
26. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
27. `voxtral-small-2507` (mistral) — 32,768 tokens
28. `voxtral-small-latest` (mistral) — 32,768 tokens
29. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 115ms probe
2. `gemma4:31b` (llm7) — 210ms probe
3. `nvidia/nemotron-parse-2.0` (nvidia) — 213ms probe
4. `nvidia/ising-calibration-1.5-31b` (nvidia) — 227ms probe
5. `openai/gpt-oss-120b` (groq) — 239ms probe
6. `allam-2-7b` (groq) — 258ms probe
7. `z-ai/glm-5.3` (nvidia) — 281ms probe
8. `ministral-3b-latest` (mistral) — 282ms probe
9. `openai/gpt-oss-20b` (groq) — 289ms probe
10. `ministral-8b-latest` (mistral) — 289ms probe
11. `mistral-code-latest` (mistral) — 295ms probe
12. `ministral-3b-2512` (mistral) — 295ms probe
13. `voxtral-small-latest` (mistral) — 300ms probe
14. `voxtral-small-2507` (mistral) — 306ms probe
15. `codestral-latest` (mistral) — 316ms probe
16. `nemotron-3-nano:30b` (ollama) — 337ms probe
17. `ministral-14b-latest` (mistral) — 345ms probe
18. `codestral-2508` (mistral) — 354ms probe
19. `mistral-code-fim-latest` (mistral) — 364ms probe
20. `ministral-8b-2512` (mistral) — 368ms probe
21. `gpt-oss:120b` (ollama) — 426ms probe
22. `gemma4:31b` (ollama) — 438ms probe
23. `moonshotai/kimi-k3` (nvidia) — 518ms probe
24. `google/diffusiongemma-26b-a4b-it` (nvidia) — 523ms probe
25. `nemotron-3-super` (ollama) — 579ms probe
26. `openai/gpt-oss-20b` (nvidia) — 637ms probe
27. `mistral-Nemo-Instruct-2407` (llm7) — 650ms probe
28. `apodex/apodex-1.1-mini:free` (openrouter) — 679ms probe
29. `ministral-14b-2512` (mistral) — 771ms probe
30. `glm-5.2` (llm7) — 819ms probe
31. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 872ms probe
32. `glm-4.5-flash` (zai) — 873ms probe
33. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 1202ms probe
34. `glm-4.7-flash` (zai) — 1252ms probe
35. `codestral-latest` (llm7) — 1351ms probe
36. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1673ms probe
37. `gpt-oss:20b` (ollama) — 1680ms probe
38. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 2041ms probe
39. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 2053ms probe
40. `minimax-m3` (llm7) — 3319ms probe
41. `nemotron-3-ultra` (ollama) — 3815ms probe
42. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 4505ms probe
43. `meta/muse-glimmer-30b` (nvidia) — 4751ms probe
44. `cohere/north-mini-code:free` (openrouter) — 5972ms probe
45. `dots-studio/dots-3-note-preview:free` (openrouter) — 12004ms probe

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
10. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
12. `codestral-2508` (mistral) — 256k ctx
13. `codestral-latest` (mistral) — 256k ctx
14. `cohere/north-mini-code:free` (openrouter) — 256k ctx
15. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
16. `glm-4.7-flash` (zai) — 200k ctx
17. `openai/gpt-oss-20b` (groq) — 131k ctx
18. `openai/gpt-oss-120b` (groq) — 131k ctx
19. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
20. `openai/gpt-oss-20b` (nvidia) — 131k ctx
21. `ministral-3b-2512` (mistral) — 131k ctx
22. `ministral-3b-latest` (mistral) — 131k ctx
23. `glm-4.5-flash` (zai) — 131k ctx
24. `qwen/qwen3.8-27b` (groq) — 131k ctx
25. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
26. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
27. `voxtral-small-2507` (mistral) — 32k ctx
28. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3` (nvidia) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
8. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
9. `cohere/north-mini-code:free` (openrouter) — 256k ctx
10. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
11. `glm-4.7-flash` (zai) — 200k ctx
12. `openai/gpt-oss-20b` (groq) — 131k ctx
13. `openai/gpt-oss-120b` (groq) — 131k ctx
14. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
15. `openai/gpt-oss-20b` (nvidia) — 131k ctx
16. `glm-4.5-flash` (zai) — 131k ctx
17. `qwen/qwen3.8-27b` (groq) — 131k ctx

**Vision (image input)** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
2. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
3. `ministral-14b-2512` (mistral) — 262k ctx
4. `ministral-8b-2512` (mistral) — 262k ctx
5. `ministral-8b-latest` (mistral) — 262k ctx
6. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
7. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
8. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
9. `ministral-3b-2512` (mistral) — 131k ctx
10. `ministral-3b-latest` (mistral) — 131k ctx
11. `qwen/qwen3.8-27b` (groq) — 131k ctx
12. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
13. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (202ms) | 1 day(s) |


## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip the official probe, but a shadow probe still runs daily to audit feed accuracy (see above).
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
