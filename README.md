# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-06T20:19:14Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-06 |
| `qwen/qwen3.8-27b` | **active** | 182ms | ctx 131k, tools, reasoning, vision | 2026-11-06 |
| `openai/gpt-oss-120b` | **active** | 211ms | ctx 131k, tools, reasoning | 2026-11-06 |
| `openai/gpt-oss-20b` | **active** | 392ms | ctx 131k, tools, reasoning | 2026-11-06 |
| `allam-2-7b` | **active** | 274ms | ctx 4k | 2026-11-06 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-06 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-06 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-06 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-06 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-06 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-06 |

</details>

<details><summary><b>nvidia</b> — 16/84 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-11-06 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-11-06 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-11-06 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-11-06 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-06 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-11-06 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-11-06 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-06 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-11-06 |
| `google/codegemma-7b` | **dead** | — | — | 2026-11-06 |
| `google/deplot` | **dead** | — | — | 2026-11-06 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 131ms | ctx 250k, tools, reasoning, vision | 2026-11-06 |
| `google/gemma-2b` | **dead** | — | — | 2026-11-06 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-06 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-06 |
| `google/gemma-4-31b-it` | **active** | 1309ms | ctx 256k, tools, reasoning, vision | 2026-11-06 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-11-06 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-11-06 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-11-06 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-11-06 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-11-06 |
| `meta/codellama-70b` | **dead** | — | — | 2026-11-06 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 6790ms | ctx 128k, tools, vision | 2026-11-06 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-11-06 |
| `meta/llama2-70b` | **dead** | — | — | 2026-11-06 |
| `meta/muse-glimmer-30b` | **active** | 1337ms | ctx 131k, tools, reasoning, vision | 2026-11-06 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-11-06 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-11-06 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-11-06 |
| `minimaxai/minimax-m3.1-flash` | **active** | 4193ms | ctx 262k, tools, reasoning, vision | 2026-11-06 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-11-06 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-11-06 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-11-06 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-11-06 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 269ms | — | 2026-11-06 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-11-06 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-06 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-11-06 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-06 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-06 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-06 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 129ms | — | 2026-11-06 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-11-06 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-06 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-11-06 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-11-06 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-06 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-11-06 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-06 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-06 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-11-06 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-11-06 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-11-06 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-11-06 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 347ms | ctx 256k, tools, reasoning, vision | 2026-11-06 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-11-06 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 1580ms | ctx 1000k, tools, reasoning | 2026-11-06 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 233ms | — | 2026-11-06 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-06 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-06 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-06 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 108ms | ctx 262k, tools, reasoning | 2026-11-06 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 864ms | ctx 1048k, tools, reasoning, vision | 2026-11-06 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-11-06 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-11-06 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-11-06 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-11-06 |
| `nvidia/nemotron-parse-2.0` | **active** | 132ms | — | 2026-11-06 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-11-06 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-06 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-06 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-11-06 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 255ms | — | 2026-11-06 |
| `nvidia/vila` | **dead** | — | — | 2026-11-06 |
| `openai/gpt-oss-20b` | **dead** | — | ctx 131k, tools, reasoning | 2026-11-06 |
| `poolside/laguna-xs-2.1` | **active** | 81ms | ctx 262k, tools, reasoning | 2026-11-06 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-06 |
| `stepfun-ai/step-5-preview` | **active** | 3741ms | ctx 1048k, tools, reasoning, vision | 2026-11-06 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-11-06 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-11-06 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-11-06 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-11-06 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-06 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-11-06 |

</details>

<details><summary><b>mistral</b> — 14/55 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 357ms | ctx 256k, tools | 2026-11-06 |
| `codestral-latest` | **active** | 383ms | ctx 256k, tools | 2026-11-06 |
| `mistral-code-latest` | **active** | 303ms | — | 2026-11-06 |
| `mistral-code-fim-latest` | **active** | 357ms | — | 2026-11-06 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-06 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-06 |
| `ministral-14b-2512` | **active** | 479ms | ctx 262k, tools, vision | 2026-11-06 |
| `ministral-14b-latest` | **active** | 374ms | — | 2026-11-06 |
| `ministral-3b-2512` | **active** | 362ms | ctx 131k, tools, vision | 2026-11-06 |
| `ministral-3b-latest` | **active** | 340ms | ctx 131k, tools, vision | 2026-11-06 |
| `ministral-8b-2512` | **active** | 365ms | ctx 262k, tools, vision | 2026-11-06 |
| `ministral-8b-latest` | **active** | 436ms | ctx 262k, tools, vision | 2026-11-06 |
| `mistral-large-4` | **active** | 710ms | ctx 1048k, tools, reasoning, vision | 2026-11-06 |
| `mistral-large-4-0` | **active** | 5203ms | ctx 1048k, tools, reasoning, vision | 2026-11-06 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-06 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-11-06 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-06 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-06 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-06 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-06 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-06 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-06 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-06 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-06 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-06 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-06 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-06 |
| `voxtral-small-2507` | **active** | 423ms | ctx 32k, tools | 2026-11-06 |
| `voxtral-small-latest` | **active** | 337ms | ctx 32k, tools | 2026-11-06 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-06 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-06 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-06 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-06 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-06 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-06 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-06 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-06 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-06 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-06 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-06 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-06 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-11-06 |
| `glm-4.5-flash` | **active** | 472ms | ctx 131k, tools, reasoning | 2026-11-06 |
| `glm-4.6v-flash` | **active** | 577ms | ctx 128k, tools, reasoning, vision | 2026-11-06 |

