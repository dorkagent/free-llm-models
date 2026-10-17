# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-17T14:21:52Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-17 |
| `qwen/qwen3.8-27b` | **active** | 144ms | ctx 131k, tools, reasoning, vision | 2026-10-17 |
| `openai/gpt-oss-20b` | **active** | 304ms | ctx 131k, tools, reasoning | 2026-10-17 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-17 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-17 |
| `openai/gpt-oss-120b` | **active** | 219ms | ctx 131k, tools, reasoning | 2026-10-17 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-17 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-17 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-17 |
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-17 |
| `allam-2-7b` | **active** | 251ms | ctx 4k | 2026-10-17 |

</details>

<details><summary><b>nvidia</b> — 10/81 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-17 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-17 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-17 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-17 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-17 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-17 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-17 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-17 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-17 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-17 |
| `google/deplot` | **dead** | — | — | 2026-10-17 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 5966ms | ctx 250k, tools, reasoning, vision | 2026-10-17 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-17 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-17 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-17 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-17 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-17 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-17 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-17 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-17 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-17 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-17 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 578ms | ctx 128k, tools, vision | 2026-10-17 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-17 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-17 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-17 |
| `meta/muse-glimmer-30b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-17 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-17 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-17 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-17 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-17 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-17 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-17 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-17 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-17 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-17 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-17 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-17 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-17 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-17 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 3911ms | — | 2026-10-17 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-17 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-17 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-17 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-17 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-17 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-17 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-17 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-17 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-17 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-17 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-17 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-17 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-17 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 460ms | — | 2026-10-17 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-17 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-17 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-17 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 388ms | ctx 1048k, tools, reasoning, vision | 2026-10-17 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-17 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-17 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-17 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-17 |
| `nvidia/nemotron-parse-2.0` | **active** | 131ms | — | 2026-10-17 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-17 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-17 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-17 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-17 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 27288ms | — | 2026-10-17 |
| `nvidia/vila` | **dead** | — | — | 2026-10-17 |
| `openai/gpt-oss-20b` | **active** | 121ms | ctx 131k, tools, reasoning | 2026-10-17 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-17 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-17 |
| `stepfun-ai/step-5-preview` | **active** | 388ms | — | 2026-10-17 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-17 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-17 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-17 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-17 |
| `z-ai/glm-5.3` | **active** | 328ms | ctx 1000k, tools, reasoning | 2026-10-17 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-17 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-17 |

</details>

<details><summary><b>mistral</b> — 12/45 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 368ms | ctx 256k, tools | 2026-10-17 |
| `codestral-latest` | **active** | 293ms | ctx 256k, tools | 2026-10-17 |
| `mistral-code-latest` | **active** | 327ms | — | 2026-10-17 |
| `mistral-code-fim-latest` | **active** | 463ms | — | 2026-10-17 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-17 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-17 |
| `ministral-14b-2512` | **active** | 416ms | ctx 262k, tools, vision | 2026-10-17 |
| `ministral-14b-latest` | **active** | 312ms | — | 2026-10-17 |
| `ministral-3b-2512` | **active** | 255ms | ctx 131k, tools, vision | 2026-10-17 |
| `ministral-3b-latest` | **active** | 313ms | ctx 131k, tools, vision | 2026-10-17 |
| `ministral-8b-2512` | **active** | 408ms | ctx 262k, tools, vision | 2026-10-17 |
| `ministral-8b-latest` | **active** | 659ms | ctx 262k, tools, vision | 2026-10-17 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-17 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-17 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-17 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-17 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-17 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-17 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-17 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-17 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-17 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-17 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-17 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-17 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-17 |
| `voxtral-small-2507` | **active** | 300ms | ctx 32k, tools | 2026-10-17 |
| `voxtral-small-latest` | **active** | 323ms | ctx 32k, tools | 2026-10-17 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-17 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-17 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-17 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-17 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-17 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-17 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-17 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-17 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-17 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-17 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-17 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-17 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-17 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-17 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-17 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-17 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-17 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-17 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-10-17 |
| `glm-4.5-flash` | **active** | 816ms | ctx 131k, tools, reasoning | 2026-10-17 |
| `glm-4.6v-flash` | **active** | 862ms | ctx 128k, tools, reasoning, vision | 2026-10-17 |

</details>

<details><summary><b>ollama</b> — 7/21 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-5.3` | **dead** | — | — | 2026-10-17 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-17 |
| `mistral-large-4` | **dead** | — | — | 2026-10-17 |
| `nemotron-3-super` | **active** | 1803ms | — | 2026-10-17 |
| `clef:27b` | **not-chat** | — | — | 2026-10-17 |
| `muse-spark-open` | **dead** | — | — | 2026-10-17 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-17 |
| `nemotron-3-ultra` | **active** | 651ms | — | 2026-10-17 |
| `beam` | **active** | 406ms | — | 2026-10-17 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-17 |
| `gemma4:31b` | **active** | 329ms | — | 2026-10-17 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-17 |
| `gpt-oss:20b` | **active** | 410ms | — | 2026-10-17 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-17 |
| `glm-5.2` | **dead** | — | — | 2026-10-17 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-17 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-17 |
| `minimax-m3` | **dead** | — | — | 2026-10-17 |
| `gpt-oss:120b` | **active** | 342ms | — | 2026-10-17 |
| `nemotron-3-nano:30b` | **active** | 502ms | — | 2026-10-17 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-17 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 212ms | ctx 128k, tools | 2026-10-17 |

