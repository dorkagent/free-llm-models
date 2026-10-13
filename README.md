# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-13T14:20:21Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `openai/gpt-oss-20b` | **active** | 207ms | ctx 131k, tools, reasoning | 2026-10-13 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-13 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-13 |
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-13 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-13 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-13 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-13 |
| `qwen/qwen3.8-27b` | **active** | 204ms | ctx 131k, tools, reasoning, vision | 2026-10-13 |
| `allam-2-7b` | **active** | 266ms | ctx 4k | 2026-10-13 |
| `openai/gpt-oss-120b` | **active** | 588ms | ctx 131k, tools, reasoning | 2026-10-13 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-13 |

</details>

<details><summary><b>nvidia</b> — 13/80 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-13 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-13 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-13 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-13 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-13 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-13 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-13 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-13 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-13 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-13 |
| `google/deplot` | **dead** | — | — | 2026-10-13 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 443ms | ctx 250k, tools, reasoning, vision | 2026-10-13 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-13 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-13 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-13 |
| `google/gemma-4-31b-it` | **active** | 3103ms | ctx 256k, tools, reasoning, vision | 2026-10-13 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-13 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-13 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-13 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-13 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-13 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-13 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 453ms | ctx 128k, tools, vision | 2026-10-13 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-13 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-13 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-13 |
| `meta/muse-glimmer-30b` | **active** | 1820ms | ctx 131k, tools, reasoning, vision | 2026-10-13 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-13 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-13 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-13 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-13 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-13 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-13 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-13 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-13 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-13 |
| `moonshotai/kimi-k3` | **active** | 740ms | ctx 1048k, tools, reasoning, vision | 2026-10-13 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-13 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-13 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-13 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-13 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 18036ms | — | 2026-10-13 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-13 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-13 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-13 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-13 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-13 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-13 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-13 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-13 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-13 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-13 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-13 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-13 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-13 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 618ms | ctx 262k, tools, reasoning | 2026-10-13 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 723ms | ctx 1000k, tools, reasoning | 2026-10-13 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-13 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 1288ms | ctx 262k, tools, reasoning | 2026-10-13 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-13 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-13 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-13 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-13 |
| `nvidia/nemotron-parse-2.0` | **active** | 248ms | — | 2026-10-13 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-13 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-13 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-13 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-13 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 27870ms | — | 2026-10-13 |
| `nvidia/vila` | **dead** | — | — | 2026-10-13 |
| `openai/gpt-oss-20b` | **active** | 251ms | ctx 131k, tools, reasoning | 2026-10-13 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-13 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-13 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-13 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-13 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-13 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-13 |
| `z-ai/glm-5.3` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-13 |
| `z-ai/glm-5.3-flash` | **active** | 27681ms | ctx 1000k, tools, reasoning, vision | 2026-10-13 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-13 |

</details>

<details><summary><b>mistral</b> — 12/46 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 369ms | ctx 256k, tools | 2026-10-13 |
| `codestral-latest` | **active** | 477ms | ctx 256k, tools | 2026-10-13 |
| `mistral-code-latest` | **active** | 420ms | — | 2026-10-13 |
| `mistral-code-fim-latest` | **active** | 461ms | — | 2026-10-13 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-13 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-13 |
| `ministral-14b-2512` | **active** | 839ms | ctx 262k, tools, vision | 2026-10-13 |
| `ministral-14b-latest` | **active** | 565ms | — | 2026-10-13 |
| `ministral-3b-2512` | **active** | 383ms | ctx 131k, tools, vision | 2026-10-13 |
| `ministral-3b-latest` | **active** | 305ms | ctx 131k, tools, vision | 2026-10-13 |
| `ministral-8b-2512` | **active** | 434ms | ctx 262k, tools, vision | 2026-10-13 |
| `ministral-8b-latest` | **active** | 390ms | ctx 262k, tools, vision | 2026-10-13 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-13 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-13 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-13 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-13 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-13 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-13 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-13 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-13 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-13 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-13 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-13 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-13 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-13 |
| `voxtral-small-2507` | **active** | 345ms | ctx 32k, tools | 2026-10-13 |
| `voxtral-small-latest` | **active** | 360ms | ctx 32k, tools | 2026-10-13 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-13 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-13 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-13 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-13 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-13 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-13 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-13 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-13 |
| `mistral-ocr-4-0` | **not-chat** | — | — | 2026-10-13 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-13 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-13 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-13 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-13 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-13 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-13 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-13 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-13 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-13 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-13 |

