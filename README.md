# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-21T14:30:31Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-21 |
| `openai/gpt-oss-20b` | **active** | 311ms | ctx 131k, tools, reasoning | 2026-10-21 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-21 |
| `qwen/qwen3.8-27b` | **active** | 184ms | ctx 131k, tools, reasoning, vision | 2026-10-21 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-21 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-10-21 |
| `openai/gpt-oss-120b` | **active** | 166ms | ctx 131k, tools, reasoning | 2026-10-21 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-10-21 |
| `allam-2-7b` | **active** | 330ms | ctx 4k | 2026-10-21 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-21 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-21 |

</details>

<details><summary><b>nvidia</b> — 9/83 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-21 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-21 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-21 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-21 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-21 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-21 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-21 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-21 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-21 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-21 |
| `google/deplot` | **dead** | — | — | 2026-10-21 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 768ms | ctx 250k, tools, reasoning, vision | 2026-10-21 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-21 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-21 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-21 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-21 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-21 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-21 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-21 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-21 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-21 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-21 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 489ms | ctx 128k, tools, vision | 2026-10-21 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-21 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-21 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-21 |
| `meta/muse-glimmer-30b` | **active** | 14034ms | ctx 131k, tools, reasoning, vision | 2026-10-21 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-21 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-21 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-21 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-21 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-21 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-21 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-21 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-21 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-21 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-21 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-21 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-21 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-21 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 324ms | — | 2026-10-21 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-21 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-21 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-21 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-21 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-21 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-21 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-21 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-21 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-21 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-21 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-21 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-21 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-21 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-10-21 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 787ms | ctx 1000k, tools, reasoning | 2026-10-21 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-21 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-10-21 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-10-21 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 258ms | ctx 262k, tools, reasoning | 2026-10-21 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 328ms | ctx 1048k, tools, reasoning, vision | 2026-10-21 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-21 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-21 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-21 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-21 |
| `nvidia/nemotron-parse-2.0` | **dead** | — | — | 2026-10-21 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-21 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-21 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-21 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-21 |
| `nvidia/riva-translate-4b-instruct-v2` | **dead** | — | — | 2026-10-21 |
| `nvidia/vila` | **dead** | — | — | 2026-10-21 |
| `openai/gpt-oss-20b` | **active** | 11498ms | ctx 131k, tools, reasoning | 2026-10-21 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-21 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-21 |
| `stepfun-ai/step-5-preview` | **active** | 536ms | ctx 1048k, tools, reasoning, vision | 2026-10-21 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-21 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-21 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-21 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-21 |
| `z-ai/glm-5.3` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-21 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-21 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-21 |

</details>

<details><summary><b>mistral</b> — 12/53 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 411ms | ctx 256k, tools | 2026-10-21 |
| `codestral-latest` | **active** | 552ms | ctx 256k, tools | 2026-10-21 |
| `mistral-code-latest` | **active** | 393ms | — | 2026-10-21 |
| `mistral-code-fim-latest` | **active** | 412ms | — | 2026-10-21 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-21 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-21 |
| `ministral-14b-2512` | **active** | 469ms | ctx 262k, tools, vision | 2026-10-21 |
| `ministral-14b-latest` | **active** | 425ms | — | 2026-10-21 |
| `ministral-3b-2512` | **active** | 433ms | ctx 131k, tools, vision | 2026-10-21 |
| `ministral-3b-latest` | **active** | 394ms | ctx 131k, tools, vision | 2026-10-21 |
| `ministral-8b-2512` | **active** | 447ms | ctx 262k, tools, vision | 2026-10-21 |
| `ministral-8b-latest` | **active** | 453ms | ctx 262k, tools, vision | 2026-10-21 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-21 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-21 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-21 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-21 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-21 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-21 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-21 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-21 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-21 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-21 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-21 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-21 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-21 |
| `voxtral-small-2507` | **active** | 418ms | ctx 32k, tools | 2026-10-21 |
| `voxtral-small-latest` | **active** | 412ms | ctx 32k, tools | 2026-10-21 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-21 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-21 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-21 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-21 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-21 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-21 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-21 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-21 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-21 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-21 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-10-21 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-10-21 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 1638ms | ctx 200k, tools, reasoning | 2026-10-21 |
| `glm-4.5-flash` | **active** | 7320ms | ctx 131k, tools, reasoning | 2026-10-21 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-21 |

</details>

