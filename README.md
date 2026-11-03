# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-03T20:27:21Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `allam-2-7b` | **active** | 307ms | ctx 4k | 2026-11-03 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-03 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-03 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-03 |
| `openai/gpt-oss-20b` | **active** | 211ms | ctx 131k, tools, reasoning | 2026-11-03 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-03 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-03 |
| `qwen/qwen3.8-27b` | **active** | 147ms | ctx 131k, tools, reasoning, vision | 2026-11-03 |
| `openai/gpt-oss-120b` | **active** | 226ms | ctx 131k, tools, reasoning | 2026-11-03 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-03 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-03 |

</details>

<details><summary><b>nvidia</b> — 14/85 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-11-03 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-11-03 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-11-03 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-11-03 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-03 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-11-03 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-11-03 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-03 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-11-03 |
| `google/codegemma-7b` | **dead** | — | — | 2026-11-03 |
| `google/deplot` | **dead** | — | — | 2026-11-03 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 214ms | ctx 250k, tools, reasoning, vision | 2026-11-03 |
| `google/gemma-2b` | **dead** | — | — | 2026-11-03 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-03 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-03 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-03 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-11-03 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-11-03 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-11-03 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-11-03 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-11-03 |
| `meta/codellama-70b` | **dead** | — | — | 2026-11-03 |
| `meta/llama-3.2-11b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-11-03 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 838ms | ctx 128k, tools, vision | 2026-11-03 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-11-03 |
| `meta/llama2-70b` | **dead** | — | — | 2026-11-03 |
| `meta/muse-glimmer-30b` | **active** | 2634ms | ctx 131k, tools, reasoning, vision | 2026-11-03 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-11-03 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-11-03 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-11-03 |
| `minimaxai/minimax-m3.1-flash` | **active** | 1521ms | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-11-03 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-11-03 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-11-03 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-11-03 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 206ms | — | 2026-11-03 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-11-03 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-11-03 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-03 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-03 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-03 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 5723ms | — | 2026-11-03 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-11-03 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-03 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-11-03 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-11-03 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-03 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-11-03 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-03 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-03 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-11-03 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-11-03 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-11-03 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-11-03 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 211ms | ctx 256k, tools, reasoning, vision | 2026-11-03 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-11-03 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 547ms | ctx 1000k, tools, reasoning | 2026-11-03 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 202ms | — | 2026-11-03 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-03 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-03 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-03 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 155ms | ctx 262k, tools, reasoning | 2026-11-03 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 288ms | ctx 1048k, tools, reasoning, vision | 2026-11-03 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-11-03 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-11-03 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-11-03 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-11-03 |
| `nvidia/nemotron-parse-2.0` | **active** | 152ms | — | 2026-11-03 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-11-03 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-03 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-03 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-11-03 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 187ms | — | 2026-11-03 |
| `nvidia/vila` | **dead** | — | — | 2026-11-03 |
| `openai/gpt-oss-20b` | **dead** | — | ctx 131k, tools, reasoning | 2026-11-03 |
| `poolside/laguna-xs-2.1` | **active** | 541ms | ctx 262k, tools, reasoning | 2026-11-03 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-03 |
| `stepfun-ai/step-5-preview` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-03 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-11-03 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-11-03 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-11-03 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-11-03 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-03 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-11-03 |

</details>

<details><summary><b>mistral</b> — 14/55 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 592ms | ctx 256k, tools | 2026-11-03 |
| `codestral-latest` | **active** | 364ms | ctx 256k, tools | 2026-11-03 |
| `mistral-code-latest` | **active** | 1597ms | — | 2026-11-03 |
| `mistral-code-fim-latest` | **active** | 350ms | — | 2026-11-03 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `ministral-14b-2512` | **active** | 1020ms | ctx 262k, tools, vision | 2026-11-03 |
| `ministral-14b-latest` | **active** | 409ms | — | 2026-11-03 |
| `ministral-3b-2512` | **active** | 332ms | ctx 131k, tools, vision | 2026-11-03 |
| `ministral-3b-latest` | **active** | 701ms | ctx 131k, tools, vision | 2026-11-03 |
| `ministral-8b-2512` | **active** | 309ms | ctx 262k, tools, vision | 2026-11-03 |
| `ministral-8b-latest` | **active** | 477ms | ctx 262k, tools, vision | 2026-11-03 |
| `mistral-large-4` | **active** | 987ms | ctx 1048k, tools, reasoning, vision | 2026-11-03 |
| `mistral-large-4-0` | **active** | 717ms | ctx 1048k, tools, reasoning, vision | 2026-11-03 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-03 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-03 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-03 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-03 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-03 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-03 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-03 |
| `voxtral-small-2507` | **active** | 354ms | ctx 32k, tools | 2026-11-03 |
| `voxtral-small-latest` | **active** | 562ms | ctx 32k, tools | 2026-11-03 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-03 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-03 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-03 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-03 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-03 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-03 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-03 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-03 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-03 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-03 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-03 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-03 |

</details>

<details><summary><b>zai</b> — 3/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 767ms | ctx 200k, tools, reasoning | 2026-11-03 |
| `glm-4.5-flash` | **active** | 5721ms | ctx 131k, tools, reasoning | 2026-11-03 |
| `glm-4.6v-flash` | **active** | 514ms | ctx 128k, tools, reasoning, vision | 2026-11-03 |

</details>

<details><summary><b>ollama</b> — 6/25 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-03 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-03 |
| `mistral-large-4` | **dead** | — | — | 2026-11-03 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-03 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-03 |
| `gemma4:31b` | **active** | 455ms | — | 2026-11-03 |
| `glm-5.2` | **dead** | — | — | 2026-11-03 |
| `gpt-oss:120b` | **active** | 320ms | — | 2026-11-03 |
| `minimax-m3` | **dead** | — | — | 2026-11-03 |
| `glm-5.3` | **dead** | — | — | 2026-11-03 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-03 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-11-03 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-03 |
| `gpt-oss:20b` | **active** | 427ms | — | 2026-11-03 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-03 |
| `nemotron-3-super` | **active** | 531ms | — | 2026-11-03 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-03 |
| `nemotron-3-nano:30b` | **active** | 577ms | — | 2026-11-03 |
| `minimax-m2.7` | **dead** | — | — | 2026-11-03 |
| `muse-spark-open` | **dead** | — | — | 2026-11-03 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-03 |
| `nemotron-3-ultra` | **active** | 748ms | — | 2026-11-03 |
| `clef:27b` | **not-chat** | — | — | 2026-11-03 |
| `beam` | **dead** | — | — | 2026-11-03 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-03 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 201ms | ctx 128k, tools | 2026-11-03 |

</details>

<details><summary><b>openrouter</b> — 3/14 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `recursive/flint-v1.0:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-03 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **active** | 485ms | ctx 262k, tools, reasoning | 2026-11-03 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-03 |
| `dots-studio/dots-3-note-preview:free` | **active** | 1255ms | ctx 512k, tools, reasoning, vision | 2026-11-03 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-11-03 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-03 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-03 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-03 |
| `cohere/north-mini-code:free` | **active** | 264ms | ctx 256k, tools, reasoning | 2026-11-03 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-03 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-03 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-03 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-03 |