</details>

<details><summary><b>ollama</b> — 7/26 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `minimax-m3` | **dead** | — | — | 2026-11-06 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-06 |
| `beam` | **active** | 410ms | — | 2026-11-06 |
| `mistral-large-4` | **dead** | — | — | 2026-11-06 |
| `gemma4:31b` | **active** | 414ms | — | 2026-11-06 |
| `nemotron-3-ultra` | **active** | 1336ms | — | 2026-11-06 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-06 |
| `kimi-k3.1-pro` | **dead** | — | ctx 1048k | 2026-11-06 |
| `gpt-oss:20b` | **active** | 373ms | — | 2026-11-06 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-11-06 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-06 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-06 |
| `nemotron-3-nano:30b` | **active** | 511ms | — | 2026-11-06 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-06 |
| `clef:27b` | **not-chat** | — | — | 2026-11-06 |
| `minimax-m2.7` | **dead** | — | — | 2026-11-06 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-06 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-06 |
| `glm-5.2` | **dead** | — | — | 2026-11-06 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-06 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-06 |
| `glm-5.3` | **dead** | — | — | 2026-11-06 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-06 |
| `gpt-oss:120b` | **active** | 340ms | — | 2026-11-06 |
| `nemotron-3-super` | **active** | 338ms | — | 2026-11-06 |
| `muse-spark-open` | **dead** | — | — | 2026-11-06 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 183ms | ctx 128k, tools | 2026-11-06 |

</details>

<details><summary><b>openrouter</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `recursive/flint-v1.0:free` | **active** | 543ms | ctx 262k, tools, reasoning | 2026-11-06 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **active** | 1594ms | ctx 262k, tools, reasoning | 2026-11-06 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-06 |
| `dots-studio/dots-3-note-preview:free` | **active** | 846ms | ctx 512k, tools, reasoning, vision | 2026-11-06 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-11-06 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-06 |
| `cohere/north-mini-code:free` | **active** | 209ms | ctx 256k, tools, reasoning | 2026-11-06 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-06 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-06 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-06 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-06 |

</details>

