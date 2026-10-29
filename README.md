# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-29T19:28:23Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-10-29 |
| `qwen/qwen3.8-27b` | **active** | 118ms | ctx 131k, tools, reasoning, vision | 2026-10-29 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-29 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-29 |
| `openai/gpt-oss-20b` | **active** | 174ms | ctx 131k, tools, reasoning | 2026-10-29 |
| `openai/gpt-oss-120b` | **active** | 245ms | ctx 131k, tools, reasoning | 2026-10-29 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-10-29 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-29 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-29 |
| `allam-2-7b` | **active** | 274ms | ctx 4k | 2026-10-29 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-29 |

</details>

<details><summary><b>nvidia</b> — 15/85 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-29 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-29 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-29 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-29 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-29 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-29 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-29 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-29 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-29 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-29 |
| `google/deplot` | **dead** | — | — | 2026-10-29 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 430ms | ctx 250k, tools, reasoning, vision | 2026-10-29 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-29 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-29 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-29 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-29 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-29 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-29 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-29 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-29 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-29 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-29 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 4454ms | ctx 128k, tools, vision | 2026-10-29 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-29 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-10-29 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-29 |
| `meta/muse-glimmer-30b` | **active** | 1301ms | ctx 131k, tools, reasoning, vision | 2026-10-29 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-29 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-29 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-29 |
| `minimaxai/minimax-m3.1-flash` | **active** | 612ms | ctx 262k, tools, reasoning, vision | 2026-10-29 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-29 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-29 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-10-29 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-29 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 6454ms | — | 2026-10-29 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-29 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-29 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-29 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-29 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-29 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-29 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 407ms | — | 2026-10-29 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-29 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-29 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-29 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-29 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-29 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-29 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-29 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-29 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-10-29 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-29 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-29 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-29 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 794ms | ctx 256k, tools, reasoning, vision | 2026-10-29 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-10-29 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 1927ms | ctx 1000k, tools, reasoning | 2026-10-29 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 349ms | — | 2026-10-29 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-29 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-10-29 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-10-29 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 261ms | ctx 262k, tools, reasoning | 2026-10-29 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 279ms | ctx 1048k, tools, reasoning, vision | 2026-10-29 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-29 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-29 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-29 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-29 |
| `nvidia/nemotron-parse-2.0` | **active** | 237ms | — | 2026-10-29 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-29 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-29 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-29 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-29 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 1707ms | — | 2026-10-29 |
| `nvidia/vila` | **dead** | — | — | 2026-10-29 |
| `openai/gpt-oss-20b` | **active** | 269ms | ctx 131k, tools, reasoning | 2026-10-29 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-29 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-29 |
| `stepfun-ai/step-5-preview` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-29 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-29 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-29 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-29 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-29 |
| `z-ai/glm-5.3-flash` | **active** | 27523ms | ctx 1000k, tools, reasoning, vision | 2026-10-29 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-29 |

</details>

<details><summary><b>mistral</b> — 14/55 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 411ms | ctx 256k, tools | 2026-10-29 |
| `codestral-latest` | **active** | 374ms | ctx 256k, tools | 2026-10-29 |
| `mistral-code-latest` | **active** | 427ms | — | 2026-10-29 |
| `mistral-code-fim-latest` | **active** | 363ms | — | 2026-10-29 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-29 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-29 |
| `ministral-14b-2512` | **active** | 774ms | ctx 262k, tools, vision | 2026-10-29 |
| `ministral-14b-latest` | **active** | 523ms | — | 2026-10-29 |
| `ministral-3b-2512` | **active** | 346ms | ctx 131k, tools, vision | 2026-10-29 |
| `ministral-3b-latest` | **active** | 399ms | ctx 131k, tools, vision | 2026-10-29 |
| `ministral-8b-2512` | **active** | 432ms | ctx 262k, tools, vision | 2026-10-29 |
| `ministral-8b-latest` | **active** | 402ms | ctx 262k, tools, vision | 2026-10-29 |
| `mistral-large-4` | **active** | 677ms | ctx 1048k, tools, reasoning, vision | 2026-10-29 |
| `mistral-large-4-0` | **active** | 867ms | ctx 1048k, tools, reasoning, vision | 2026-10-29 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-29 |
| `mistral-medium` | **rate-limited** | — | ctx 131k, tools, vision | 2026-10-29 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-29 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-29 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-29 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-29 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-29 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-29 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-29 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-29 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-29 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-29 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-29 |
| `voxtral-small-2507` | **active** | 393ms | ctx 32k, tools | 2026-10-29 |
| `voxtral-small-latest` | **active** | 370ms | ctx 32k, tools | 2026-10-29 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-29 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-29 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-29 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-29 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-29 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-29 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-29 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-29 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-29 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-29 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-10-29 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-10-29 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 943ms | ctx 200k, tools, reasoning | 2026-10-29 |
| `glm-4.5-flash` | **active** | 8293ms | ctx 131k, tools, reasoning | 2026-10-29 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-29 |