<details><summary><b>ollama</b> — 8/23 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `nemotron-3-ultra` | **active** | 1137ms | — | 2026-10-21 |
| `clef:27b` | **not-chat** | — | — | 2026-10-21 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-21 |
| `minimax-m3` | **dead** | — | — | 2026-10-21 |
| `muse-spark-open` | **dead** | — | — | 2026-10-21 |
| `nemotron-3-nano:30b` | **active** | 535ms | — | 2026-10-21 |
| `mistral-large-4` | **dead** | — | — | 2026-10-21 |
| `glm-5.3` | **dead** | — | — | 2026-10-21 |
| `gpt-oss:120b` | **active** | 569ms | — | 2026-10-21 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-21 |
| `gemma4:31b` | **active** | 642ms | — | 2026-10-21 |
| `nemotron-3-super` | **active** | 625ms | — | 2026-10-21 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-21 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-21 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-21 |
| `gpt-oss:20b` | **active** | 639ms | — | 2026-10-21 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-21 |
| `beam` | **active** | 406ms | — | 2026-10-21 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-21 |
| `glm-5.2` | **dead** | — | — | 2026-10-21 |
| `minimax-m3.1-flash` | **active** | 1101ms | — | 2026-10-21 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-21 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-10-21 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 225ms | ctx 128k, tools | 2026-10-21 |

</details>

<details><summary><b>openrouter</b> — 3/17 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `minimax/minimax-m3.1-flash:free` | **active** | 669ms | ctx 1000k, tools, reasoning, vision | 2026-10-21 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **rate-limited** | — | ctx 262k, tools, reasoning | 2026-10-21 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-21 |
| `dots-studio/dots-3-note-preview:free` | **active** | 759ms | ctx 512k, tools, reasoning, vision | 2026-10-21 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-21 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-21 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-21 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-21 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-21 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-21 |
| `cohere/north-mini-code:free` | **active** | 224ms | ctx 256k, tools, reasoning | 2026-10-21 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-21 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-21 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-21 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-21 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-21 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-21 |

</details>

