# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-11T21:10:00Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `allam-2-7b` | **active** | 253ms | ctx 4k | 2026-11-11 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-11 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-11 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-11 |
| `openai/gpt-oss-120b` | **active** | 164ms | ctx 131k, tools, reasoning | 2026-11-11 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-11 |
| `qwen/qwen3.8-27b` | **active** | 250ms | ctx 131k, tools, reasoning, vision | 2026-11-11 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-11 |
| `openai/gpt-oss-20b` | **active** | 256ms | ctx 131k, tools, reasoning | 2026-11-11 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-11 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-11 |

</details>

<details><summary><b>nvidia</b> — 12/84 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-11-11 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-11-11 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-11-11 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-11-11 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-11 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-11-11 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-11-11 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-11 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-11-11 |
| `google/codegemma-7b` | **dead** | — | — | 2026-11-11 |
| `google/deplot` | **dead** | — | — | 2026-11-11 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 18678ms | ctx 250k, tools, reasoning, vision | 2026-11-11 |
| `google/gemma-2b` | **dead** | — | — | 2026-11-11 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-11 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-11 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-11 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-11-11 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-11-11 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-11-11 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-11-11 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-11-11 |
| `meta/codellama-70b` | **dead** | — | — | 2026-11-11 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 19126ms | ctx 128k, tools, vision | 2026-11-11 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-11-11 |
| `meta/llama2-70b` | **dead** | — | — | 2026-11-11 |
| `meta/muse-glimmer-30b` | **not-chat** | — | ctx 131k, tools, reasoning, vision | 2026-11-11 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-11-11 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-11-11 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-11-11 |
| `minimaxai/minimax-m3.1-flash` | **active** | 1762ms | ctx 262k, tools, reasoning, vision | 2026-11-11 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-11-11 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-11-11 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-11-11 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-11-11 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 172ms | — | 2026-11-11 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-11-11 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-11 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-11-11 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-11 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-11 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-11 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 5781ms | — | 2026-11-11 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-11-11 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-11 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-11-11 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-11-11 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-11 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-11-11 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-11 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-11 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-11-11 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-11-11 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-11-11 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-11-11 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 172ms | ctx 256k, tools, reasoning, vision | 2026-11-11 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-11-11 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 4524ms | ctx 1000k, tools, reasoning | 2026-11-11 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 212ms | — | 2026-11-11 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-11 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-11 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-11 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 555ms | ctx 262k, tools, reasoning | 2026-11-11 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-11 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-11-11 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-11-11 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-11-11 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-11-11 |
| `nvidia/nemotron-parse-2.0` | **active** | 132ms | — | 2026-11-11 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-11-11 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-11 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-11 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-11-11 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 167ms | — | 2026-11-11 |
| `nvidia/vila` | **dead** | — | — | 2026-11-11 |
| `openai/gpt-oss-20b` | **dead** | — | ctx 131k, tools, reasoning | 2026-11-11 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-11 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-11 |
| `stepfun-ai/step-5-preview` | **active** | 347ms | ctx 1048k, tools, reasoning, vision | 2026-11-11 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-11-11 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-11-11 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-11-11 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-11-11 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-11 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-11-11 |

</details>

<details><summary><b>mistral</b> — 11/55 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 343ms | ctx 256k, tools | 2026-11-11 |
| `codestral-latest` | **active** | 330ms | ctx 256k, tools | 2026-11-11 |
| `mistral-code-latest` | **rate-limited** | — | — | 2026-11-11 |
| `mistral-code-fim-latest` | **rate-limited** | — | — | 2026-11-11 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-11 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-11 |
| `ministral-14b-2512` | **rate-limited** | — | ctx 262k, tools, vision | 2026-11-11 |
| `ministral-14b-latest` | **active** | 493ms | — | 2026-11-11 |
| `ministral-3b-2512` | **active** | 266ms | ctx 131k, tools, vision | 2026-11-11 |
| `ministral-3b-latest` | **active** | 338ms | ctx 131k, tools, vision | 2026-11-11 |
| `ministral-8b-2512` | **active** | 444ms | ctx 262k, tools, vision | 2026-11-11 |
| `ministral-8b-latest` | **active** | 315ms | ctx 262k, tools, vision | 2026-11-11 |
| `mistral-large-4` | **active** | 1081ms | ctx 1048k, tools, reasoning, vision | 2026-11-11 |
| `mistral-large-4-0` | **active** | 1059ms | ctx 1048k, tools, reasoning, vision | 2026-11-11 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-11 |
| `mistral-medium` | **rate-limited** | — | ctx 131k, tools, vision | 2026-11-11 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-11 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-11 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-11 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-11 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-11 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-11 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-11 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-11 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-11 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-11 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-11 |
| `voxtral-small-2507` | **active** | 358ms | ctx 32k, tools | 2026-11-11 |
| `voxtral-small-latest` | **active** | 407ms | ctx 32k, tools | 2026-11-11 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-11 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-11 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-11 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-11 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-11 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-11 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-11 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-11 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-11 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-11 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-11 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-11 |

