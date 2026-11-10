# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-10T20:44:19Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-10 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-10 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-10 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-10 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-10 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-10 |
| `allam-2-7b` | **active** | 365ms | ctx 4k | 2026-11-10 |
| `openai/gpt-oss-120b` | **active** | 281ms | ctx 131k, tools, reasoning | 2026-11-10 |
| `openai/gpt-oss-20b` | **active** | 348ms | ctx 131k, tools, reasoning | 2026-11-10 |
| `qwen/qwen3.8-27b` | **active** | 175ms | ctx 131k, tools, reasoning, vision | 2026-11-10 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-10 |

</details>

<details><summary><b>nvidia</b> — 14/84 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-11-10 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-11-10 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-11-10 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-11-10 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-10 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-11-10 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-11-10 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-10 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-11-10 |
| `google/codegemma-7b` | **dead** | — | — | 2026-11-10 |
| `google/deplot` | **dead** | — | — | 2026-11-10 |
| `google/diffusiongemma-26b-a4b-it` | **dead** | — | ctx 250k, tools, reasoning, vision | 2026-11-10 |
| `google/gemma-2b` | **dead** | — | — | 2026-11-10 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-10 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-10 |
| `google/gemma-4-31b-it` | **active** | 383ms | ctx 256k, tools, reasoning, vision | 2026-11-10 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-11-10 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-11-10 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-11-10 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-11-10 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-11-10 |
| `meta/codellama-70b` | **dead** | — | — | 2026-11-10 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-11-10 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-11-10 |
| `meta/llama2-70b` | **dead** | — | — | 2026-11-10 |
| `meta/muse-glimmer-30b` | **active** | 1512ms | ctx 131k, tools, reasoning, vision | 2026-11-10 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-11-10 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-11-10 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-11-10 |
| `minimaxai/minimax-m3.1-flash` | **active** | 4820ms | ctx 262k, tools, reasoning, vision | 2026-11-10 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-11-10 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-11-10 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-11-10 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-11-10 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 673ms | — | 2026-11-10 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-11-10 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-10 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-11-10 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-10 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-10 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-10 |
| `nvidia/ising-calibration-1.5-31b` | **dead** | — | — | 2026-11-10 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-11-10 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-10 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-11-10 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-11-10 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-10 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-11-10 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-10 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-10 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-11-10 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-11-10 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-11-10 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-11-10 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 304ms | ctx 256k, tools, reasoning, vision | 2026-11-10 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-11-10 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 1995ms | ctx 1000k, tools, reasoning | 2026-11-10 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 287ms | — | 2026-11-10 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-10 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-10 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-10 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 300ms | ctx 262k, tools, reasoning | 2026-11-10 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 407ms | ctx 1048k, tools, reasoning, vision | 2026-11-10 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-11-10 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-11-10 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-11-10 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-11-10 |
| `nvidia/nemotron-parse-2.0` | **active** | 319ms | — | 2026-11-10 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-11-10 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-10 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-10 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-11-10 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 339ms | — | 2026-11-10 |
| `nvidia/vila` | **dead** | — | — | 2026-11-10 |
| `openai/gpt-oss-20b` | **dead** | — | ctx 131k, tools, reasoning | 2026-11-10 |
| `poolside/laguna-xs-2.1` | **active** | 201ms | ctx 262k, tools, reasoning | 2026-11-10 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-10 |
| `stepfun-ai/step-5-preview` | **active** | 15499ms | ctx 1048k, tools, reasoning, vision | 2026-11-10 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-11-10 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-11-10 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-11-10 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-11-10 |
| `z-ai/glm-5.3-flash` | **active** | 9776ms | ctx 1000k, tools, reasoning, vision | 2026-11-10 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-11-10 |

</details>

<details><summary><b>mistral</b> — 12/55 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 396ms | ctx 256k, tools | 2026-11-10 |
| `codestral-latest` | **active** | 394ms | ctx 256k, tools | 2026-11-10 |
| `mistral-code-latest` | **rate-limited** | — | — | 2026-11-10 |
| `mistral-code-fim-latest` | **rate-limited** | — | — | 2026-11-10 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-10 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-10 |
| `ministral-14b-2512` | **active** | 556ms | ctx 262k, tools, vision | 2026-11-10 |
| `ministral-14b-latest` | **active** | 482ms | — | 2026-11-10 |
| `ministral-3b-2512` | **active** | 354ms | ctx 131k, tools, vision | 2026-11-10 |
| `ministral-3b-latest` | **active** | 396ms | ctx 131k, tools, vision | 2026-11-10 |
| `ministral-8b-2512` | **active** | 628ms | ctx 262k, tools, vision | 2026-11-10 |
| `ministral-8b-latest` | **active** | 449ms | ctx 262k, tools, vision | 2026-11-10 |
| `mistral-large-4` | **active** | 1170ms | ctx 1048k, tools, reasoning, vision | 2026-11-10 |
| `mistral-large-4-0` | **active** | 10919ms | ctx 1048k, tools, reasoning, vision | 2026-11-10 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-10 |
| `mistral-medium` | **rate-limited** | — | ctx 131k, tools, vision | 2026-11-10 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-10 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-10 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-10 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-10 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-10 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-10 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-10 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-10 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-10 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-10 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-10 |
| `voxtral-small-2507` | **active** | 462ms | ctx 32k, tools | 2026-11-10 |
| `voxtral-small-latest` | **active** | 452ms | ctx 32k, tools | 2026-11-10 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-10 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-10 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-10 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-10 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-10 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-10 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-10 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-10 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-10 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-10 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-10 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-10 |