</details>

<details><summary><b>llm7</b> — 3/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-03 |
| `GLM-5.3-Flash` | **dead** | — | — | 2026-11-03 |
| `codestral-latest` | **active** | 736ms | — | 2026-11-03 |
| `gemma4:31b` | **dead** | — | — | 2026-11-03 |
| `glm-5.2` | **dead** | — | — | 2026-11-03 |
| `gpt-oss:20b` | **active** | 965ms | — | 2026-11-03 |
| `minimax-m2.7` | **dead** | — | — | 2026-11-03 |
| `minimax-m3` | **dead** | — | — | 2026-11-03 |
| `mistral-Nemo-Instruct-2407` | **active** | 239ms | — | 2026-11-03 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-11-03 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `mistral-large-4` (mistral) — 1,048,576 tokens
3. `mistral-large-4-0` (mistral) — 1,048,576 tokens
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
6. `minimaxai/minimax-m3.1-flash` (nvidia) — 262,144 tokens
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
8. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
9. `ministral-14b-2512` (mistral) — 262,144 tokens
10. `ministral-8b-2512` (mistral) — 262,144 tokens
11. `ministral-8b-latest` (mistral) — 262,144 tokens
12. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262,144 tokens
13. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
14. `codestral-2508` (mistral) — 256,000 tokens
15. `codestral-latest` (mistral) — 256,000 tokens
16. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
17. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
18. `glm-4.7-flash` (zai) — 200,000 tokens
19. `openai/gpt-oss-20b` (groq) — 131,072 tokens
20. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
21. `openai/gpt-oss-120b` (groq) — 131,072 tokens
22. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
23. `ministral-3b-2512` (mistral) — 131,072 tokens
24. `ministral-3b-latest` (mistral) — 131,072 tokens
25. `glm-4.5-flash` (zai) — 131,072 tokens
26. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
27. `glm-4.6v-flash` (zai) — 128,000 tokens
28. `voxtral-small-2507` (mistral) — 32,768 tokens
29. `voxtral-small-latest` (mistral) — 32,768 tokens
30. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 147ms probe
2. `nvidia/nemotron-parse-2.0` (nvidia) — 152ms probe
3. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 155ms probe
4. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 187ms probe
5. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 202ms probe
6. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 206ms probe
7. `openai/gpt-oss-20b` (groq) — 211ms probe
8. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 211ms probe
9. `google/diffusiongemma-26b-a4b-it` (nvidia) — 214ms probe
10. `openai/gpt-oss-120b` (groq) — 226ms probe
11. `mistral-Nemo-Instruct-2407` (llm7) — 239ms probe
12. `cohere/north-mini-code:free` (openrouter) — 264ms probe
13. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 288ms probe
14. `allam-2-7b` (groq) — 307ms probe
15. `ministral-8b-2512` (mistral) — 309ms probe
16. `gpt-oss:120b` (ollama) — 320ms probe
17. `ministral-3b-2512` (mistral) — 332ms probe
18. `mistral-code-fim-latest` (mistral) — 350ms probe
19. `voxtral-small-2507` (mistral) — 354ms probe
20. `codestral-latest` (mistral) — 364ms probe
21. `ministral-14b-latest` (mistral) — 409ms probe
22. `gpt-oss:20b` (ollama) — 427ms probe
23. `gemma4:31b` (ollama) — 455ms probe
24. `ministral-8b-latest` (mistral) — 477ms probe
25. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 485ms probe
26. `glm-4.6v-flash` (zai) — 514ms probe
27. `nemotron-3-super` (ollama) — 531ms probe
28. `poolside/laguna-xs-2.1` (nvidia) — 541ms probe
29. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 547ms probe
30. `voxtral-small-latest` (mistral) — 562ms probe
31. `nemotron-3-nano:30b` (ollama) — 577ms probe
32. `codestral-2508` (mistral) — 592ms probe
33. `ministral-3b-latest` (mistral) — 701ms probe
34. `mistral-large-4-0` (mistral) — 717ms probe
35. `codestral-latest` (llm7) — 736ms probe
36. `nemotron-3-ultra` (ollama) — 748ms probe
37. `glm-4.7-flash` (zai) — 767ms probe
38. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 838ms probe
39. `gpt-oss:20b` (llm7) — 965ms probe
40. `mistral-large-4` (mistral) — 987ms probe
41. `ministral-14b-2512` (mistral) — 1020ms probe
42. `dots-studio/dots-3-note-preview:free` (openrouter) — 1255ms probe
43. `minimaxai/minimax-m3.1-flash` (nvidia) — 1521ms probe
44. `mistral-code-latest` (mistral) — 1597ms probe
45. `meta/muse-glimmer-30b` (nvidia) — 2634ms probe
46. `glm-4.5-flash` (zai) — 5721ms probe
47. `nvidia/ising-calibration-1.5-31b` (nvidia) — 5723ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `mistral-large-4` (mistral) — 1048k ctx
3. `mistral-large-4-0` (mistral) — 1048k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
8. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
9. `ministral-14b-2512` (mistral) — 262k ctx
10. `ministral-8b-2512` (mistral) — 262k ctx
11. `ministral-8b-latest` (mistral) — 262k ctx
12. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
13. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
14. `codestral-2508` (mistral) — 256k ctx
15. `codestral-latest` (mistral) — 256k ctx
16. `cohere/north-mini-code:free` (openrouter) — 256k ctx
17. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
18. `glm-4.7-flash` (zai) — 200k ctx
19. `openai/gpt-oss-20b` (groq) — 131k ctx
20. `qwen/qwen3.8-27b` (groq) — 131k ctx
21. `openai/gpt-oss-120b` (groq) — 131k ctx
22. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
23. `ministral-3b-2512` (mistral) — 131k ctx
24. `ministral-3b-latest` (mistral) — 131k ctx
25. `glm-4.5-flash` (zai) — 131k ctx
26. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
27. `glm-4.6v-flash` (zai) — 128k ctx
28. `voxtral-small-2507` (mistral) — 32k ctx
29. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `mistral-large-4` (mistral) — 1048k ctx
3. `mistral-large-4-0` (mistral) — 1048k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
8. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
9. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
10. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
11. `cohere/north-mini-code:free` (openrouter) — 256k ctx
12. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
13. `glm-4.7-flash` (zai) — 200k ctx
14. `openai/gpt-oss-20b` (groq) — 131k ctx
15. `qwen/qwen3.8-27b` (groq) — 131k ctx
16. `openai/gpt-oss-120b` (groq) — 131k ctx
17. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
18. `glm-4.5-flash` (zai) — 131k ctx
19. `glm-4.6v-flash` (zai) — 128k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `mistral-large-4` (mistral) — 1048k ctx
3. `mistral-large-4-0` (mistral) — 1048k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
6. `ministral-14b-2512` (mistral) — 262k ctx
7. `ministral-8b-2512` (mistral) — 262k ctx
8. `ministral-8b-latest` (mistral) — 262k ctx
9. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
10. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
11. `qwen/qwen3.8-27b` (groq) — 131k ctx
12. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
13. `ministral-3b-2512` (mistral) — 131k ctx
14. `ministral-3b-latest` (mistral) — 131k ctx
15. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
16. `glm-4.6v-flash` (zai) — 128k ctx

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
