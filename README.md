# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-30T19:04:37Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-10-30 |
| `openai/gpt-oss-120b` | **active** | 302ms | ctx 131k, tools, reasoning | 2026-10-30 |
| `openai/gpt-oss-20b` | **active** | 258ms | ctx 131k, tools, reasoning | 2026-10-30 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-30 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-30 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-30 |
| `qwen/qwen3.8-27b` | **active** | 315ms | ctx 131k, tools, reasoning, vision | 2026-10-30 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-30 |
| `allam-2-7b` | **active** | 263ms | ctx 4k | 2026-10-30 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-10-30 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-30 |

</details>

<details><summary><b>nvidia</b> — 14/85 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-30 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-30 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-30 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-30 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-30 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-30 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-30 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-30 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-30 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-30 |
| `google/deplot` | **dead** | — | — | 2026-10-30 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 562ms | ctx 250k, tools, reasoning, vision | 2026-10-30 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-30 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-30 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-30 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-30 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-30 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-30 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-30 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-30 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-30 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-30 |
| `meta/llama-3.2-11b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-30 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 4082ms | ctx 128k, tools, vision | 2026-10-30 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-10-30 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-30 |
| `meta/muse-glimmer-30b` | **active** | 1152ms | ctx 131k, tools, reasoning, vision | 2026-10-30 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-30 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-30 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-30 |
| `minimaxai/minimax-m3.1-flash` | **active** | 715ms | ctx 262k, tools, reasoning, vision | 2026-10-30 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-30 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-30 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-10-30 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-30 |
| `mistralai/mistral-large-4-1t-a52b` | **dead** | — | — | 2026-10-30 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-30 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-30 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-30 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-30 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-30 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-30 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 155ms | — | 2026-10-30 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-30 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-30 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-30 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-30 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-30 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-30 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-30 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-30 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-10-30 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-30 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-30 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-30 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 136ms | ctx 256k, tools, reasoning, vision | 2026-10-30 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-10-30 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 392ms | ctx 1000k, tools, reasoning | 2026-10-30 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 233ms | — | 2026-10-30 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-30 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-10-30 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-10-30 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 112ms | ctx 262k, tools, reasoning | 2026-10-30 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 6286ms | ctx 1048k, tools, reasoning, vision | 2026-10-30 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-30 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-30 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-30 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-30 |
| `nvidia/nemotron-parse-2.0` | **active** | 143ms | — | 2026-10-30 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-30 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-30 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-30 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-30 |
| `nvidia/riva-translate-4b-instruct-v2` | **dead** | — | — | 2026-10-30 |
| `nvidia/vila` | **dead** | — | — | 2026-10-30 |
| `openai/gpt-oss-20b` | **active** | 277ms | ctx 131k, tools, reasoning | 2026-10-30 |
| `poolside/laguna-xs-2.1` | **active** | 429ms | ctx 262k, tools, reasoning | 2026-10-30 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-30 |
| `stepfun-ai/step-5-preview` | **active** | 338ms | ctx 1048k, tools, reasoning, vision | 2026-10-30 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-30 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-30 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-30 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-30 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-30 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-30 |

</details>

<details><summary><b>mistral</b> — 14/55 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 485ms | ctx 256k, tools | 2026-10-30 |
| `codestral-latest` | **active** | 321ms | ctx 256k, tools | 2026-10-30 |
| `mistral-code-latest` | **active** | 341ms | — | 2026-10-30 |
| `mistral-code-fim-latest` | **active** | 293ms | — | 2026-10-30 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-30 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-30 |
| `ministral-14b-2512` | **active** | 357ms | ctx 262k, tools, vision | 2026-10-30 |
| `ministral-14b-latest` | **active** | 443ms | — | 2026-10-30 |
| `ministral-3b-2512` | **active** | 418ms | ctx 131k, tools, vision | 2026-10-30 |
| `ministral-3b-latest` | **active** | 341ms | ctx 131k, tools, vision | 2026-10-30 |
| `ministral-8b-2512` | **active** | 852ms | ctx 262k, tools, vision | 2026-10-30 |
| `ministral-8b-latest` | **active** | 699ms | ctx 262k, tools, vision | 2026-10-30 |
| `mistral-large-4` | **active** | 595ms | ctx 1048k, tools, reasoning, vision | 2026-10-30 |
| `mistral-large-4-0` | **active** | 660ms | ctx 1048k, tools, reasoning, vision | 2026-10-30 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-30 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-30 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-30 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-30 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-30 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-30 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-30 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-30 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-30 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-30 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-30 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-30 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-30 |
| `voxtral-small-2507` | **active** | 320ms | ctx 32k, tools | 2026-10-30 |
| `voxtral-small-latest` | **active** | 307ms | ctx 32k, tools | 2026-10-30 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-30 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-30 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-30 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-30 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-30 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-30 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-30 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-30 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-30 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-30 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-10-30 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-10-30 |

</details>

<details><summary><b>zai</b> — 3/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 931ms | ctx 200k, tools, reasoning | 2026-10-30 |
| `glm-4.5-flash` | **active** | 3115ms | ctx 131k, tools, reasoning | 2026-10-30 |
| `glm-4.6v-flash` | **active** | 594ms | ctx 128k, tools, reasoning, vision | 2026-10-30 |

</details>

<details><summary><b>ollama</b> — 7/23 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `gemma4:31b` | **active** | 348ms | — | 2026-10-30 |
| `minimax-m3` | **dead** | — | — | 2026-10-30 |
| `glm-5.3` | **dead** | — | — | 2026-10-30 |
| `gpt-oss:120b` | **active** | 353ms | — | 2026-10-30 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-30 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-30 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-30 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-30 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-10-30 |
| `nemotron-3-super` | **active** | 379ms | — | 2026-10-30 |
| `clef:27b` | **not-chat** | — | — | 2026-10-30 |
| `nemotron-3-nano:30b` | **active** | 553ms | — | 2026-10-30 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-30 |
| `nemotron-3-ultra` | **active** | 654ms | — | 2026-10-30 |
| `beam` | **active** | 408ms | — | 2026-10-30 |
| `glm-5.2` | **dead** | — | — | 2026-10-30 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-30 |
| `mistral-large-4` | **dead** | — | — | 2026-10-30 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-10-30 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-30 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-30 |
| `muse-spark-open` | **dead** | — | — | 2026-10-30 |
| `gpt-oss:20b` | **active** | 379ms | — | 2026-10-30 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 178ms | ctx 128k, tools | 2026-10-30 |

</details>

<details><summary><b>openrouter</b> — 3/16 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `recursive/flint-v1.0:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-30 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **active** | 636ms | ctx 262k, tools, reasoning | 2026-10-30 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-30 |
| `dots-studio/dots-3-note-preview:free` | **active** | 752ms | ctx 512k, tools, reasoning, vision | 2026-10-30 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-30 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-30 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-30 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-30 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-30 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-30 |
| `cohere/north-mini-code:free` | **active** | 233ms | ctx 256k, tools, reasoning | 2026-10-30 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-30 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-30 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-30 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-30 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-30 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-30 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-10-30 |
| `codestral-latest` | **active** | 248ms | — | 2026-10-30 |
| `gemma4:31b` | **dead** | — | — | 2026-10-30 |
| `glm-5.2` | **dead** | — | — | 2026-10-30 |
| `gpt-oss:20b` | **active** | 748ms | — | 2026-10-30 |
| `minimax-m2.7` | **not-chat** | — | — | 2026-10-30 |
| `minimax-m3` | **dead** | — | — | 2026-10-30 |
| `mistral-Nemo-Instruct-2407` | **active** | 1454ms | — | 2026-10-30 |
| `nemotron-3-nano:30b` | **active** | 571ms | — | 2026-10-30 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `stepfun-ai/step-5-preview` (nvidia) — 1,048,576 tokens
3. `mistral-large-4` (mistral) — 1,048,576 tokens
4. `mistral-large-4-0` (mistral) — 1,048,576 tokens
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262,144 tokens
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
9. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
10. `ministral-14b-2512` (mistral) — 262,144 tokens
11. `ministral-8b-2512` (mistral) — 262,144 tokens
12. `ministral-8b-latest` (mistral) — 262,144 tokens
13. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262,144 tokens
14. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
15. `codestral-2508` (mistral) — 256,000 tokens
16. `codestral-latest` (mistral) — 256,000 tokens
17. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
18. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
19. `glm-4.7-flash` (zai) — 200,000 tokens
20. `openai/gpt-oss-120b` (groq) — 131,072 tokens
21. `openai/gpt-oss-20b` (groq) — 131,072 tokens
22. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
23. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
24. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
25. `ministral-3b-2512` (mistral) — 131,072 tokens
26. `ministral-3b-latest` (mistral) — 131,072 tokens
27. `glm-4.5-flash` (zai) — 131,072 tokens
28. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
29. `glm-4.6v-flash` (zai) — 128,000 tokens
30. `voxtral-small-2507` (mistral) — 32,768 tokens
31. `voxtral-small-latest` (mistral) — 32,768 tokens
32. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 112ms probe
2. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 136ms probe
3. `nvidia/nemotron-parse-2.0` (nvidia) — 143ms probe
4. `nvidia/ising-calibration-1.5-31b` (nvidia) — 155ms probe
5. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 233ms probe
6. `cohere/north-mini-code:free` (openrouter) — 233ms probe
7. `codestral-latest` (llm7) — 248ms probe
8. `openai/gpt-oss-20b` (groq) — 258ms probe
9. `allam-2-7b` (groq) — 263ms probe
10. `openai/gpt-oss-20b` (nvidia) — 277ms probe
11. `mistral-code-fim-latest` (mistral) — 293ms probe
12. `openai/gpt-oss-120b` (groq) — 302ms probe
13. `voxtral-small-latest` (mistral) — 307ms probe
14. `qwen/qwen3.8-27b` (groq) — 315ms probe
15. `voxtral-small-2507` (mistral) — 320ms probe
16. `codestral-latest` (mistral) — 321ms probe
17. `stepfun-ai/step-5-preview` (nvidia) — 338ms probe
18. `mistral-code-latest` (mistral) — 341ms probe
19. `ministral-3b-latest` (mistral) — 341ms probe
20. `gemma4:31b` (ollama) — 348ms probe
21. `gpt-oss:120b` (ollama) — 353ms probe
22. `ministral-14b-2512` (mistral) — 357ms probe
23. `nemotron-3-super` (ollama) — 379ms probe
24. `gpt-oss:20b` (ollama) — 379ms probe
25. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 392ms probe
26. `beam` (ollama) — 408ms probe
27. `ministral-3b-2512` (mistral) — 418ms probe
28. `poolside/laguna-xs-2.1` (nvidia) — 429ms probe
29. `ministral-14b-latest` (mistral) — 443ms probe
30. `codestral-2508` (mistral) — 485ms probe
31. `nemotron-3-nano:30b` (ollama) — 553ms probe
32. `google/diffusiongemma-26b-a4b-it` (nvidia) — 562ms probe
33. `nemotron-3-nano:30b` (llm7) — 571ms probe
34. `glm-4.6v-flash` (zai) — 594ms probe
35. `mistral-large-4` (mistral) — 595ms probe
36. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 636ms probe
37. `nemotron-3-ultra` (ollama) — 654ms probe
38. `mistral-large-4-0` (mistral) — 660ms probe
39. `ministral-8b-latest` (mistral) — 699ms probe
40. `minimaxai/minimax-m3.1-flash` (nvidia) — 715ms probe
41. `gpt-oss:20b` (llm7) — 748ms probe
42. `dots-studio/dots-3-note-preview:free` (openrouter) — 752ms probe
43. `ministral-8b-2512` (mistral) — 852ms probe
44. `glm-4.7-flash` (zai) — 931ms probe
45. `meta/muse-glimmer-30b` (nvidia) — 1152ms probe
46. `mistral-Nemo-Instruct-2407` (llm7) — 1454ms probe
47. `glm-4.5-flash` (zai) — 3115ms probe
48. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 4082ms probe
49. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 6286ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `mistral-large-4` (mistral) — 1048k ctx
4. `mistral-large-4-0` (mistral) — 1048k ctx
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
9. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
10. `ministral-14b-2512` (mistral) — 262k ctx
11. `ministral-8b-2512` (mistral) — 262k ctx
12. `ministral-8b-latest` (mistral) — 262k ctx
13. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
14. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
15. `codestral-2508` (mistral) — 256k ctx
16. `codestral-latest` (mistral) — 256k ctx
17. `cohere/north-mini-code:free` (openrouter) — 256k ctx
18. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
19. `glm-4.7-flash` (zai) — 200k ctx
20. `openai/gpt-oss-120b` (groq) — 131k ctx
21. `openai/gpt-oss-20b` (groq) — 131k ctx
22. `qwen/qwen3.8-27b` (groq) — 131k ctx
23. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
24. `openai/gpt-oss-20b` (nvidia) — 131k ctx
25. `ministral-3b-2512` (mistral) — 131k ctx
26. `ministral-3b-latest` (mistral) — 131k ctx
27. `glm-4.5-flash` (zai) — 131k ctx
28. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
29. `glm-4.6v-flash` (zai) — 128k ctx
30. `voxtral-small-2507` (mistral) — 32k ctx
31. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `mistral-large-4` (mistral) — 1048k ctx
4. `mistral-large-4-0` (mistral) — 1048k ctx
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
9. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
10. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
12. `cohere/north-mini-code:free` (openrouter) — 256k ctx
13. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
14. `glm-4.7-flash` (zai) — 200k ctx
15. `openai/gpt-oss-120b` (groq) — 131k ctx
16. `openai/gpt-oss-20b` (groq) — 131k ctx
17. `qwen/qwen3.8-27b` (groq) — 131k ctx
18. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
19. `openai/gpt-oss-20b` (nvidia) — 131k ctx
20. `glm-4.5-flash` (zai) — 131k ctx
21. `glm-4.6v-flash` (zai) — 128k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `mistral-large-4` (mistral) — 1048k ctx
4. `mistral-large-4-0` (mistral) — 1048k ctx
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
16. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
17. `glm-4.6v-flash` (zai) — 128k ctx

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