</details>

<details><summary><b>zai</b> — 3/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 821ms | ctx 200k, tools, reasoning | 2026-11-10 |
| `glm-4.5-flash` | **active** | 668ms | ctx 131k, tools, reasoning | 2026-11-10 |
| `glm-4.6v-flash` | **active** | 1343ms | ctx 128k, tools, reasoning, vision | 2026-11-10 |

</details>

<details><summary><b>ollama</b> — 0/23 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-10 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-10 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-10 |
| `nemotron-3-super` | **dead** | — | — | 2026-11-10 |
| `nemotron-3-ultra` | **dead** | — | — | 2026-11-10 |
| `clef:27b` | **not-chat** | — | — | 2026-11-10 |
| `beam` | **dead** | — | — | 2026-11-10 |
| `gemma4:31b` | **dead** | — | — | 2026-11-10 |
| `gpt-oss:20b` | **dead** | — | — | 2026-11-10 |
| `glm-5.2` | **dead** | — | — | 2026-11-10 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-10 |
| `kimi-k3.1-pro` | **dead** | — | ctx 1048k | 2026-11-10 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-10 |
| `minimax-m3` | **dead** | — | — | 2026-11-10 |
| `gpt-oss:120b` | **dead** | — | — | 2026-11-10 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-10 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-10 |
| `mistral-large-4` | **dead** | — | — | 2026-11-10 |
| `muse-spark-open` | **dead** | — | — | 2026-11-10 |
| `glm-5.3` | **dead** | — | — | 2026-11-10 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-10 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-10 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-10 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 264ms | ctx 128k, tools | 2026-11-10 |

</details>

<details><summary><b>openrouter</b> — 3/13 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `thinkingmachines/inkling-2-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-10 |
| `liquid/lfm-3-1.7b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-10 |
| `recursive/flint-v1.0:free` | **active** | 697ms | ctx 262k, tools, reasoning | 2026-11-10 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **rate-limited** | — | ctx 262k, tools, reasoning | 2026-11-10 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-10 |
| `dots-studio/dots-3-note-preview:free` | **active** | 743ms | ctx 512k, tools, reasoning, vision | 2026-11-10 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-11-10 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-10 |
| `cohere/north-mini-code:free` | **active** | 221ms | ctx 256k, tools, reasoning | 2026-11-10 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-10 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-10 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-10 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-10 |

</details>

