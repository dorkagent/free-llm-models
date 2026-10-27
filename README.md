# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-27T14:44:04Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-27 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-27 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-10-27 |
| `openai/gpt-oss-20b` | **active** | 292ms | ctx 131k, tools, reasoning | 2026-10-27 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-10-27 |
| `allam-2-7b` | **active** | 332ms | ctx 4k | 2026-10-27 |
| `openai/gpt-oss-120b` | **active** | 241ms | ctx 131k, tools, reasoning | 2026-10-27 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-27 |
| `qwen/qwen3.8-27b` | **active** | 187ms | ctx 131k, tools, reasoning, vision | 2026-10-27 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-27 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-27 |

</details>

<details><summary><b>nvidia</b> — 12/85 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-27 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-27 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-27 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-27 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-27 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-27 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-27 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-27 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-27 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-27 |
| `google/deplot` | **dead** | — | — | 2026-10-27 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 1330ms | ctx 250k, tools, reasoning, vision | 2026-10-27 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-27 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-27 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-27 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-27 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-27 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-27 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-27 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-27 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-27 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-27 |
| `meta/llama-3.2-11b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-27 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-27 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-10-27 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-27 |
| `meta/muse-glimmer-30b` | **active** | 1707ms | ctx 131k, tools, reasoning, vision | 2026-10-27 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-27 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-27 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-27 |
| `minimaxai/minimax-m3.1-flash` | **active** | 332ms | ctx 262k, tools, reasoning, vision | 2026-10-27 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-27 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-27 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-10-27 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-27 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-27 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-27 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-27 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-27 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-27 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-27 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 1677ms | — | 2026-10-27 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-27 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-27 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-27 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-27 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-27 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-27 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-27 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-27 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-10-27 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-27 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-27 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-27 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 770ms | ctx 256k, tools, reasoning, vision | 2026-10-27 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-10-27 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 2272ms | ctx 1000k, tools, reasoning | 2026-10-27 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 338ms | — | 2026-10-27 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-27 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-10-27 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-10-27 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 193ms | ctx 262k, tools, reasoning | 2026-10-27 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 383ms | ctx 1048k, tools, reasoning, vision | 2026-10-27 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-27 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-27 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-27 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-27 |
| `nvidia/nemotron-parse-2.0` | **dead** | — | — | 2026-10-27 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-27 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-27 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-27 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-27 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 9073ms | — | 2026-10-27 |
| `nvidia/vila` | **dead** | — | — | 2026-10-27 |
| `openai/gpt-oss-20b` | **active** | 343ms | ctx 131k, tools, reasoning | 2026-10-27 |
| `poolside/laguna-xs-2.1` | **active** | 23609ms | ctx 262k, tools, reasoning | 2026-10-27 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-27 |
| `stepfun-ai/step-5-preview` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-27 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-27 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-27 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-27 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-27 |
| `z-ai/glm-5.3` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-27 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-27 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-27 |

</details>

<details><summary><b>mistral</b> — 12/53 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 399ms | ctx 256k, tools | 2026-10-27 |
| `codestral-latest` | **active** | 540ms | ctx 256k, tools | 2026-10-27 |
| `mistral-code-latest` | **active** | 442ms | — | 2026-10-27 |
| `mistral-code-fim-latest` | **active** | 821ms | — | 2026-10-27 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-27 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-27 |
| `ministral-14b-2512` | **active** | 420ms | ctx 262k, tools, vision | 2026-10-27 |
| `ministral-14b-latest` | **active** | 456ms | — | 2026-10-27 |
| `ministral-3b-2512` | **active** | 1296ms | ctx 131k, tools, vision | 2026-10-27 |
| `ministral-3b-latest` | **active** | 369ms | ctx 131k, tools, vision | 2026-10-27 |
| `ministral-8b-2512` | **active** | 377ms | ctx 262k, tools, vision | 2026-10-27 |
| `ministral-8b-latest` | **active** | 487ms | ctx 262k, tools, vision | 2026-10-27 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-27 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-27 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-27 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-27 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-27 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-27 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-27 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-27 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-27 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-27 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-27 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-27 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-27 |
| `voxtral-small-2507` | **active** | 405ms | ctx 32k, tools | 2026-10-27 |
| `voxtral-small-latest` | **active** | 475ms | ctx 32k, tools | 2026-10-27 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-27 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-27 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-27 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-27 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-27 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-27 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-27 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-27 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-27 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-27 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-10-27 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-10-27 |

</details>

<details><summary><b>zai</b> — 1/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **dead** | — | ctx 200k, tools, reasoning | 2026-10-27 |
| `glm-4.5-flash` | **active** | 724ms | ctx 131k, tools, reasoning | 2026-10-27 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-27 |

</details>

<details><summary><b>ollama</b> — 7/23 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-5.3` | **dead** | — | — | 2026-10-27 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-27 |
| `beam` | **active** | 452ms | — | 2026-10-27 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-27 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-27 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-27 |
| `mistral-large-4` | **dead** | — | — | 2026-10-27 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-27 |
| `nemotron-3-nano:30b` | **active** | 1053ms | — | 2026-10-27 |
| `minimax-m3` | **dead** | — | — | 2026-10-27 |
| `clef:27b` | **not-chat** | — | — | 2026-10-27 |
| `gpt-oss:120b` | **active** | 418ms | — | 2026-10-27 |
| `nemotron-3-ultra` | **active** | 742ms | — | 2026-10-27 |
| `muse-spark-open` | **dead** | — | — | 2026-10-27 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-27 |
| `nemotron-3-super` | **active** | 380ms | — | 2026-10-27 |
| `glm-5.2` | **dead** | — | — | 2026-10-27 |
| `gpt-oss:20b` | **active** | 1308ms | — | 2026-10-27 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-10-27 |
| `gemma4:31b` | **active** | 584ms | — | 2026-10-27 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-10-27 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-27 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-27 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 205ms | ctx 128k, tools | 2026-10-27 |

