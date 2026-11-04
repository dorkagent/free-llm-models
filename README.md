# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-04T20:42:39Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-04 |
| `allam-2-7b` | **active** | 290ms | ctx 4k | 2026-11-04 |
| `openai/gpt-oss-20b` | **active** | 458ms | ctx 131k, tools, reasoning | 2026-11-04 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-04 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-04 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-04 |
| `openai/gpt-oss-120b` | **active** | 323ms | ctx 131k, tools, reasoning | 2026-11-04 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-04 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-04 |
| `qwen/qwen3.8-27b` | **active** | 196ms | ctx 131k, tools, reasoning, vision | 2026-11-04 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-04 |

</details>

<details><summary><b>nvidia</b> — 14/85 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-11-04 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-11-04 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-11-04 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-11-04 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-04 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-11-04 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-11-04 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-04 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-11-04 |
| `google/codegemma-7b` | **dead** | — | — | 2026-11-04 |
| `google/deplot` | **dead** | — | — | 2026-11-04 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 2628ms | ctx 250k, tools, reasoning, vision | 2026-11-04 |
| `google/gemma-2b` | **dead** | — | — | 2026-11-04 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-04 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-04 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-04 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-11-04 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-11-04 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-11-04 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-11-04 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-11-04 |
| `meta/codellama-70b` | **dead** | — | — | 2026-11-04 |
| `meta/llama-3.2-11b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-11-04 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-11-04 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-11-04 |
| `meta/llama2-70b` | **dead** | — | — | 2026-11-04 |
| `meta/muse-glimmer-30b` | **active** | 1631ms | ctx 131k, tools, reasoning, vision | 2026-11-04 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-11-04 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-11-04 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-11-04 |
| `minimaxai/minimax-m3.1-flash` | **active** | 501ms | ctx 262k, tools, reasoning, vision | 2026-11-04 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-11-04 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-11-04 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-11-04 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-11-04 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 219ms | — | 2026-11-04 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-11-04 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-04 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-11-04 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-04 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-04 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-04 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 449ms | — | 2026-11-04 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-11-04 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-04 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-11-04 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-11-04 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-04 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-11-04 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-04 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-04 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-11-04 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-11-04 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-11-04 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-11-04 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 527ms | ctx 256k, tools, reasoning, vision | 2026-11-04 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-11-04 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 710ms | ctx 1000k, tools, reasoning | 2026-11-04 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 245ms | — | 2026-11-04 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-04 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-04 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-04 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 175ms | ctx 262k, tools, reasoning | 2026-11-04 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 363ms | ctx 1048k, tools, reasoning, vision | 2026-11-04 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-11-04 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-11-04 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-11-04 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-11-04 |
| `nvidia/nemotron-parse-2.0` | **active** | 399ms | — | 2026-11-04 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-11-04 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-04 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-04 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-11-04 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 311ms | — | 2026-11-04 |
| `nvidia/vila` | **dead** | — | — | 2026-11-04 |
| `openai/gpt-oss-20b` | **dead** | — | ctx 131k, tools, reasoning | 2026-11-04 |
| `poolside/laguna-xs-2.1` | **active** | 129ms | ctx 262k, tools, reasoning | 2026-11-04 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-04 |
| `stepfun-ai/step-5-preview` | **active** | 1680ms | ctx 1048k, tools, reasoning, vision | 2026-11-04 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-11-04 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-11-04 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-11-04 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-11-04 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-04 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-11-04 |

</details>

<details><summary><b>mistral</b> — 14/55 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 407ms | ctx 256k, tools | 2026-11-04 |
| `codestral-latest` | **active** | 343ms | ctx 256k, tools | 2026-11-04 |
| `mistral-code-latest` | **active** | 704ms | — | 2026-11-04 |
| `mistral-code-fim-latest` | **active** | 435ms | — | 2026-11-04 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-04 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-04 |
| `ministral-14b-2512` | **active** | 405ms | ctx 262k, tools, vision | 2026-11-04 |
| `ministral-14b-latest` | **active** | 390ms | — | 2026-11-04 |
| `ministral-3b-2512` | **active** | 379ms | ctx 131k, tools, vision | 2026-11-04 |
| `ministral-3b-latest` | **active** | 390ms | ctx 131k, tools, vision | 2026-11-04 |
| `ministral-8b-2512` | **active** | 399ms | ctx 262k, tools, vision | 2026-11-04 |
| `ministral-8b-latest` | **active** | 414ms | ctx 262k, tools, vision | 2026-11-04 |
| `mistral-large-4` | **active** | 694ms | ctx 1048k, tools, reasoning, vision | 2026-11-04 |
| `mistral-large-4-0` | **active** | 478ms | ctx 1048k, tools, reasoning, vision | 2026-11-04 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-04 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-11-04 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-04 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-04 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-04 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-04 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-04 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-04 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-04 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-04 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-04 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-04 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-04 |
| `voxtral-small-2507` | **active** | 352ms | ctx 32k, tools | 2026-11-04 |
| `voxtral-small-latest` | **active** | 403ms | ctx 32k, tools | 2026-11-04 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-04 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-04 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-04 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-04 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-04 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-04 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-04 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-04 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-04 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-04 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-04 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-04 |

</details>

<details><summary><b>zai</b> — 3/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 26976ms | ctx 200k, tools, reasoning | 2026-11-04 |
| `glm-4.5-flash` | **active** | 702ms | ctx 131k, tools, reasoning | 2026-11-04 |
| `glm-4.6v-flash` | **active** | 687ms | ctx 128k, tools, reasoning, vision | 2026-11-04 |

</details>

<details><summary><b>ollama</b> — 7/26 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `nemotron-3-super` | **active** | 318ms | — | 2026-11-04 |
| `nemotron-3-ultra` | **active** | 588ms | — | 2026-11-04 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-04 |
| `kimi-k3.1-pro` | **dead** | — | ctx 1048k | 2026-11-04 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-04 |
| `mistral-large-4` | **dead** | — | — | 2026-11-04 |
| `muse-spark-open` | **dead** | — | — | 2026-11-04 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-04 |
| `nemotron-3-nano:30b` | **active** | 529ms | — | 2026-11-04 |
| `minimax-m2.7` | **dead** | — | — | 2026-11-04 |
| `clef:27b` | **not-chat** | — | — | 2026-11-04 |
| `glm-5.2` | **dead** | — | — | 2026-11-04 |
| `glm-5.3` | **dead** | — | — | 2026-11-04 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-04 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-04 |
| `gpt-oss:20b` | **active** | 401ms | — | 2026-11-04 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-04 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-04 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-04 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-04 |
| `gpt-oss:120b` | **active** | 374ms | — | 2026-11-04 |
| `gemma4:31b` | **active** | 306ms | — | 2026-11-04 |
| `beam` | **active** | 555ms | — | 2026-11-04 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-04 |
| `minimax-m3` | **dead** | — | — | 2026-11-04 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-11-04 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 191ms | ctx 128k, tools | 2026-11-04 |

</details>

<details><summary><b>openrouter</b> — 3/12 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `recursive/flint-v1.0:free` | **active** | 1066ms | ctx 262k, tools, reasoning | 2026-11-04 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **rate-limited** | — | ctx 262k, tools, reasoning | 2026-11-04 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-04 |
| `dots-studio/dots-3-note-preview:free` | **active** | 744ms | ctx 512k, tools, reasoning, vision | 2026-11-04 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-11-04 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-04 |
| `cohere/north-mini-code:free` | **active** | 1226ms | ctx 256k, tools, reasoning | 2026-11-04 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-04 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-04 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-04 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-04 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-04 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-04 |
| `GLM-5.3-Flash` | **dead** | — | — | 2026-11-04 |
| `codestral-latest` | **active** | 1686ms | — | 2026-11-04 |
| `gemma4:31b` | **dead** | — | — | 2026-11-04 |
| `glm-5.2` | **dead** | — | — | 2026-11-04 |
| `gpt-oss:20b` | **active** | 1025ms | — | 2026-11-04 |
| `minimax-m2.7` | **active** | 442ms | — | 2026-11-04 |
| `minimax-m3` | **dead** | — | — | 2026-11-04 |
| `mistral-Nemo-Instruct-2407` | **active** | 240ms | — | 2026-11-04 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-11-04 |

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
14. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
15. `codestral-2508` (mistral) — 256,000 tokens
16. `codestral-latest` (mistral) — 256,000 tokens
17. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
18. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
19. `glm-4.7-flash` (zai) — 200,000 tokens
20. `openai/gpt-oss-20b` (groq) — 131,072 tokens
21. `openai/gpt-oss-120b` (groq) — 131,072 tokens
22. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
23. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
24. `ministral-3b-2512` (mistral) — 131,072 tokens
25. `ministral-3b-latest` (mistral) — 131,072 tokens
26. `glm-4.5-flash` (zai) — 131,072 tokens
27. `glm-4.6v-flash` (zai) — 128,000 tokens
28. `voxtral-small-2507` (mistral) — 32,768 tokens
29. `voxtral-small-latest` (mistral) — 32,768 tokens
30. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `poolside/laguna-xs-2.1` (nvidia) — 129ms probe
2. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 175ms probe
3. `qwen/qwen3.8-27b` (groq) — 196ms probe
4. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 219ms probe
5. `mistral-Nemo-Instruct-2407` (llm7) — 240ms probe
6. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 245ms probe
7. `allam-2-7b` (groq) — 290ms probe
8. `gemma4:31b` (ollama) — 306ms probe
9. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 311ms probe
10. `nemotron-3-super` (ollama) — 318ms probe
11. `openai/gpt-oss-120b` (groq) — 323ms probe
12. `codestral-latest` (mistral) — 343ms probe
13. `voxtral-small-2507` (mistral) — 352ms probe
14. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 363ms probe
15. `gpt-oss:120b` (ollama) — 374ms probe
16. `ministral-3b-2512` (mistral) — 379ms probe
17. `ministral-14b-latest` (mistral) — 390ms probe
18. `ministral-3b-latest` (mistral) — 390ms probe
19. `nvidia/nemotron-parse-2.0` (nvidia) — 399ms probe
20. `ministral-8b-2512` (mistral) — 399ms probe
21. `gpt-oss:20b` (ollama) — 401ms probe
22. `voxtral-small-latest` (mistral) — 403ms probe
23. `ministral-14b-2512` (mistral) — 405ms probe
24. `codestral-2508` (mistral) — 407ms probe
25. `ministral-8b-latest` (mistral) — 414ms probe
26. `mistral-code-fim-latest` (mistral) — 435ms probe
27. `minimax-m2.7` (llm7) — 442ms probe
28. `nvidia/ising-calibration-1.5-31b` (nvidia) — 449ms probe
29. `openai/gpt-oss-20b` (groq) — 458ms probe
30. `mistral-large-4-0` (mistral) — 478ms probe
31. `minimaxai/minimax-m3.1-flash` (nvidia) — 501ms probe
32. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 527ms probe
33. `nemotron-3-nano:30b` (ollama) — 529ms probe
34. `beam` (ollama) — 555ms probe
35. `nemotron-3-ultra` (ollama) — 588ms probe
36. `glm-4.6v-flash` (zai) — 687ms probe
37. `mistral-large-4` (mistral) — 694ms probe
38. `glm-4.5-flash` (zai) — 702ms probe
39. `mistral-code-latest` (mistral) — 704ms probe
40. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 710ms probe
41. `dots-studio/dots-3-note-preview:free` (openrouter) — 744ms probe
42. `gpt-oss:20b` (llm7) — 1025ms probe
43. `recursive/flint-v1.0:free` (openrouter) — 1066ms probe
44. `cohere/north-mini-code:free` (openrouter) — 1226ms probe
45. `meta/muse-glimmer-30b` (nvidia) — 1631ms probe
46. `stepfun-ai/step-5-preview` (nvidia) — 1680ms probe
47. `codestral-latest` (llm7) — 1686ms probe
48. `google/diffusiongemma-26b-a4b-it` (nvidia) — 2628ms probe
49. `glm-4.7-flash` (zai) — 26976ms probe

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
14. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
15. `codestral-2508` (mistral) — 256k ctx
16. `codestral-latest` (mistral) — 256k ctx
17. `cohere/north-mini-code:free` (openrouter) — 256k ctx
18. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
19. `glm-4.7-flash` (zai) — 200k ctx
20. `openai/gpt-oss-20b` (groq) — 131k ctx
21. `openai/gpt-oss-120b` (groq) — 131k ctx
22. `qwen/qwen3.8-27b` (groq) — 131k ctx
23. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
24. `ministral-3b-2512` (mistral) — 131k ctx
25. `ministral-3b-latest` (mistral) — 131k ctx
26. `glm-4.5-flash` (zai) — 131k ctx
27. `glm-4.6v-flash` (zai) — 128k ctx
28. `voxtral-small-2507` (mistral) — 32k ctx
29. `voxtral-small-latest` (mistral) — 32k ctx

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
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
12. `cohere/north-mini-code:free` (openrouter) — 256k ctx
13. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
14. `glm-4.7-flash` (zai) — 200k ctx
15. `openai/gpt-oss-20b` (groq) — 131k ctx
16. `openai/gpt-oss-120b` (groq) — 131k ctx
17. `qwen/qwen3.8-27b` (groq) — 131k ctx
18. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
19. `glm-4.5-flash` (zai) — 131k ctx
20. `glm-4.6v-flash` (zai) — 128k ctx

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
16. `glm-4.6v-flash` (zai) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (740ms) | 1 day(s) |


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