<details><summary><b>llm7</b> — 3/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-10 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-11-10 |
| `codestral-latest` | **active** | 889ms | — | 2026-11-10 |
| `gemma4:31b` | **dead** | — | — | 2026-11-10 |
| `glm-5.2` | **dead** | — | — | 2026-11-10 |
| `gpt-oss:20b` | **active** | 308ms | — | 2026-11-10 |
| `minimax-m2.7` | **not-chat** | — | — | 2026-11-10 |
| `minimax-m3` | **dead** | — | — | 2026-11-10 |
| `mistral-Nemo-Instruct-2407` | **active** | 320ms | — | 2026-11-10 |
| `nemotron-3-nano:30b` | **not-chat** | — | — | 2026-11-10 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `stepfun-ai/step-5-preview` (nvidia) — 1,048,576 tokens
3. `mistral-large-4` (mistral) — 1,048,576 tokens
4. `mistral-large-4-0` (mistral) — 1,048,576 tokens
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
6. `z-ai/glm-5.3-flash` (nvidia) — 1,000,000 tokens
7. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
8. `minimaxai/minimax-m3.1-flash` (nvidia) — 262,144 tokens
9. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
10. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
11. `ministral-14b-2512` (mistral) — 262,144 tokens
12. `ministral-8b-2512` (mistral) — 262,144 tokens
13. `ministral-8b-latest` (mistral) — 262,144 tokens
14. `recursive/flint-v1.0:free` (openrouter) — 262,144 tokens
15. `google/gemma-4-31b-it` (nvidia) — 256,000 tokens
16. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
17. `codestral-2508` (mistral) — 256,000 tokens
18. `codestral-latest` (mistral) — 256,000 tokens
19. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
20. `glm-4.7-flash` (zai) — 200,000 tokens
21. `openai/gpt-oss-120b` (groq) — 131,072 tokens
22. `openai/gpt-oss-20b` (groq) — 131,072 tokens
23. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
24. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
25. `ministral-3b-2512` (mistral) — 131,072 tokens
26. `ministral-3b-latest` (mistral) — 131,072 tokens
27. `glm-4.5-flash` (zai) — 131,072 tokens
28. `glm-4.6v-flash` (zai) — 128,000 tokens
29. `voxtral-small-2507` (mistral) — 32,768 tokens
30. `voxtral-small-latest` (mistral) — 32,768 tokens
31. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 175ms probe
2. `poolside/laguna-xs-2.1` (nvidia) — 201ms probe
3. `cohere/north-mini-code:free` (openrouter) — 221ms probe
4. `openai/gpt-oss-120b` (groq) — 281ms probe
5. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 287ms probe
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 300ms probe
7. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 304ms probe
8. `gpt-oss:20b` (llm7) — 308ms probe
9. `nvidia/nemotron-parse-2.0` (nvidia) — 319ms probe
10. `mistral-Nemo-Instruct-2407` (llm7) — 320ms probe
11. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 339ms probe
12. `openai/gpt-oss-20b` (groq) — 348ms probe
13. `ministral-3b-2512` (mistral) — 354ms probe
14. `allam-2-7b` (groq) — 365ms probe
15. `google/gemma-4-31b-it` (nvidia) — 383ms probe
16. `codestral-latest` (mistral) — 394ms probe
17. `codestral-2508` (mistral) — 396ms probe
18. `ministral-3b-latest` (mistral) — 396ms probe
19. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 407ms probe
20. `ministral-8b-latest` (mistral) — 449ms probe
21. `voxtral-small-latest` (mistral) — 452ms probe
22. `voxtral-small-2507` (mistral) — 462ms probe
23. `ministral-14b-latest` (mistral) — 482ms probe
24. `ministral-14b-2512` (mistral) — 556ms probe
25. `ministral-8b-2512` (mistral) — 628ms probe
26. `glm-4.5-flash` (zai) — 668ms probe
27. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 673ms probe
28. `recursive/flint-v1.0:free` (openrouter) — 697ms probe
29. `dots-studio/dots-3-note-preview:free` (openrouter) — 743ms probe
30. `glm-4.7-flash` (zai) — 821ms probe
31. `codestral-latest` (llm7) — 889ms probe
32. `mistral-large-4` (mistral) — 1170ms probe
33. `glm-4.6v-flash` (zai) — 1343ms probe
34. `meta/muse-glimmer-30b` (nvidia) — 1512ms probe
35. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1995ms probe
36. `minimaxai/minimax-m3.1-flash` (nvidia) — 4820ms probe
37. `z-ai/glm-5.3-flash` (nvidia) — 9776ms probe
38. `mistral-large-4-0` (mistral) — 10919ms probe
39. `stepfun-ai/step-5-preview` (nvidia) — 15499ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `mistral-large-4` (mistral) — 1048k ctx
4. `mistral-large-4-0` (mistral) — 1048k ctx
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
6. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
7. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
8. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
9. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
10. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
11. `ministral-14b-2512` (mistral) — 262k ctx
12. `ministral-8b-2512` (mistral) — 262k ctx
13. `ministral-8b-latest` (mistral) — 262k ctx
14. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
15. `google/gemma-4-31b-it` (nvidia) — 256k ctx
16. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
17. `codestral-2508` (mistral) — 256k ctx
18. `codestral-latest` (mistral) — 256k ctx
19. `cohere/north-mini-code:free` (openrouter) — 256k ctx
20. `glm-4.7-flash` (zai) — 200k ctx
21. `openai/gpt-oss-120b` (groq) — 131k ctx
22. `openai/gpt-oss-20b` (groq) — 131k ctx
23. `qwen/qwen3.8-27b` (groq) — 131k ctx
24. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
25. `ministral-3b-2512` (mistral) — 131k ctx
26. `ministral-3b-latest` (mistral) — 131k ctx
27. `glm-4.5-flash` (zai) — 131k ctx
28. `glm-4.6v-flash` (zai) — 128k ctx
29. `voxtral-small-2507` (mistral) — 32k ctx
30. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `mistral-large-4` (mistral) — 1048k ctx
4. `mistral-large-4-0` (mistral) — 1048k ctx
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
6. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
7. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
8. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
9. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
10. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
11. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
12. `google/gemma-4-31b-it` (nvidia) — 256k ctx
13. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
14. `cohere/north-mini-code:free` (openrouter) — 256k ctx
15. `glm-4.7-flash` (zai) — 200k ctx
16. `openai/gpt-oss-120b` (groq) — 131k ctx
17. `openai/gpt-oss-20b` (groq) — 131k ctx
18. `qwen/qwen3.8-27b` (groq) — 131k ctx
19. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
20. `glm-4.5-flash` (zai) — 131k ctx
21. `glm-4.6v-flash` (zai) — 128k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `mistral-large-4` (mistral) — 1048k ctx
4. `mistral-large-4-0` (mistral) — 1048k ctx
5. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
8. `ministral-14b-2512` (mistral) — 262k ctx
9. `ministral-8b-2512` (mistral) — 262k ctx
10. `ministral-8b-latest` (mistral) — 262k ctx
11. `google/gemma-4-31b-it` (nvidia) — 256k ctx
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
13. `qwen/qwen3.8-27b` (groq) — 131k ctx
14. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
15. `ministral-3b-2512` (mistral) — 131k ctx
16. `ministral-3b-latest` (mistral) — 131k ctx
17. `glm-4.6v-flash` (zai) — 128k ctx

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