<details><summary><b>llm7</b> — 5/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-21 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-10-21 |
| `codestral-latest` | **active** | 1333ms | — | 2026-10-21 |
| `gemma4:31b` | **dead** | — | — | 2026-10-21 |
| `glm-5.2` | **dead** | — | — | 2026-10-21 |
| `gpt-oss:20b` | **active** | 599ms | — | 2026-10-21 |
| `minimax-m2.7` | **active** | 1094ms | — | 2026-10-21 |
| `minimax-m3` | **dead** | — | — | 2026-10-21 |
| `mistral-Nemo-Instruct-2407` | **active** | 955ms | — | 2026-10-21 |
| `nemotron-3-nano:30b` | **active** | 1734ms | — | 2026-10-21 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `stepfun-ai/step-5-preview` (nvidia) — 1,048,576 tokens
3. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
4. `minimax/minimax-m3.1-flash:free` (openrouter) — 1,000,000 tokens
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
7. `ministral-14b-2512` (mistral) — 262,144 tokens
8. `ministral-8b-2512` (mistral) — 262,144 tokens
9. `ministral-8b-latest` (mistral) — 262,144 tokens
10. `codestral-2508` (mistral) — 256,000 tokens
11. `codestral-latest` (mistral) — 256,000 tokens
12. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
13. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
14. `glm-4.7-flash` (zai) — 200,000 tokens
15. `openai/gpt-oss-20b` (groq) — 131,072 tokens
16. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
17. `openai/gpt-oss-120b` (groq) — 131,072 tokens
18. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
19. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
20. `ministral-3b-2512` (mistral) — 131,072 tokens
21. `ministral-3b-latest` (mistral) — 131,072 tokens
22. `glm-4.5-flash` (zai) — 131,072 tokens
23. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
24. `voxtral-small-2507` (mistral) — 32,768 tokens
25. `voxtral-small-latest` (mistral) — 32,768 tokens
26. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `openai/gpt-oss-120b` (groq) — 166ms probe
2. `qwen/qwen3.8-27b` (groq) — 184ms probe
3. `cohere/north-mini-code:free` (openrouter) — 224ms probe
4. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 258ms probe
5. `openai/gpt-oss-20b` (groq) — 311ms probe
6. `nvidia/ising-calibration-1.5-31b` (nvidia) — 324ms probe
7. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 328ms probe
8. `allam-2-7b` (groq) — 330ms probe
9. `mistral-code-latest` (mistral) — 393ms probe
10. `ministral-3b-latest` (mistral) — 394ms probe
11. `beam` (ollama) — 406ms probe
12. `codestral-2508` (mistral) — 411ms probe
13. `mistral-code-fim-latest` (mistral) — 412ms probe
14. `voxtral-small-latest` (mistral) — 412ms probe
15. `voxtral-small-2507` (mistral) — 418ms probe
16. `ministral-14b-latest` (mistral) — 425ms probe
17. `ministral-3b-2512` (mistral) — 433ms probe
18. `ministral-8b-2512` (mistral) — 447ms probe
19. `ministral-8b-latest` (mistral) — 453ms probe
20. `ministral-14b-2512` (mistral) — 469ms probe
21. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 489ms probe
22. `nemotron-3-nano:30b` (ollama) — 535ms probe
23. `stepfun-ai/step-5-preview` (nvidia) — 536ms probe
24. `codestral-latest` (mistral) — 552ms probe
25. `gpt-oss:120b` (ollama) — 569ms probe
26. `gpt-oss:20b` (llm7) — 599ms probe
27. `nemotron-3-super` (ollama) — 625ms probe
28. `gpt-oss:20b` (ollama) — 639ms probe
29. `gemma4:31b` (ollama) — 642ms probe
30. `minimax/minimax-m3.1-flash:free` (openrouter) — 669ms probe
31. `dots-studio/dots-3-note-preview:free` (openrouter) — 759ms probe
32. `google/diffusiongemma-26b-a4b-it` (nvidia) — 768ms probe
33. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 787ms probe
34. `mistral-Nemo-Instruct-2407` (llm7) — 955ms probe
35. `minimax-m2.7` (llm7) — 1094ms probe
36. `minimax-m3.1-flash` (ollama) — 1101ms probe
37. `nemotron-3-ultra` (ollama) — 1137ms probe
38. `codestral-latest` (llm7) — 1333ms probe
39. `glm-4.7-flash` (zai) — 1638ms probe
40. `nemotron-3-nano:30b` (llm7) — 1734ms probe
41. `glm-4.5-flash` (zai) — 7320ms probe
42. `openai/gpt-oss-20b` (nvidia) — 11498ms probe
43. `meta/muse-glimmer-30b` (nvidia) — 14034ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
4. `minimax/minimax-m3.1-flash:free` (openrouter) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `ministral-14b-2512` (mistral) — 262k ctx
8. `ministral-8b-2512` (mistral) — 262k ctx
9. `ministral-8b-latest` (mistral) — 262k ctx
10. `codestral-2508` (mistral) — 256k ctx
11. `codestral-latest` (mistral) — 256k ctx
12. `cohere/north-mini-code:free` (openrouter) — 256k ctx
13. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
14. `glm-4.7-flash` (zai) — 200k ctx
15. `openai/gpt-oss-20b` (groq) — 131k ctx
16. `qwen/qwen3.8-27b` (groq) — 131k ctx
17. `openai/gpt-oss-120b` (groq) — 131k ctx
18. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
19. `openai/gpt-oss-20b` (nvidia) — 131k ctx
20. `ministral-3b-2512` (mistral) — 131k ctx
21. `ministral-3b-latest` (mistral) — 131k ctx
22. `glm-4.5-flash` (zai) — 131k ctx
23. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
24. `voxtral-small-2507` (mistral) — 32k ctx
25. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
4. `minimax/minimax-m3.1-flash:free` (openrouter) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `cohere/north-mini-code:free` (openrouter) — 256k ctx
8. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
9. `glm-4.7-flash` (zai) — 200k ctx
10. `openai/gpt-oss-20b` (groq) — 131k ctx
11. `qwen/qwen3.8-27b` (groq) — 131k ctx
12. `openai/gpt-oss-120b` (groq) — 131k ctx
13. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
14. `openai/gpt-oss-20b` (nvidia) — 131k ctx
15. `glm-4.5-flash` (zai) — 131k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `minimax/minimax-m3.1-flash:free` (openrouter) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `ministral-14b-2512` (mistral) — 262k ctx
6. `ministral-8b-2512` (mistral) — 262k ctx
7. `ministral-8b-latest` (mistral) — 262k ctx
8. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
9. `qwen/qwen3.8-27b` (groq) — 131k ctx
10. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
11. `ministral-3b-2512` (mistral) — 131k ctx
12. `ministral-3b-latest` (mistral) — 131k ctx
13. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx

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