<details><summary><b>llm7</b> — 3/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-06 |
| `GLM-5.3-Flash` | **rate-limited** | — | — | 2026-11-06 |
| `codestral-latest` | **rate-limited** | — | — | 2026-11-06 |
| `gemma4:31b` | **dead** | — | — | 2026-11-06 |
| `glm-5.2` | **dead** | — | — | 2026-11-06 |
| `gpt-oss:20b` | **active** | 205ms | — | 2026-11-06 |
| `minimax-m2.7` | **active** | 537ms | — | 2026-11-06 |
| `minimax-m3` | **dead** | — | — | 2026-11-06 |
| `mistral-Nemo-Instruct-2407` | **active** | 223ms | — | 2026-11-06 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-11-06 |

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
13. `recursive/flint-v1.0:free` (openrouter) — 262,144 tokens
14. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262,144 tokens
15. `google/gemma-4-31b-it` (nvidia) — 256,000 tokens
16. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
17. `codestral-2508` (mistral) — 256,000 tokens
18. `codestral-latest` (mistral) — 256,000 tokens
19. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
20. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
21. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
22. `openai/gpt-oss-120b` (groq) — 131,072 tokens
23. `openai/gpt-oss-20b` (groq) — 131,072 tokens
24. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
25. `ministral-3b-2512` (mistral) — 131,072 tokens
26. `ministral-3b-latest` (mistral) — 131,072 tokens
27. `glm-4.5-flash` (zai) — 131,072 tokens
28. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
29. `glm-4.6v-flash` (zai) — 128,000 tokens
30. `voxtral-small-2507` (mistral) — 32,768 tokens
31. `voxtral-small-latest` (mistral) — 32,768 tokens
32. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `poolside/laguna-xs-2.1` (nvidia) — 81ms probe
2. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 108ms probe
3. `nvidia/ising-calibration-1.5-31b` (nvidia) — 129ms probe
4. `google/diffusiongemma-26b-a4b-it` (nvidia) — 131ms probe
5. `nvidia/nemotron-parse-2.0` (nvidia) — 132ms probe
6. `qwen/qwen3.8-27b` (groq) — 182ms probe
7. `gpt-oss:20b` (llm7) — 205ms probe
8. `cohere/north-mini-code:free` (openrouter) — 209ms probe
9. `openai/gpt-oss-120b` (groq) — 211ms probe
10. `mistral-Nemo-Instruct-2407` (llm7) — 223ms probe
11. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 233ms probe
12. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 255ms probe
13. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 269ms probe
14. `allam-2-7b` (groq) — 274ms probe
15. `mistral-code-latest` (mistral) — 303ms probe
16. `voxtral-small-latest` (mistral) — 337ms probe
17. `nemotron-3-super` (ollama) — 338ms probe
18. `ministral-3b-latest` (mistral) — 340ms probe
19. `gpt-oss:120b` (ollama) — 340ms probe
20. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 347ms probe
21. `codestral-2508` (mistral) — 357ms probe
22. `mistral-code-fim-latest` (mistral) — 357ms probe
23. `ministral-3b-2512` (mistral) — 362ms probe
24. `ministral-8b-2512` (mistral) — 365ms probe
25. `gpt-oss:20b` (ollama) — 373ms probe
26. `ministral-14b-latest` (mistral) — 374ms probe
27. `codestral-latest` (mistral) — 383ms probe
28. `openai/gpt-oss-20b` (groq) — 392ms probe
29. `beam` (ollama) — 410ms probe
30. `gemma4:31b` (ollama) — 414ms probe
31. `voxtral-small-2507` (mistral) — 423ms probe
32. `ministral-8b-latest` (mistral) — 436ms probe
33. `glm-4.5-flash` (zai) — 472ms probe
34. `ministral-14b-2512` (mistral) — 479ms probe
35. `nemotron-3-nano:30b` (ollama) — 511ms probe
36. `minimax-m2.7` (llm7) — 537ms probe
37. `recursive/flint-v1.0:free` (openrouter) — 543ms probe
38. `glm-4.6v-flash` (zai) — 577ms probe
39. `mistral-large-4` (mistral) — 710ms probe
40. `dots-studio/dots-3-note-preview:free` (openrouter) — 846ms probe
41. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 864ms probe
42. `google/gemma-4-31b-it` (nvidia) — 1309ms probe
43. `nemotron-3-ultra` (ollama) — 1336ms probe
44. `meta/muse-glimmer-30b` (nvidia) — 1337ms probe
45. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1580ms probe
46. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 1594ms probe
47. `stepfun-ai/step-5-preview` (nvidia) — 3741ms probe
48. `minimaxai/minimax-m3.1-flash` (nvidia) — 4193ms probe
49. `mistral-large-4-0` (mistral) — 5203ms probe
50. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 6790ms probe

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
13. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
14. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
15. `google/gemma-4-31b-it` (nvidia) — 256k ctx
16. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
17. `codestral-2508` (mistral) — 256k ctx
18. `codestral-latest` (mistral) — 256k ctx
19. `cohere/north-mini-code:free` (openrouter) — 256k ctx
20. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
21. `qwen/qwen3.8-27b` (groq) — 131k ctx
22. `openai/gpt-oss-120b` (groq) — 131k ctx
23. `openai/gpt-oss-20b` (groq) — 131k ctx
24. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
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
10. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
11. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
12. `google/gemma-4-31b-it` (nvidia) — 256k ctx
13. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
14. `cohere/north-mini-code:free` (openrouter) — 256k ctx
15. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
16. `qwen/qwen3.8-27b` (groq) — 131k ctx
17. `openai/gpt-oss-120b` (groq) — 131k ctx
18. `openai/gpt-oss-20b` (groq) — 131k ctx
19. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
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
10. `google/gemma-4-31b-it` (nvidia) — 256k ctx
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
12. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
13. `qwen/qwen3.8-27b` (groq) — 131k ctx
14. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
15. `ministral-3b-2512` (mistral) — 131k ctx
16. `ministral-3b-latest` (mistral) — 131k ctx
17. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
18. `glm-4.6v-flash` (zai) — 128k ctx

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
| llm7 | response-headers | — | — |  |


## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip the official probe, but a shadow probe still runs daily to audit feed accuracy (see above).
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
