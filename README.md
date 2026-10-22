# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-22T14:31:45Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-10-22 |
| `allam-2-7b` | **active** | 311ms | ctx 4k | 2026-10-22 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-22 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-22 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-10-22 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-22 |
| `qwen/qwen3.8-27b` | **active** | 125ms | ctx 131k, tools, reasoning, vision | 2026-10-22 |
| `openai/gpt-oss-20b` | **active** | 258ms | ctx 131k, tools, reasoning | 2026-10-22 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-22 |
| `openai/gpt-oss-120b` | **active** | 267ms | ctx 131k, tools, reasoning | 2026-10-22 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-22 |

</details>

<details><summary><b>nvidia</b> — 10/83 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-22 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-22 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-22 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-22 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-22 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-22 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-22 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-22 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-22 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-22 |
| `google/deplot` | **dead** | — | — | 2026-10-22 |
| `google/diffusiongemma-26b-a4b-it` | **dead** | — | ctx 250k, tools, reasoning, vision | 2026-10-22 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-22 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-22 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-22 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-22 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-22 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-22 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-22 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-22 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-22 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-22 |
| `meta/llama-3.2-11b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-22 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-22 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-10-22 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-22 |
| `meta/muse-glimmer-30b` | **active** | 26390ms | ctx 131k, tools, reasoning, vision | 2026-10-22 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-22 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-22 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-22 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-22 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-22 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-10-22 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-22 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-22 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-22 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-22 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-22 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-22 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 550ms | — | 2026-10-22 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-22 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-22 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-22 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-22 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-22 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-22 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-22 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-22 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-10-22 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-22 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-22 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-22 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-22 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-10-22 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 519ms | ctx 1000k, tools, reasoning | 2026-10-22 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-22 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-10-22 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-10-22 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 283ms | ctx 262k, tools, reasoning | 2026-10-22 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 409ms | ctx 1048k, tools, reasoning, vision | 2026-10-22 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-22 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-22 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-22 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-22 |
| `nvidia/nemotron-parse-2.0` | **active** | 314ms | — | 2026-10-22 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-22 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-22 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-22 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-22 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 1100ms | — | 2026-10-22 |
| `nvidia/vila` | **dead** | — | — | 2026-10-22 |
| `openai/gpt-oss-20b` | **active** | 879ms | ctx 131k, tools, reasoning | 2026-10-22 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-22 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-22 |
| `stepfun-ai/step-5-preview` | **active** | 670ms | ctx 1048k, tools, reasoning, vision | 2026-10-22 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-22 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-22 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-22 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-22 |
| `z-ai/glm-5.3` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-22 |
| `z-ai/glm-5.3-flash` | **active** | 12056ms | ctx 1000k, tools, reasoning, vision | 2026-10-22 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-22 |

</details>

<details><summary><b>mistral</b> — 12/53 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 413ms | ctx 256k, tools | 2026-10-22 |
| `codestral-latest` | **active** | 686ms | ctx 256k, tools | 2026-10-22 |
| `mistral-code-latest` | **active** | 379ms | — | 2026-10-22 |
| `mistral-code-fim-latest` | **active** | 401ms | — | 2026-10-22 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `ministral-14b-2512` | **active** | 490ms | ctx 262k, tools, vision | 2026-10-22 |
| `ministral-14b-latest` | **active** | 413ms | — | 2026-10-22 |
| `ministral-3b-2512` | **active** | 458ms | ctx 131k, tools, vision | 2026-10-22 |
| `ministral-3b-latest` | **active** | 419ms | ctx 131k, tools, vision | 2026-10-22 |
| `ministral-8b-2512` | **active** | 739ms | ctx 262k, tools, vision | 2026-10-22 |
| `ministral-8b-latest` | **active** | 366ms | ctx 262k, tools, vision | 2026-10-22 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-22 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-22 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-22 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-22 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-22 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-22 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-22 |
| `voxtral-small-2507` | **active** | 434ms | ctx 32k, tools | 2026-10-22 |
| `voxtral-small-latest` | **active** | 399ms | ctx 32k, tools | 2026-10-22 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-22 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-22 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-22 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-22 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-22 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-22 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-22 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-22 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-22 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-22 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-10-22 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-10-22 |

</details>

<details><summary><b>zai</b> — 1/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-10-22 |
| `glm-4.5-flash` | **active** | 10165ms | ctx 131k, tools, reasoning | 2026-10-22 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-22 |

</details>

<details><summary><b>ollama</b> — 8/23 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-22 |
| `gemma4:31b` | **active** | 533ms | — | 2026-10-22 |
| `nemotron-3-super` | **active** | 428ms | — | 2026-10-22 |
| `clef:27b` | **not-chat** | — | — | 2026-10-22 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-22 |
| `minimax-m3.1-flash` | **active** | 1206ms | — | 2026-10-22 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-22 |
| `gpt-oss:20b` | **active** | 616ms | — | 2026-10-22 |
| `glm-5.3` | **dead** | — | — | 2026-10-22 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-22 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-22 |
| `nemotron-3-ultra` | **active** | 698ms | — | 2026-10-22 |
| `beam` | **active** | 765ms | — | 2026-10-22 |
| `muse-spark-open` | **dead** | — | — | 2026-10-22 |
| `glm-5.2` | **dead** | — | — | 2026-10-22 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-22 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-22 |
| `minimax-m3` | **dead** | — | — | 2026-10-22 |
| `mistral-large-4` | **dead** | — | — | 2026-10-22 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-10-22 |
| `gpt-oss:120b` | **active** | 1038ms | — | 2026-10-22 |
| `nemotron-3-nano:30b` | **active** | 1258ms | — | 2026-10-22 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-22 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 197ms | ctx 128k, tools | 2026-10-22 |

</details>

<details><summary><b>openrouter</b> — 3/17 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `recursive/flint-v1.0:free` | **active** | 742ms | ctx 262k, tools, reasoning | 2026-10-22 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **rate-limited** | — | ctx 262k, tools, reasoning | 2026-10-22 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-22 |
| `dots-studio/dots-3-note-preview:free` | **active** | 691ms | ctx 512k, tools, reasoning, vision | 2026-10-22 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-22 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-22 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-22 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-22 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-22 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-22 |
| `cohere/north-mini-code:free` | **active** | 242ms | ctx 256k, tools, reasoning | 2026-10-22 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-22 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-22 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-22 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-22 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-22 |

</details>

<details><summary><b>llm7</b> — 2/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-22 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-10-22 |
| `codestral-latest` | **active** | 550ms | — | 2026-10-22 |
| `gemma4:31b` | **dead** | — | — | 2026-10-22 |
| `glm-5.2` | **dead** | — | — | 2026-10-22 |
| `gpt-oss:20b` | **active** | 502ms | — | 2026-10-22 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-22 |
| `minimax-m3` | **dead** | — | — | 2026-10-22 |
| `mistral-Nemo-Instruct-2407` | **rate-limited** | — | — | 2026-10-22 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-10-22 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `stepfun-ai/step-5-preview` (nvidia) — 1,048,576 tokens
3. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
4. `z-ai/glm-5.3-flash` (nvidia) — 1,000,000 tokens
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
7. `ministral-14b-2512` (mistral) — 262,144 tokens
8. `ministral-8b-2512` (mistral) — 262,144 tokens
9. `ministral-8b-latest` (mistral) — 262,144 tokens
10. `recursive/flint-v1.0:free` (openrouter) — 262,144 tokens
11. `codestral-2508` (mistral) — 256,000 tokens
12. `codestral-latest` (mistral) — 256,000 tokens
13. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
14. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
15. `openai/gpt-oss-20b` (groq) — 131,072 tokens
16. `openai/gpt-oss-120b` (groq) — 131,072 tokens
17. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
18. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
19. `ministral-3b-2512` (mistral) — 131,072 tokens
20. `ministral-3b-latest` (mistral) — 131,072 tokens
21. `glm-4.5-flash` (zai) — 131,072 tokens
22. `voxtral-small-2507` (mistral) — 32,768 tokens
23. `voxtral-small-latest` (mistral) — 32,768 tokens
24. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 125ms probe
2. `cohere/north-mini-code:free` (openrouter) — 242ms probe
3. `openai/gpt-oss-20b` (groq) — 258ms probe
4. `openai/gpt-oss-120b` (groq) — 267ms probe
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 283ms probe
6. `allam-2-7b` (groq) — 311ms probe
7. `nvidia/nemotron-parse-2.0` (nvidia) — 314ms probe
8. `ministral-8b-latest` (mistral) — 366ms probe
9. `mistral-code-latest` (mistral) — 379ms probe
10. `voxtral-small-latest` (mistral) — 399ms probe
11. `mistral-code-fim-latest` (mistral) — 401ms probe
12. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 409ms probe
13. `codestral-2508` (mistral) — 413ms probe
14. `ministral-14b-latest` (mistral) — 413ms probe
15. `ministral-3b-latest` (mistral) — 419ms probe
16. `nemotron-3-super` (ollama) — 428ms probe
17. `voxtral-small-2507` (mistral) — 434ms probe
18. `ministral-3b-2512` (mistral) — 458ms probe
19. `ministral-14b-2512` (mistral) — 490ms probe
20. `gpt-oss:20b` (llm7) — 502ms probe
21. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 519ms probe
22. `gemma4:31b` (ollama) — 533ms probe
23. `nvidia/ising-calibration-1.5-31b` (nvidia) — 550ms probe
24. `codestral-latest` (llm7) — 550ms probe
25. `gpt-oss:20b` (ollama) — 616ms probe
26. `stepfun-ai/step-5-preview` (nvidia) — 670ms probe
27. `codestral-latest` (mistral) — 686ms probe
28. `dots-studio/dots-3-note-preview:free` (openrouter) — 691ms probe
29. `nemotron-3-ultra` (ollama) — 698ms probe
30. `ministral-8b-2512` (mistral) — 739ms probe
31. `recursive/flint-v1.0:free` (openrouter) — 742ms probe
32. `beam` (ollama) — 765ms probe
33. `openai/gpt-oss-20b` (nvidia) — 879ms probe
34. `gpt-oss:120b` (ollama) — 1038ms probe
35. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 1100ms probe
36. `minimax-m3.1-flash` (ollama) — 1206ms probe
37. `nemotron-3-nano:30b` (ollama) — 1258ms probe
38. `glm-4.5-flash` (zai) — 10165ms probe
39. `z-ai/glm-5.3-flash` (nvidia) — 12056ms probe
40. `meta/muse-glimmer-30b` (nvidia) — 26390ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
4. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `ministral-14b-2512` (mistral) — 262k ctx
8. `ministral-8b-2512` (mistral) — 262k ctx
9. `ministral-8b-latest` (mistral) — 262k ctx
10. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
11. `codestral-2508` (mistral) — 256k ctx
12. `codestral-latest` (mistral) — 256k ctx
13. `cohere/north-mini-code:free` (openrouter) — 256k ctx
14. `qwen/qwen3.8-27b` (groq) — 131k ctx
15. `openai/gpt-oss-20b` (groq) — 131k ctx
16. `openai/gpt-oss-120b` (groq) — 131k ctx
17. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
18. `openai/gpt-oss-20b` (nvidia) — 131k ctx
19. `ministral-3b-2512` (mistral) — 131k ctx
20. `ministral-3b-latest` (mistral) — 131k ctx
21. `glm-4.5-flash` (zai) — 131k ctx
22. `voxtral-small-2507` (mistral) — 32k ctx
23. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
4. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
8. `cohere/north-mini-code:free` (openrouter) — 256k ctx
9. `qwen/qwen3.8-27b` (groq) — 131k ctx
10. `openai/gpt-oss-20b` (groq) — 131k ctx
11. `openai/gpt-oss-120b` (groq) — 131k ctx
12. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
13. `openai/gpt-oss-20b` (nvidia) — 131k ctx
14. `glm-4.5-flash` (zai) — 131k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `ministral-14b-2512` (mistral) — 262k ctx
6. `ministral-8b-2512` (mistral) — 262k ctx
7. `ministral-8b-latest` (mistral) — 262k ctx
8. `qwen/qwen3.8-27b` (groq) — 131k ctx
9. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
10. `ministral-3b-2512` (mistral) — 131k ctx
11. `ministral-3b-latest` (mistral) — 131k ctx

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