</details>

<details><summary><b>ollama</b> — 7/23 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `mistral-large-4` | **dead** | — | — | 2026-10-29 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-29 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-29 |
| `gpt-oss:120b` | **active** | 419ms | — | 2026-10-29 |
| `nemotron-3-nano:30b` | **active** | 617ms | — | 2026-10-29 |
| `minimax-m3` | **dead** | — | — | 2026-10-29 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-29 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-10-29 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-10-29 |
| `nemotron-3-ultra` | **active** | 1600ms | — | 2026-10-29 |
| `clef:27b` | **not-chat** | — | — | 2026-10-29 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-29 |
| `beam` | **active** | 597ms | — | 2026-10-29 |
| `muse-spark-open` | **dead** | — | — | 2026-10-29 |
| `glm-5.2` | **dead** | — | — | 2026-10-29 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-29 |
| `gemma4:31b` | **active** | 396ms | — | 2026-10-29 |
| `glm-5.3` | **dead** | — | — | 2026-10-29 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-29 |
| `gpt-oss:20b` | **active** | 457ms | — | 2026-10-29 |
| `nemotron-3-super` | **active** | 427ms | — | 2026-10-29 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-29 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-29 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 234ms | ctx 128k, tools | 2026-10-29 |

</details>

<details><summary><b>openrouter</b> — 3/16 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `recursive/flint-v1.0:free` | **active** | 297ms | ctx 262k, tools, reasoning | 2026-10-29 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **rate-limited** | — | ctx 262k, tools, reasoning | 2026-10-29 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-29 |
| `dots-studio/dots-3-note-preview:free` | **active** | 788ms | ctx 512k, tools, reasoning, vision | 2026-10-29 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-29 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-29 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-29 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-29 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-29 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-29 |
| `cohere/north-mini-code:free` | **active** | 365ms | ctx 256k, tools, reasoning | 2026-10-29 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-29 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-29 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-29 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-29 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-29 |

</details>

