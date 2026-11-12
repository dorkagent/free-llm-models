# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-12T21:22:22Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `openai/gpt-oss-20b` | **active** | 458ms | ctx 131k, tools, reasoning | 2026-11-12 |
| `qwen/qwen3.8-27b` | **active** | 235ms | ctx 131k, tools, reasoning, vision | 2026-11-12 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-12 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-12 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-12 |
| `allam-2-7b` | **active** | 243ms | ctx 4k | 2026-11-12 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-12 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-12 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-12 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-12 |
| `openai/gpt-oss-120b` | **active** | 251ms | ctx 131k, tools, reasoning | 2026-11-12 |

</details>

<details><summary><b>nvidia</b> — 12/83 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-11-12 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-11-12 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-11-12 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-11-12 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-12 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-11-12 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-11-12 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-12 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-11-12 |
| `google/codegemma-7b` | **dead** | — | — | 2026-11-12 |
| `google/deplot` | **dead** | — | — | 2026-11-12 |
| `google/gemma-2b` | **dead** | — | — | 2026-11-12 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-12 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-12 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-12 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-11-12 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-11-12 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-11-12 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-11-12 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-11-12 |
| `meta/codellama-70b` | **dead** | — | — | 2026-11-12 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 3602ms | ctx 128k, tools, vision | 2026-11-12 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-11-12 |
| `meta/llama2-70b` | **dead** | — | — | 2026-11-12 |
| `meta/muse-glimmer-30b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-12 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-11-12 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-11-12 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-11-12 |
| `minimaxai/minimax-m3.1-flash` | **active** | 366ms | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-11-12 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-11-12 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-11-12 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-11-12 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 4746ms | — | 2026-11-12 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-11-12 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-11-12 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-12 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-12 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-12 |
| `nvidia/ising-calibration-1.5-31b` | **dead** | — | — | 2026-11-12 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-11-12 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-12 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-11-12 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-11-12 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-12 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-11-12 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-12 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-12 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-11-12 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-11-12 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-11-12 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-11-12 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 229ms | ctx 256k, tools, reasoning, vision | 2026-11-12 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-11-12 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 1005ms | ctx 1000k, tools, reasoning | 2026-11-12 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 233ms | — | 2026-11-12 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-12 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-12 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-12 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 210ms | ctx 262k, tools, reasoning | 2026-11-12 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 367ms | ctx 1048k, tools, reasoning, vision | 2026-11-12 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-11-12 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-11-12 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-11-12 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-11-12 |
| `nvidia/nemotron-parse-2.0` | **active** | 209ms | — | 2026-11-12 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-11-12 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-12 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-12 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-11-12 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 251ms | — | 2026-11-12 |
| `nvidia/vila` | **dead** | — | — | 2026-11-12 |
| `openai/gpt-oss-20b` | **dead** | — | ctx 131k, tools, reasoning | 2026-11-12 |
| `poolside/laguna-xs-2.1` | **active** | 141ms | ctx 262k, tools, reasoning | 2026-11-12 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-12 |
| `stepfun-ai/step-5-preview` | **active** | 6764ms | ctx 1048k, tools, reasoning, vision | 2026-11-12 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-11-12 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-11-12 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-11-12 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-11-12 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-12 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-11-12 |

</details>

<details><summary><b>mistral</b> — 14/56 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 314ms | ctx 256k, tools | 2026-11-12 |
| `codestral-latest` | **active** | 321ms | ctx 256k, tools | 2026-11-12 |
| `mistral-code-latest` | **rate-limited** | — | — | 2026-11-12 |
| `mistral-code-fim-latest` | **active** | 350ms | — | 2026-11-12 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `ministral-14b-2512` | **active** | 348ms | ctx 262k, tools, vision | 2026-11-12 |
| `ministral-14b-latest` | **active** | 352ms | — | 2026-11-12 |
| `ministral-3b-2512` | **active** | 321ms | ctx 131k, tools, vision | 2026-11-12 |
| `ministral-3b-latest` | **active** | 329ms | ctx 131k, tools, vision | 2026-11-12 |
| `ministral-8b-2512` | **active** | 413ms | ctx 262k, tools, vision | 2026-11-12 |
| `ministral-8b-latest` | **active** | 333ms | ctx 262k, tools, vision | 2026-11-12 |
| `mistral-large-4` | **active** | 782ms | ctx 1048k, tools, reasoning, vision | 2026-11-12 |
| `mistral-large-4-0` | **active** | 720ms | ctx 1048k, tools, reasoning, vision | 2026-11-12 |
| `mistral-large-latest` | **active** | 668ms | ctx 262k, tools, vision | 2026-11-12 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-12 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-12 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-12 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-12 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-12 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-12 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-12 |
| `voxtral-small-2507` | **active** | 306ms | ctx 32k, tools | 2026-11-12 |
| `voxtral-small-latest` | **active** | 360ms | ctx 32k, tools | 2026-11-12 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-12 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-12 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-12 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-12 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-12 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-12 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-12 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-12 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-12 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-12 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-12 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-12 |

</details>

<details><summary><b>zai</b> — 1/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-11-12 |
| `glm-4.5-flash` | **active** | 696ms | ctx 131k, tools, reasoning | 2026-11-12 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-11-12 |

</details>

<details><summary><b>ollama</b> — 0/23 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `clef:27b` | **not-chat** | — | — | 2026-11-12 |
| `glm-5.3` | **dead** | — | — | 2026-11-12 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-12 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-12 |
| `nemotron-3-ultra` | **dead** | — | — | 2026-11-12 |
| `beam` | **dead** | — | — | 2026-11-12 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-12 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-12 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-12 |
| `mistral-large-4` | **dead** | — | — | 2026-11-12 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-12 |
| `minimax-m3` | **dead** | — | — | 2026-11-12 |
| `gpt-oss:120b` | **dead** | — | — | 2026-11-12 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-12 |
| `glm-5.2` | **dead** | — | — | 2026-11-12 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-12 |
| `nemotron-3-super` | **dead** | — | — | 2026-11-12 |
| `gpt-oss:20b` | **dead** | — | — | 2026-11-12 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-12 |
| `gemma4:31b` | **dead** | — | — | 2026-11-12 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-12 |
| `kimi-k3.1-pro` | **dead** | — | ctx 1048k | 2026-11-12 |
| `muse-spark-open` | **dead** | — | — | 2026-11-12 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 221ms | ctx 128k, tools | 2026-11-12 |

</details>

<details><summary><b>openrouter</b> — 5/14 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `baidu/ernie-5.5-flash-preview:free` | **active** | 1313ms | ctx 1024k, tools, reasoning | 2026-11-12 |
| `thinkingmachines/inkling-2-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-12 |
| `liquid/lfm-3-1.7b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-12 |
| `recursive/flint-v1.0:free` | **active** | 901ms | ctx 262k, tools, reasoning | 2026-11-12 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-12 |
| `apodex/apodex-1.1-mini:free` | **active** | 592ms | — | 2026-11-12 |
| `dots-studio/dots-3-note-preview:free` | **active** | 811ms | ctx 512k, tools, reasoning, vision | 2026-11-12 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-11-12 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-12 |
| `cohere/north-mini-code:free` | **active** | 196ms | ctx 256k, tools, reasoning | 2026-11-12 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-12 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-12 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-12 |

</details>

<details><summary><b>llm7</b> — 2/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-12 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-11-12 |
| `codestral-latest` | **active** | 581ms | — | 2026-11-12 |
| `gemma4:31b` | **dead** | — | — | 2026-11-12 |
| `glm-5.2` | **dead** | — | — | 2026-11-12 |
| `gpt-oss:20b` | **dead** | — | — | 2026-11-12 |
| `minimax-m2.7` | **not-chat** | — | — | 2026-11-12 |
| `minimax-m3` | **dead** | — | — | 2026-11-12 |
| `mistral-Nemo-Instruct-2407` | **active** | 477ms | — | 2026-11-12 |
| `nemotron-3-nano:30b` | **not-chat** | — | — | 2026-11-12 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `stepfun-ai/step-5-preview` (nvidia) — 1,048,576 tokens
3. `mistral-large-4` (mistral) — 1,048,576 tokens
4. `mistral-large-4-0` (mistral) — 1,048,576 tokens
5. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1,024,000 tokens
6. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
7. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
8. `minimaxai/minimax-m3.1-flash` (nvidia) — 262,144 tokens
9. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
10. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
11. `ministral-14b-2512` (mistral) — 262,144 tokens
12. `ministral-8b-2512` (mistral) — 262,144 tokens
13. `ministral-8b-latest` (mistral) — 262,144 tokens
14. `mistral-large-latest` (mistral) — 262,144 tokens
15. `recursive/flint-v1.0:free` (openrouter) — 262,144 tokens
16. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
17. `codestral-2508` (mistral) — 256,000 tokens
18. `codestral-latest` (mistral) — 256,000 tokens
19. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
20. `openai/gpt-oss-20b` (groq) — 131,072 tokens
21. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
22. `openai/gpt-oss-120b` (groq) — 131,072 tokens
23. `ministral-3b-2512` (mistral) — 131,072 tokens
24. `ministral-3b-latest` (mistral) — 131,072 tokens
25. `glm-4.5-flash` (zai) — 131,072 tokens
26. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
27. `voxtral-small-2507` (mistral) — 32,768 tokens
28. `voxtral-small-latest` (mistral) — 32,768 tokens
29. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `poolside/laguna-xs-2.1` (nvidia) — 141ms probe
2. `cohere/north-mini-code:free` (openrouter) — 196ms probe
3. `nvidia/nemotron-parse-2.0` (nvidia) — 209ms probe
4. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 210ms probe
5. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 229ms probe
6. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 233ms probe
7. `qwen/qwen3.8-27b` (groq) — 235ms probe
8. `allam-2-7b` (groq) — 243ms probe
9. `openai/gpt-oss-120b` (groq) — 251ms probe
10. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 251ms probe
11. `voxtral-small-2507` (mistral) — 306ms probe
12. `codestral-2508` (mistral) — 314ms probe
13. `codestral-latest` (mistral) — 321ms probe
14. `ministral-3b-2512` (mistral) — 321ms probe
15. `ministral-3b-latest` (mistral) — 329ms probe
16. `ministral-8b-latest` (mistral) — 333ms probe
17. `ministral-14b-2512` (mistral) — 348ms probe
18. `mistral-code-fim-latest` (mistral) — 350ms probe
19. `ministral-14b-latest` (mistral) — 352ms probe
20. `voxtral-small-latest` (mistral) — 360ms probe
21. `minimaxai/minimax-m3.1-flash` (nvidia) — 366ms probe
22. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 367ms probe
23. `ministral-8b-2512` (mistral) — 413ms probe
24. `openai/gpt-oss-20b` (groq) — 458ms probe
25. `mistral-Nemo-Instruct-2407` (llm7) — 477ms probe
26. `codestral-latest` (llm7) — 581ms probe
27. `apodex/apodex-1.1-mini:free` (openrouter) — 592ms probe
28. `mistral-large-latest` (mistral) — 668ms probe
29. `glm-4.5-flash` (zai) — 696ms probe
30. `mistral-large-4-0` (mistral) — 720ms probe
31. `mistral-large-4` (mistral) — 782ms probe
32. `dots-studio/dots-3-note-preview:free` (openrouter) — 811ms probe
33. `recursive/flint-v1.0:free` (openrouter) — 901ms probe
34. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1005ms probe
35. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1313ms probe
36. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 3602ms probe
37. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 4746ms probe
38. `stepfun-ai/step-5-preview` (nvidia) — 6764ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `mistral-large-4` (mistral) — 1048k ctx
4. `mistral-large-4-0` (mistral) — 1048k ctx
5. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
6. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
7. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
8. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
9. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
10. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
11. `ministral-14b-2512` (mistral) — 262k ctx
12. `ministral-8b-2512` (mistral) — 262k ctx
13. `ministral-8b-latest` (mistral) — 262k ctx
14. `mistral-large-latest` (mistral) — 262k ctx
15. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
16. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
17. `codestral-2508` (mistral) — 256k ctx
18. `codestral-latest` (mistral) — 256k ctx
19. `cohere/north-mini-code:free` (openrouter) — 256k ctx
20. `openai/gpt-oss-20b` (groq) — 131k ctx
21. `qwen/qwen3.8-27b` (groq) — 131k ctx
22. `openai/gpt-oss-120b` (groq) — 131k ctx
23. `ministral-3b-2512` (mistral) — 131k ctx
24. `ministral-3b-latest` (mistral) — 131k ctx
25. `glm-4.5-flash` (zai) — 131k ctx
26. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
27. `voxtral-small-2507` (mistral) — 32k ctx
28. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `mistral-large-4` (mistral) — 1048k ctx
4. `mistral-large-4-0` (mistral) — 1048k ctx
5. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
6. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
7. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
8. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
9. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
10. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
11. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
13. `cohere/north-mini-code:free` (openrouter) — 256k ctx
14. `openai/gpt-oss-20b` (groq) — 131k ctx
15. `qwen/qwen3.8-27b` (groq) — 131k ctx
16. `openai/gpt-oss-120b` (groq) — 131k ctx
17. `glm-4.5-flash` (zai) — 131k ctx

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
10. `mistral-large-latest` (mistral) — 262k ctx
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
12. `qwen/qwen3.8-27b` (groq) — 131k ctx
13. `ministral-3b-2512` (mistral) — 131k ctx
14. `ministral-3b-latest` (mistral) — 131k ctx
15. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx

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