</details>

<details><summary><b>openrouter</b> — 4/16 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `recursive/flint-v1.0:free` | **rate-limited** | — | ctx 262k, tools, reasoning | 2026-10-27 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **active** | 1074ms | ctx 262k, tools, reasoning | 2026-10-27 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-27 |
| `dots-studio/dots-3-note-preview:free` | **active** | 6288ms | ctx 512k, tools, reasoning, vision | 2026-10-27 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-27 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-27 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-27 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-27 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-27 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-27 |
| `cohere/north-mini-code:free` | **active** | 233ms | ctx 256k, tools, reasoning | 2026-10-27 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-27 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-27 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-27 |
| `google/gemma-4-26b-a4b-it:free` | **active** | 454ms | ctx 262k, tools, reasoning, vision | 2026-10-27 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-27 |

</details>

<details><summary><b>llm7</b> — 5/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-27 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-10-27 |
| `codestral-latest` | **active** | 242ms | — | 2026-10-27 |
| `gemma4:31b` | **dead** | — | — | 2026-10-27 |
| `glm-5.2` | **dead** | — | — | 2026-10-27 |
| `gpt-oss:20b` | **active** | 2002ms | — | 2026-10-27 |
| `minimax-m2.7` | **active** | 261ms | — | 2026-10-27 |
| `minimax-m3` | **dead** | — | — | 2026-10-27 |
| `mistral-Nemo-Instruct-2407` | **active** | 300ms | — | 2026-10-27 |
| `nemotron-3-nano:30b` | **active** | 1569ms | — | 2026-10-27 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
4. `minimaxai/minimax-m3.1-flash` (nvidia) — 262,144 tokens
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
6. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
7. `ministral-14b-2512` (mistral) — 262,144 tokens
8. `ministral-8b-2512` (mistral) — 262,144 tokens
9. `ministral-8b-latest` (mistral) — 262,144 tokens
10. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262,144 tokens
11. `google/gemma-4-26b-a4b-it:free` (openrouter) — 262,144 tokens
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
13. `codestral-2508` (mistral) — 256,000 tokens
14. `codestral-latest` (mistral) — 256,000 tokens
15. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
16. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
17. `openai/gpt-oss-20b` (groq) — 131,072 tokens
18. `openai/gpt-oss-120b` (groq) — 131,072 tokens
19. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
20. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
21. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
22. `ministral-3b-2512` (mistral) — 131,072 tokens
23. `ministral-3b-latest` (mistral) — 131,072 tokens
24. `glm-4.5-flash` (zai) — 131,072 tokens
25. `voxtral-small-2507` (mistral) — 32,768 tokens
26. `voxtral-small-latest` (mistral) — 32,768 tokens
27. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 187ms probe
2. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 193ms probe
3. `cohere/north-mini-code:free` (openrouter) — 233ms probe
4. `openai/gpt-oss-120b` (groq) — 241ms probe
5. `codestral-latest` (llm7) — 242ms probe
6. `minimax-m2.7` (llm7) — 261ms probe
7. `openai/gpt-oss-20b` (groq) — 292ms probe
8. `mistral-Nemo-Instruct-2407` (llm7) — 300ms probe
9. `allam-2-7b` (groq) — 332ms probe
10. `minimaxai/minimax-m3.1-flash` (nvidia) — 332ms probe
11. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 338ms probe
12. `openai/gpt-oss-20b` (nvidia) — 343ms probe
13. `ministral-3b-latest` (mistral) — 369ms probe
14. `ministral-8b-2512` (mistral) — 377ms probe
15. `nemotron-3-super` (ollama) — 380ms probe
16. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 383ms probe
17. `codestral-2508` (mistral) — 399ms probe
18. `voxtral-small-2507` (mistral) — 405ms probe
19. `gpt-oss:120b` (ollama) — 418ms probe
20. `ministral-14b-2512` (mistral) — 420ms probe
21. `mistral-code-latest` (mistral) — 442ms probe
22. `beam` (ollama) — 452ms probe
23. `google/gemma-4-26b-a4b-it:free` (openrouter) — 454ms probe
24. `ministral-14b-latest` (mistral) — 456ms probe
25. `voxtral-small-latest` (mistral) — 475ms probe
26. `ministral-8b-latest` (mistral) — 487ms probe
27. `codestral-latest` (mistral) — 540ms probe
28. `gemma4:31b` (ollama) — 584ms probe
29. `glm-4.5-flash` (zai) — 724ms probe
30. `nemotron-3-ultra` (ollama) — 742ms probe
31. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 770ms probe
32. `mistral-code-fim-latest` (mistral) — 821ms probe
33. `nemotron-3-nano:30b` (ollama) — 1053ms probe
34. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 1074ms probe
35. `ministral-3b-2512` (mistral) — 1296ms probe
36. `gpt-oss:20b` (ollama) — 1308ms probe
37. `google/diffusiongemma-26b-a4b-it` (nvidia) — 1330ms probe
38. `nemotron-3-nano:30b` (llm7) — 1569ms probe
39. `nvidia/ising-calibration-1.5-31b` (nvidia) — 1677ms probe
40. `meta/muse-glimmer-30b` (nvidia) — 1707ms probe
41. `gpt-oss:20b` (llm7) — 2002ms probe
42. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 2272ms probe
43. `dots-studio/dots-3-note-preview:free` (openrouter) — 6288ms probe
44. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 9073ms probe
45. `poolside/laguna-xs-2.1` (nvidia) — 23609ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
6. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
7. `ministral-14b-2512` (mistral) — 262k ctx
8. `ministral-8b-2512` (mistral) — 262k ctx
9. `ministral-8b-latest` (mistral) — 262k ctx
10. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
11. `google/gemma-4-26b-a4b-it:free` (openrouter) — 262k ctx
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
13. `codestral-2508` (mistral) — 256k ctx
14. `codestral-latest` (mistral) — 256k ctx
15. `cohere/north-mini-code:free` (openrouter) — 256k ctx
16. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
17. `openai/gpt-oss-20b` (groq) — 131k ctx
18. `openai/gpt-oss-120b` (groq) — 131k ctx
19. `qwen/qwen3.8-27b` (groq) — 131k ctx
20. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
21. `openai/gpt-oss-20b` (nvidia) — 131k ctx
22. `ministral-3b-2512` (mistral) — 131k ctx
23. `ministral-3b-latest` (mistral) — 131k ctx
24. `glm-4.5-flash` (zai) — 131k ctx
25. `voxtral-small-2507` (mistral) — 32k ctx
26. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
6. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
7. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
8. `google/gemma-4-26b-a4b-it:free` (openrouter) — 262k ctx
9. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
10. `cohere/north-mini-code:free` (openrouter) — 256k ctx
11. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
12. `openai/gpt-oss-20b` (groq) — 131k ctx
13. `openai/gpt-oss-120b` (groq) — 131k ctx
14. `qwen/qwen3.8-27b` (groq) — 131k ctx
15. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
16. `openai/gpt-oss-20b` (nvidia) — 131k ctx
17. `glm-4.5-flash` (zai) — 131k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
3. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
4. `ministral-14b-2512` (mistral) — 262k ctx
5. `ministral-8b-2512` (mistral) — 262k ctx
6. `ministral-8b-latest` (mistral) — 262k ctx
7. `google/gemma-4-26b-a4b-it:free` (openrouter) — 262k ctx
8. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
9. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
10. `qwen/qwen3.8-27b` (groq) — 131k ctx
11. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
12. `ministral-3b-2512` (mistral) — 131k ctx
13. `ministral-3b-latest` (mistral) — 131k ctx

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