</details>

<details><summary><b>zai</b> — 3/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 884ms | ctx 200k, tools, reasoning | 2026-11-11 |
| `glm-4.5-flash` | **active** | 636ms | ctx 131k, tools, reasoning | 2026-11-11 |
| `glm-4.6v-flash` | **active** | 2138ms | ctx 128k, tools, reasoning, vision | 2026-11-11 |

</details>

<details><summary><b>ollama</b> — 0/23 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-11 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-11 |
| `gpt-oss:120b` | **dead** | — | — | 2026-11-11 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-11 |
| `mistral-large-4` | **dead** | — | — | 2026-11-11 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-11 |
| `gemma4:31b` | **dead** | — | — | 2026-11-11 |
| `muse-spark-open` | **dead** | — | — | 2026-11-11 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-11 |
| `nemotron-3-super` | **dead** | — | — | 2026-11-11 |
| `nemotron-3-ultra` | **dead** | — | — | 2026-11-11 |
| `glm-5.2` | **dead** | — | — | 2026-11-11 |
| `glm-5.3` | **dead** | — | — | 2026-11-11 |
| `beam` | **dead** | — | — | 2026-11-11 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-11 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-11 |
| `kimi-k3.1-pro` | **dead** | — | ctx 1048k | 2026-11-11 |
| `clef:27b` | **not-chat** | — | — | 2026-11-11 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-11 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-11 |
| `gpt-oss:20b` | **dead** | — | — | 2026-11-11 |
| `minimax-m3` | **dead** | — | — | 2026-11-11 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-11 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 155ms | ctx 128k, tools | 2026-11-11 |

</details>

<details><summary><b>openrouter</b> — 4/13 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `baidu/ernie-5.5-flash-preview:free` | **active** | 1103ms | ctx 1024k, tools, reasoning | 2026-11-11 |
| `thinkingmachines/inkling-2-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-11 |
| `liquid/lfm-3-1.7b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-11 |
| `recursive/flint-v1.0:free` | **active** | 275ms | ctx 262k, tools, reasoning | 2026-11-11 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-11 |
| `dots-studio/dots-3-note-preview:free` | **active** | 806ms | ctx 512k, tools, reasoning, vision | 2026-11-11 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-11-11 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-11 |
| `cohere/north-mini-code:free` | **active** | 981ms | ctx 256k, tools, reasoning | 2026-11-11 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-11 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-11 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-11 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-11 |

</details>