<details><summary><b>llm7</b> — 5/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-29 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-10-29 |
| `codestral-latest` | **active** | 526ms | — | 2026-10-29 |
| `gemma4:31b` | **dead** | — | — | 2026-10-29 |
| `glm-5.2` | **dead** | — | — | 2026-10-29 |
| `gpt-oss:20b` | **active** | 324ms | — | 2026-10-29 |
| `minimax-m2.7` | **active** | 747ms | — | 2026-10-29 |
| `minimax-m3` | **dead** | — | — | 2026-10-29 |
| `mistral-Nemo-Instruct-2407` | **active** | 523ms | — | 2026-10-29 |
| `nemotron-3-nano:30b` | **active** | 1322ms | — | 2026-10-29 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `mistral-large-4` (mistral) — 1,048,576 tokens
3. `mistral-large-4-0` (mistral) — 1,048,576 tokens
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
5. `z-ai/glm-5.3-flash` (nvidia) — 1,000,000 tokens
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262,144 tokens
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
9. `ministral-14b-2512` (mistral) — 262,144 tokens
10. `ministral-8b-2512` (mistral) — 262,144 tokens
11. `ministral-8b-latest` (mistral) — 262,144 tokens
12. `recursive/flint-v1.0:free` (openrouter) — 262,144 tokens
13. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
14. `codestral-2508` (mistral) — 256,000 tokens
15. `codestral-latest` (mistral) — 256,000 tokens
16. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
17. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
18. `glm-4.7-flash` (zai) — 200,000 tokens
19. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
20. `openai/gpt-oss-20b` (groq) — 131,072 tokens
21. `openai/gpt-oss-120b` (groq) — 131,072 tokens
22. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
23. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
24. `ministral-3b-2512` (mistral) — 131,072 tokens
25. `ministral-3b-latest` (mistral) — 131,072 tokens
26. `glm-4.5-flash` (zai) — 131,072 tokens
27. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
28. `voxtral-small-2507` (mistral) — 32,768 tokens
29. `voxtral-small-latest` (mistral) — 32,768 tokens
30. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 118ms probe
2. `openai/gpt-oss-20b` (groq) — 174ms probe
3. `nvidia/nemotron-parse-2.0` (nvidia) — 237ms probe
4. `openai/gpt-oss-120b` (groq) — 245ms probe
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 261ms probe
6. `openai/gpt-oss-20b` (nvidia) — 269ms probe
7. `allam-2-7b` (groq) — 274ms probe
8. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 279ms probe
9. `recursive/flint-v1.0:free` (openrouter) — 297ms probe
10. `gpt-oss:20b` (llm7) — 324ms probe
11. `ministral-3b-2512` (mistral) — 346ms probe
12. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 349ms probe
13. `mistral-code-fim-latest` (mistral) — 363ms probe
14. `cohere/north-mini-code:free` (openrouter) — 365ms probe
15. `voxtral-small-latest` (mistral) — 370ms probe
16. `codestral-latest` (mistral) — 374ms probe
17. `voxtral-small-2507` (mistral) — 393ms probe
18. `gemma4:31b` (ollama) — 396ms probe
19. `ministral-3b-latest` (mistral) — 399ms probe
20. `ministral-8b-latest` (mistral) — 402ms probe
21. `nvidia/ising-calibration-1.5-31b` (nvidia) — 407ms probe
22. `codestral-2508` (mistral) — 411ms probe
23. `gpt-oss:120b` (ollama) — 419ms probe
24. `mistral-code-latest` (mistral) — 427ms probe
25. `nemotron-3-super` (ollama) — 427ms probe
26. `google/diffusiongemma-26b-a4b-it` (nvidia) — 430ms probe
27. `ministral-8b-2512` (mistral) — 432ms probe
28. `gpt-oss:20b` (ollama) — 457ms probe
29. `ministral-14b-latest` (mistral) — 523ms probe
30. `mistral-Nemo-Instruct-2407` (llm7) — 523ms probe
31. `codestral-latest` (llm7) — 526ms probe
32. `beam` (ollama) — 597ms probe
33. `minimaxai/minimax-m3.1-flash` (nvidia) — 612ms probe
34. `nemotron-3-nano:30b` (ollama) — 617ms probe
35. `mistral-large-4` (mistral) — 677ms probe
36. `minimax-m2.7` (llm7) — 747ms probe
37. `ministral-14b-2512` (mistral) — 774ms probe
38. `dots-studio/dots-3-note-preview:free` (openrouter) — 788ms probe
39. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 794ms probe
40. `mistral-large-4-0` (mistral) — 867ms probe
41. `glm-4.7-flash` (zai) — 943ms probe
42. `meta/muse-glimmer-30b` (nvidia) — 1301ms probe
43. `nemotron-3-nano:30b` (llm7) — 1322ms probe
44. `nemotron-3-ultra` (ollama) — 1600ms probe
45. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 1707ms probe
46. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1927ms probe
47. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 4454ms probe
48. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 6454ms probe
49. `glm-4.5-flash` (zai) — 8293ms probe
50. `z-ai/glm-5.3-flash` (nvidia) — 27523ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `mistral-large-4` (mistral) — 1048k ctx
3. `mistral-large-4-0` (mistral) — 1048k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
9. `ministral-14b-2512` (mistral) — 262k ctx
10. `ministral-8b-2512` (mistral) — 262k ctx
11. `ministral-8b-latest` (mistral) — 262k ctx
12. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
13. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
14. `codestral-2508` (mistral) — 256k ctx
15. `codestral-latest` (mistral) — 256k ctx
16. `cohere/north-mini-code:free` (openrouter) — 256k ctx
17. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
18. `glm-4.7-flash` (zai) — 200k ctx
19. `qwen/qwen3.8-27b` (groq) — 131k ctx
20. `openai/gpt-oss-20b` (groq) — 131k ctx
21. `openai/gpt-oss-120b` (groq) — 131k ctx
22. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
23. `openai/gpt-oss-20b` (nvidia) — 131k ctx
24. `ministral-3b-2512` (mistral) — 131k ctx
25. `ministral-3b-latest` (mistral) — 131k ctx
26. `glm-4.5-flash` (zai) — 131k ctx
27. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
28. `voxtral-small-2507` (mistral) — 32k ctx
29. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `mistral-large-4` (mistral) — 1048k ctx
3. `mistral-large-4-0` (mistral) — 1048k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
9. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
10. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
11. `cohere/north-mini-code:free` (openrouter) — 256k ctx
12. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
13. `glm-4.7-flash` (zai) — 200k ctx
14. `qwen/qwen3.8-27b` (groq) — 131k ctx
15. `openai/gpt-oss-20b` (groq) — 131k ctx
16. `openai/gpt-oss-120b` (groq) — 131k ctx
17. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
18. `openai/gpt-oss-20b` (nvidia) — 131k ctx
19. `glm-4.5-flash` (zai) — 131k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `mistral-large-4` (mistral) — 1048k ctx
3. `mistral-large-4-0` (mistral) — 1048k ctx
4. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
7. `ministral-14b-2512` (mistral) — 262k ctx
8. `ministral-8b-2512` (mistral) — 262k ctx
9. `ministral-8b-latest` (mistral) — 262k ctx
10. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
11. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
12. `qwen/qwen3.8-27b` (groq) — 131k ctx
13. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
14. `ministral-3b-2512` (mistral) — 131k ctx
15. `ministral-3b-latest` (mistral) — 131k ctx
16. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


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
| llm7 | none | — | — | no quota endpoint; /v1/models shows tiers only (verified 2026-10-09) |


## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip the official probe, but a shadow probe still runs daily to audit feed accuracy (see above).
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