</details>

<details><summary><b>openrouter</b> — 3/16 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `xingchen-agi/xing4.0-29b-a4b:free` | **active** | 10907ms | ctx 262k, tools, reasoning | 2026-10-17 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-17 |
| `dots-studio/dots-3-note-preview:free` | **active** | 872ms | ctx 512k, tools, reasoning, vision | 2026-10-17 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-17 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-17 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-17 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-17 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-17 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-17 |
| `cohere/north-mini-code:free` | **active** | 519ms | ctx 256k, tools, reasoning | 2026-10-17 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-17 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-17 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-17 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-17 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-17 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-17 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-17 |
| `GLM-5.3-Flash` | **active** | 2191ms | — | 2026-10-17 |
| `codestral-latest` | **active** | 847ms | — | 2026-10-17 |
| `gemma4:31b` | **dead** | — | — | 2026-10-17 |
| `glm-5.2` | **dead** | — | — | 2026-10-17 |
| `gpt-oss:20b` | **active** | 277ms | — | 2026-10-17 |
| `minimax-m2.7` | **active** | 692ms | — | 2026-10-17 |
| `minimax-m3` | **dead** | — | — | 2026-10-17 |
| `mistral-Nemo-Instruct-2407` | **rate-limited** | — | — | 2026-10-17 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-10-17 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `z-ai/glm-5.3` (nvidia) — 1,000,000 tokens
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
4. `ministral-14b-2512` (mistral) — 262,144 tokens
5. `ministral-8b-2512` (mistral) — 262,144 tokens
6. `ministral-8b-latest` (mistral) — 262,144 tokens
7. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262,144 tokens
8. `codestral-2508` (mistral) — 256,000 tokens
9. `codestral-latest` (mistral) — 256,000 tokens
10. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
11. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
12. `openai/gpt-oss-20b` (groq) — 131,072 tokens
13. `openai/gpt-oss-120b` (groq) — 131,072 tokens
14. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
15. `ministral-3b-2512` (mistral) — 131,072 tokens
16. `ministral-3b-latest` (mistral) — 131,072 tokens
17. `glm-4.5-flash` (zai) — 131,072 tokens
18. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
19. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
20. `glm-4.6v-flash` (zai) — 128,000 tokens
21. `voxtral-small-2507` (mistral) — 32,768 tokens
22. `voxtral-small-latest` (mistral) — 32,768 tokens
23. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `openai/gpt-oss-20b` (nvidia) — 121ms probe
2. `nvidia/nemotron-parse-2.0` (nvidia) — 131ms probe
3. `qwen/qwen3.8-27b` (groq) — 144ms probe
4. `openai/gpt-oss-120b` (groq) — 219ms probe
5. `allam-2-7b` (groq) — 251ms probe
6. `ministral-3b-2512` (mistral) — 255ms probe
7. `gpt-oss:20b` (llm7) — 277ms probe
8. `codestral-latest` (mistral) — 293ms probe
9. `voxtral-small-2507` (mistral) — 300ms probe
10. `openai/gpt-oss-20b` (groq) — 304ms probe
11. `ministral-14b-latest` (mistral) — 312ms probe
12. `ministral-3b-latest` (mistral) — 313ms probe
13. `voxtral-small-latest` (mistral) — 323ms probe
14. `mistral-code-latest` (mistral) — 327ms probe
15. `z-ai/glm-5.3` (nvidia) — 328ms probe
16. `gemma4:31b` (ollama) — 329ms probe
17. `gpt-oss:120b` (ollama) — 342ms probe
18. `codestral-2508` (mistral) — 368ms probe
19. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 388ms probe
20. `stepfun-ai/step-5-preview` (nvidia) — 388ms probe
21. `beam` (ollama) — 406ms probe
22. `ministral-8b-2512` (mistral) — 408ms probe
23. `gpt-oss:20b` (ollama) — 410ms probe
24. `ministral-14b-2512` (mistral) — 416ms probe
25. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 460ms probe
26. `mistral-code-fim-latest` (mistral) — 463ms probe
27. `nemotron-3-nano:30b` (ollama) — 502ms probe
28. `cohere/north-mini-code:free` (openrouter) — 519ms probe
29. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 578ms probe
30. `nemotron-3-ultra` (ollama) — 651ms probe
31. `ministral-8b-latest` (mistral) — 659ms probe
32. `minimax-m2.7` (llm7) — 692ms probe
33. `glm-4.5-flash` (zai) — 816ms probe
34. `codestral-latest` (llm7) — 847ms probe
35. `glm-4.6v-flash` (zai) — 862ms probe
36. `dots-studio/dots-3-note-preview:free` (openrouter) — 872ms probe
37. `nemotron-3-super` (ollama) — 1803ms probe
38. `GLM-5.3-Flash` (llm7) — 2191ms probe
39. `nvidia/ising-calibration-1.5-31b` (nvidia) — 3911ms probe
40. `google/diffusiongemma-26b-a4b-it` (nvidia) — 5966ms probe
41. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 10907ms probe
42. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 27288ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `z-ai/glm-5.3` (nvidia) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `ministral-14b-2512` (mistral) — 262k ctx
5. `ministral-8b-2512` (mistral) — 262k ctx
6. `ministral-8b-latest` (mistral) — 262k ctx
7. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
8. `codestral-2508` (mistral) — 256k ctx
9. `codestral-latest` (mistral) — 256k ctx
10. `cohere/north-mini-code:free` (openrouter) — 256k ctx
11. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
12. `openai/gpt-oss-20b` (groq) — 131k ctx
13. `openai/gpt-oss-120b` (groq) — 131k ctx
14. `openai/gpt-oss-20b` (nvidia) — 131k ctx
15. `ministral-3b-2512` (mistral) — 131k ctx
16. `ministral-3b-latest` (mistral) — 131k ctx
17. `glm-4.5-flash` (zai) — 131k ctx
18. `qwen/qwen3.8-27b` (groq) — 131k ctx
19. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
20. `glm-4.6v-flash` (zai) — 128k ctx
21. `voxtral-small-2507` (mistral) — 32k ctx
22. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `z-ai/glm-5.3` (nvidia) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
5. `cohere/north-mini-code:free` (openrouter) — 256k ctx
6. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
7. `openai/gpt-oss-20b` (groq) — 131k ctx
8. `openai/gpt-oss-120b` (groq) — 131k ctx
9. `openai/gpt-oss-20b` (nvidia) — 131k ctx
10. `glm-4.5-flash` (zai) — 131k ctx
11. `qwen/qwen3.8-27b` (groq) — 131k ctx
12. `glm-4.6v-flash` (zai) — 128k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
3. `ministral-14b-2512` (mistral) — 262k ctx
4. `ministral-8b-2512` (mistral) — 262k ctx
5. `ministral-8b-latest` (mistral) — 262k ctx
6. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
7. `ministral-3b-2512` (mistral) — 131k ctx
8. `ministral-3b-latest` (mistral) — 131k ctx
9. `qwen/qwen3.8-27b` (groq) — 131k ctx
10. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
11. `glm-4.6v-flash` (zai) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (968ms) | 1 day(s) |


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