<details><summary><b>llm7</b> — 2/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-11 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-11-11 |
| `codestral-latest` | **active** | 940ms | — | 2026-11-11 |
| `gemma4:31b` | **dead** | — | — | 2026-11-11 |
| `glm-5.2` | **dead** | — | — | 2026-11-11 |
| `gpt-oss:20b` | **dead** | — | — | 2026-11-11 |
| `minimax-m2.7` | **not-chat** | — | — | 2026-11-11 |
| `minimax-m3` | **dead** | — | — | 2026-11-11 |
| `mistral-Nemo-Instruct-2407` | **active** | 149ms | — | 2026-11-11 |
| `nemotron-3-nano:30b` | **not-chat** | — | — | 2026-11-11 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `stepfun-ai/step-5-preview` (nvidia) — 1,048,576 tokens
2. `mistral-large-4` (mistral) — 1,048,576 tokens
3. `mistral-large-4-0` (mistral) — 1,048,576 tokens
4. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1,024,000 tokens
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262,144 tokens
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
9. `ministral-8b-2512` (mistral) — 262,144 tokens
10. `ministral-8b-latest` (mistral) — 262,144 tokens
11. `recursive/flint-v1.0:free` (openrouter) — 262,144 tokens
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
13. `codestral-2508` (mistral) — 256,000 tokens
14. `codestral-latest` (mistral) — 256,000 tokens
15. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
16. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
17. `glm-4.7-flash` (zai) — 200,000 tokens
18. `openai/gpt-oss-120b` (groq) — 131,072 tokens
19. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
20. `openai/gpt-oss-20b` (groq) — 131,072 tokens
21. `ministral-3b-2512` (mistral) — 131,072 tokens
22. `ministral-3b-latest` (mistral) — 131,072 tokens
23. `glm-4.5-flash` (zai) — 131,072 tokens
24. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
25. `glm-4.6v-flash` (zai) — 128,000 tokens
26. `voxtral-small-2507` (mistral) — 32,768 tokens
27. `voxtral-small-latest` (mistral) — 32,768 tokens
28. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `nvidia/nemotron-parse-2.0` (nvidia) — 132ms probe
2. `mistral-Nemo-Instruct-2407` (llm7) — 149ms probe
3. `openai/gpt-oss-120b` (groq) — 164ms probe
4. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 167ms probe
5. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 172ms probe
6. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 172ms probe
7. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 212ms probe
8. `qwen/qwen3.8-27b` (groq) — 250ms probe
9. `allam-2-7b` (groq) — 253ms probe
10. `openai/gpt-oss-20b` (groq) — 256ms probe
11. `ministral-3b-2512` (mistral) — 266ms probe
12. `recursive/flint-v1.0:free` (openrouter) — 275ms probe
13. `ministral-8b-latest` (mistral) — 315ms probe
14. `codestral-latest` (mistral) — 330ms probe
15. `ministral-3b-latest` (mistral) — 338ms probe
16. `codestral-2508` (mistral) — 343ms probe
17. `stepfun-ai/step-5-preview` (nvidia) — 347ms probe
18. `voxtral-small-2507` (mistral) — 358ms probe
19. `voxtral-small-latest` (mistral) — 407ms probe
20. `ministral-8b-2512` (mistral) — 444ms probe
21. `ministral-14b-latest` (mistral) — 493ms probe
22. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 555ms probe
23. `glm-4.5-flash` (zai) — 636ms probe
24. `dots-studio/dots-3-note-preview:free` (openrouter) — 806ms probe
25. `glm-4.7-flash` (zai) — 884ms probe
26. `codestral-latest` (llm7) — 940ms probe
27. `cohere/north-mini-code:free` (openrouter) — 981ms probe
28. `mistral-large-4-0` (mistral) — 1059ms probe
29. `mistral-large-4` (mistral) — 1081ms probe
30. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1103ms probe
31. `minimaxai/minimax-m3.1-flash` (nvidia) — 1762ms probe
32. `glm-4.6v-flash` (zai) — 2138ms probe
33. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 4524ms probe
34. `nvidia/ising-calibration-1.5-31b` (nvidia) — 5781ms probe
35. `google/diffusiongemma-26b-a4b-it` (nvidia) — 18678ms probe
36. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 19126ms probe

**Tool calling** (ranked):
1. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
2. `mistral-large-4` (mistral) — 1048k ctx
3. `mistral-large-4-0` (mistral) — 1048k ctx
4. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
9. `ministral-8b-2512` (mistral) — 262k ctx
10. `ministral-8b-latest` (mistral) — 262k ctx
11. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
13. `codestral-2508` (mistral) — 256k ctx
14. `codestral-latest` (mistral) — 256k ctx
15. `cohere/north-mini-code:free` (openrouter) — 256k ctx
16. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
17. `glm-4.7-flash` (zai) — 200k ctx
18. `openai/gpt-oss-120b` (groq) — 131k ctx
19. `qwen/qwen3.8-27b` (groq) — 131k ctx
20. `openai/gpt-oss-20b` (groq) — 131k ctx
21. `ministral-3b-2512` (mistral) — 131k ctx
22. `ministral-3b-latest` (mistral) — 131k ctx
23. `glm-4.5-flash` (zai) — 131k ctx
24. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
25. `glm-4.6v-flash` (zai) — 128k ctx
26. `voxtral-small-2507` (mistral) — 32k ctx
27. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
2. `mistral-large-4` (mistral) — 1048k ctx
3. `mistral-large-4-0` (mistral) — 1048k ctx
4. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
9. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
10. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
11. `cohere/north-mini-code:free` (openrouter) — 256k ctx
12. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
13. `glm-4.7-flash` (zai) — 200k ctx
14. `openai/gpt-oss-120b` (groq) — 131k ctx
15. `qwen/qwen3.8-27b` (groq) — 131k ctx
16. `openai/gpt-oss-20b` (groq) — 131k ctx
17. `glm-4.5-flash` (zai) — 131k ctx
18. `glm-4.6v-flash` (zai) — 128k ctx

**Vision (image input)** (ranked):
1. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
2. `mistral-large-4` (mistral) — 1048k ctx
3. `mistral-large-4-0` (mistral) — 1048k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
6. `ministral-8b-2512` (mistral) — 262k ctx
7. `ministral-8b-latest` (mistral) — 262k ctx
8. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
9. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
10. `qwen/qwen3.8-27b` (groq) — 131k ctx
11. `ministral-3b-2512` (mistral) — 131k ctx
12. `ministral-3b-latest` (mistral) — 131k ctx
13. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
14. `glm-4.6v-flash` (zai) — 128k ctx

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