</details>

<details><summary><b>zai</b> — 1/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-10-13 |
| `glm-4.5-flash` | **active** | 3652ms | ctx 131k, tools, reasoning | 2026-10-13 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-13 |

</details>

<details><summary><b>ollama</b> — 6/18 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-13 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-13 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-13 |
| `nemotron-3-nano:30b` | **active** | 1471ms | — | 2026-10-13 |
| `gpt-oss:20b` | **active** | 557ms | — | 2026-10-13 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-13 |
| `minimax-m3` | **dead** | — | — | 2026-10-13 |
| `gpt-oss:120b` | **active** | 437ms | — | 2026-10-13 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-13 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-13 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-13 |
| `nemotron-3-super` | **active** | 586ms | — | 2026-10-13 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-13 |
| `glm-5.2` | **dead** | — | — | 2026-10-13 |
| `glm-5.3` | **dead** | — | — | 2026-10-13 |
| `gemma4:31b` | **active** | 395ms | — | 2026-10-13 |
| `nemotron-3-ultra` | **active** | 3179ms | — | 2026-10-13 |
| `mistral-large-4` | **dead** | — | — | 2026-10-13 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 236ms | ctx 128k, tools | 2026-10-13 |

</details>

<details><summary><b>openrouter</b> — 3/15 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `apodex/apodex-1.1-mini:free` | **active** | 802ms | ctx 262k, tools, reasoning | 2026-10-13 |
| `dots-studio/dots-3-note-preview:free` | **active** | 18149ms | ctx 512k, tools, reasoning, vision | 2026-10-13 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-13 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-13 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-13 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-13 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-13 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-13 |
| `cohere/north-mini-code:free` | **active** | 273ms | ctx 256k, tools, reasoning | 2026-10-13 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-13 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-13 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-13 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-13 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-13 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-13 |

</details>

<details><summary><b>llm7</b> — 3/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-13 |
| `GLM-5.3-Flash` | **dead** | — | — | 2026-10-13 |
| `codestral-latest` | **rate-limited** | — | — | 2026-10-13 |
| `gemma4:31b` | **dead** | — | — | 2026-10-13 |
| `glm-5.2` | **dead** | — | — | 2026-10-13 |
| `gpt-oss:20b` | **active** | 1298ms | — | 2026-10-13 |
| `minimax-m2.7` | **not-chat** | — | — | 2026-10-13 |
| `minimax-m3` | **dead** | — | — | 2026-10-13 |
| `mistral-Nemo-Instruct-2407` | **active** | 1018ms | — | 2026-10-13 |
| `nemotron-3-nano:30b` | **active** | 784ms | — | 2026-10-13 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1,048,576 tokens
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
3. `z-ai/glm-5.3-flash` (nvidia) — 1,000,000 tokens
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262,144 tokens
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
7. `ministral-14b-2512` (mistral) — 262,144 tokens
8. `ministral-8b-2512` (mistral) — 262,144 tokens
9. `ministral-8b-latest` (mistral) — 262,144 tokens
10. `apodex/apodex-1.1-mini:free` (openrouter) — 262,144 tokens
11. `google/gemma-4-31b-it` (nvidia) — 256,000 tokens
12. `codestral-2508` (mistral) — 256,000 tokens
13. `codestral-latest` (mistral) — 256,000 tokens
14. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
15. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
16. `openai/gpt-oss-20b` (groq) — 131,072 tokens
17. `openai/gpt-oss-120b` (groq) — 131,072 tokens
18. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
19. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
20. `ministral-3b-2512` (mistral) — 131,072 tokens
21. `ministral-3b-latest` (mistral) — 131,072 tokens
22. `glm-4.5-flash` (zai) — 131,072 tokens
23. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
24. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
25. `voxtral-small-2507` (mistral) — 32,768 tokens
26. `voxtral-small-latest` (mistral) — 32,768 tokens
27. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 204ms probe
2. `openai/gpt-oss-20b` (groq) — 207ms probe
3. `nvidia/nemotron-parse-2.0` (nvidia) — 248ms probe
4. `openai/gpt-oss-20b` (nvidia) — 251ms probe
5. `allam-2-7b` (groq) — 266ms probe
6. `cohere/north-mini-code:free` (openrouter) — 273ms probe
7. `ministral-3b-latest` (mistral) — 305ms probe
8. `voxtral-small-2507` (mistral) — 345ms probe
9. `voxtral-small-latest` (mistral) — 360ms probe
10. `codestral-2508` (mistral) — 369ms probe
11. `ministral-3b-2512` (mistral) — 383ms probe
12. `ministral-8b-latest` (mistral) — 390ms probe
13. `gemma4:31b` (ollama) — 395ms probe
14. `mistral-code-latest` (mistral) — 420ms probe
15. `ministral-8b-2512` (mistral) — 434ms probe
16. `gpt-oss:120b` (ollama) — 437ms probe
17. `google/diffusiongemma-26b-a4b-it` (nvidia) — 443ms probe
18. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 453ms probe
19. `mistral-code-fim-latest` (mistral) — 461ms probe
20. `codestral-latest` (mistral) — 477ms probe
21. `gpt-oss:20b` (ollama) — 557ms probe
22. `ministral-14b-latest` (mistral) — 565ms probe
23. `nemotron-3-super` (ollama) — 586ms probe
24. `openai/gpt-oss-120b` (groq) — 588ms probe
25. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 618ms probe
26. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 723ms probe
27. `moonshotai/kimi-k3` (nvidia) — 740ms probe
28. `nemotron-3-nano:30b` (llm7) — 784ms probe
29. `apodex/apodex-1.1-mini:free` (openrouter) — 802ms probe
30. `ministral-14b-2512` (mistral) — 839ms probe
31. `mistral-Nemo-Instruct-2407` (llm7) — 1018ms probe
32. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 1288ms probe
33. `gpt-oss:20b` (llm7) — 1298ms probe
34. `nemotron-3-nano:30b` (ollama) — 1471ms probe
35. `meta/muse-glimmer-30b` (nvidia) — 1820ms probe
36. `google/gemma-4-31b-it` (nvidia) — 3103ms probe
37. `nemotron-3-ultra` (ollama) — 3179ms probe
38. `glm-4.5-flash` (zai) — 3652ms probe
39. `nvidia/ising-calibration-1.5-31b` (nvidia) — 18036ms probe
40. `dots-studio/dots-3-note-preview:free` (openrouter) — 18149ms probe
41. `z-ai/glm-5.3-flash` (nvidia) — 27681ms probe
42. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 27870ms probe

**Tool calling** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `ministral-14b-2512` (mistral) — 262k ctx
8. `ministral-8b-2512` (mistral) — 262k ctx
9. `ministral-8b-latest` (mistral) — 262k ctx
10. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
11. `google/gemma-4-31b-it` (nvidia) — 256k ctx
12. `codestral-2508` (mistral) — 256k ctx
13. `codestral-latest` (mistral) — 256k ctx
14. `cohere/north-mini-code:free` (openrouter) — 256k ctx
15. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
16. `openai/gpt-oss-20b` (groq) — 131k ctx
17. `openai/gpt-oss-120b` (groq) — 131k ctx
18. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
19. `openai/gpt-oss-20b` (nvidia) — 131k ctx
20. `ministral-3b-2512` (mistral) — 131k ctx
21. `ministral-3b-latest` (mistral) — 131k ctx
22. `glm-4.5-flash` (zai) — 131k ctx
23. `qwen/qwen3.8-27b` (groq) — 131k ctx
24. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
25. `voxtral-small-2507` (mistral) — 32k ctx
26. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
8. `google/gemma-4-31b-it` (nvidia) — 256k ctx
9. `cohere/north-mini-code:free` (openrouter) — 256k ctx
10. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
11. `openai/gpt-oss-20b` (groq) — 131k ctx
12. `openai/gpt-oss-120b` (groq) — 131k ctx
13. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
14. `openai/gpt-oss-20b` (nvidia) — 131k ctx
15. `glm-4.5-flash` (zai) — 131k ctx
16. `qwen/qwen3.8-27b` (groq) — 131k ctx

**Vision (image input)** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
2. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `ministral-14b-2512` (mistral) — 262k ctx
5. `ministral-8b-2512` (mistral) — 262k ctx
6. `ministral-8b-latest` (mistral) — 262k ctx
7. `google/gemma-4-31b-it` (nvidia) — 256k ctx
8. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
9. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
10. `ministral-3b-2512` (mistral) — 131k ctx
11. `ministral-3b-latest` (mistral) — 131k ctx
12. `qwen/qwen3.8-27b` (groq) — 131k ctx
13. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx

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
| llm7 | response-headers | — | — |  |


## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip the official probe, but a shadow probe still runs daily to audit feed accuracy (see above).
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
