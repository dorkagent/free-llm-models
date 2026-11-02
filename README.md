# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-02T22:39:28Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-02 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-02 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-02 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-02 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-02 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-02 |
| `allam-2-7b` | **active** | 272ms | ctx 4k | 2026-11-02 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-02 |
| `qwen/qwen3.8-27b` | **active** | 76ms | ctx 131k, tools, reasoning, vision | 2026-11-02 |
| `openai/gpt-oss-120b` | **active** | 247ms | ctx 131k, tools, reasoning | 2026-11-02 |
| `openai/gpt-oss-20b` | **active** | 170ms | ctx 131k, tools, reasoning | 2026-11-02 |

</details>

<details><summary><b>nvidia</b> — 17/85 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-11-02 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-11-02 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-11-02 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-11-02 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-02 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-11-02 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-11-02 |
| `deepseek-ai/deepseek-v4.1-flash` | **active** | 945ms | ctx 1000k, tools, reasoning, vision | 2026-11-02 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-11-02 |
| `google/codegemma-7b` | **dead** | — | — | 2026-11-02 |
| `google/deplot` | **dead** | — | — | 2026-11-02 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 360ms | ctx 250k, tools, reasoning, vision | 2026-11-02 |
| `google/gemma-2b` | **dead** | — | — | 2026-11-02 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-02 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-02 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-02 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-11-02 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-11-02 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-11-02 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-11-02 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-11-02 |
| `meta/codellama-70b` | **dead** | — | — | 2026-11-02 |
| `meta/llama-3.2-11b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-11-02 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 610ms | ctx 128k, tools, vision | 2026-11-02 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 163k, vision | 2026-11-02 |
| `meta/llama2-70b` | **dead** | — | — | 2026-11-02 |
| `meta/muse-glimmer-30b` | **active** | 1681ms | ctx 131k, tools, reasoning, vision | 2026-11-02 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-11-02 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-11-02 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-11-02 |
| `minimaxai/minimax-m3.1-flash` | **active** | 437ms | ctx 262k, tools, reasoning, vision | 2026-11-02 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-11-02 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-11-02 |
| `mistralai/mistral-large` | **dead** | — | — | 2026-11-02 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-11-02 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 718ms | — | 2026-11-02 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-11-02 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-02 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-11-02 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-02 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-02 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-02 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 487ms | — | 2026-11-02 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-11-02 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-02 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-11-02 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-11-02 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-02 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-11-02 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-02 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-02 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 8k, vision | 2026-11-02 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-11-02 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-11-02 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-11-02 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 224ms | ctx 256k, tools, reasoning, vision | 2026-11-02 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-11-02 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 622ms | ctx 1000k, tools, reasoning | 2026-11-02 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 471ms | — | 2026-11-02 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-02 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-02 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-02 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 9550ms | ctx 262k, tools, reasoning | 2026-11-02 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 226ms | ctx 1048k, tools, reasoning, vision | 2026-11-02 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-11-02 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-11-02 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-11-02 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-11-02 |
| `nvidia/nemotron-parse-2.0` | **active** | 229ms | — | 2026-11-02 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-11-02 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-02 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-02 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-11-02 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 280ms | — | 2026-11-02 |
| `nvidia/vila` | **dead** | — | — | 2026-11-02 |
| `openai/gpt-oss-20b` | **dead** | — | ctx 131k, tools, reasoning | 2026-11-02 |
| `poolside/laguna-xs-2.1` | **active** | 206ms | ctx 262k, tools, reasoning | 2026-11-02 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-02 |
| `stepfun-ai/step-5-preview` | **active** | 8444ms | ctx 1048k, tools, reasoning, vision | 2026-11-02 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-11-02 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-11-02 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-11-02 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-11-02 |
| `z-ai/glm-5.3-flash` | **active** | 6618ms | ctx 1000k, tools, reasoning, vision | 2026-11-02 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-11-02 |

</details>

<details><summary><b>mistral</b> — 14/55 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 394ms | ctx 256k, tools | 2026-11-02 |
| `codestral-latest` | **active** | 512ms | ctx 256k, tools | 2026-11-02 |
| `mistral-code-latest` | **active** | 1862ms | — | 2026-11-02 |
| `mistral-code-fim-latest` | **active** | 424ms | — | 2026-11-02 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-02 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-02 |
| `ministral-14b-2512` | **active** | 435ms | ctx 262k, tools, vision | 2026-11-02 |
| `ministral-14b-latest` | **active** | 480ms | — | 2026-11-02 |
| `ministral-3b-2512` | **active** | 368ms | ctx 131k, tools, vision | 2026-11-02 |
| `ministral-3b-latest` | **active** | 383ms | ctx 131k, tools, vision | 2026-11-02 |
| `ministral-8b-2512` | **active** | 515ms | ctx 262k, tools, vision | 2026-11-02 |
| `ministral-8b-latest` | **active** | 758ms | ctx 262k, tools, vision | 2026-11-02 |
| `mistral-large-4` | **active** | 680ms | ctx 1048k, tools, reasoning, vision | 2026-11-02 |
| `mistral-large-4-0` | **active** | 803ms | ctx 1048k, tools, reasoning, vision | 2026-11-02 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-02 |
| `mistral-medium` | **rate-limited** | — | ctx 131k, tools, vision | 2026-11-02 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-02 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-02 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-02 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-02 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-02 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-02 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-02 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-02 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-02 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-02 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-02 |
| `voxtral-small-2507` | **active** | 387ms | ctx 32k, tools | 2026-11-02 |
| `voxtral-small-latest` | **active** | 447ms | ctx 32k, tools | 2026-11-02 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-02 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-02 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-02 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-02 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-02 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-02 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-02 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-02 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-02 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-02 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-02 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-02 |

</details>

<details><summary><b>zai</b> — 3/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 13062ms | ctx 200k, tools, reasoning | 2026-11-02 |
| `glm-4.5-flash` | **active** | 1213ms | ctx 131k, tools, reasoning | 2026-11-02 |
| `glm-4.6v-flash` | **active** | 391ms | ctx 128k, tools, reasoning, vision | 2026-11-02 |

</details>

<details><summary><b>ollama</b> — 7/25 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `nemotron-3-nano:30b` | **active** | 434ms | — | 2026-11-02 |
| `mistral-large-4` | **dead** | — | — | 2026-11-02 |
| `nemotron-3-ultra` | **active** | 847ms | — | 2026-11-02 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-02 |
| `minimax-m2.7` | **dead** | — | — | 2026-11-02 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-02 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-02 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-11-02 |
| `minimax-m3` | **dead** | — | — | 2026-11-02 |
| `nemotron-3-super` | **active** | 395ms | — | 2026-11-02 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-02 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-02 |
| `clef:27b` | **not-chat** | — | — | 2026-11-02 |
| `gpt-oss:120b` | **active** | 418ms | — | 2026-11-02 |
| `beam` | **active** | 533ms | — | 2026-11-02 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-02 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-02 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-02 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-02 |
| `gpt-oss:20b` | **active** | 453ms | — | 2026-11-02 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-02 |
| `gemma4:31b` | **active** | 417ms | — | 2026-11-02 |
| `glm-5.2` | **dead** | — | — | 2026-11-02 |
| `muse-spark-open` | **dead** | — | — | 2026-11-02 |
| `glm-5.3` | **dead** | — | — | 2026-11-02 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 255ms | ctx 128k, tools | 2026-11-02 |

</details>

<details><summary><b>openrouter</b> — 2/14 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `recursive/flint-v1.0:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-02 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **rate-limited** | — | ctx 262k, tools, reasoning | 2026-11-02 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-02 |
| `dots-studio/dots-3-note-preview:free` | **active** | 841ms | ctx 512k, tools, reasoning, vision | 2026-11-02 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-11-02 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-02 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-02 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-02 |
| `cohere/north-mini-code:free` | **active** | 1119ms | ctx 256k, tools, reasoning | 2026-11-02 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-02 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-02 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-02 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-02 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-02 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-02 |
| `GLM-5.3-Flash` | **dead** | — | — | 2026-11-02 |
| `codestral-latest` | **active** | 716ms | — | 2026-11-02 |
| `gemma4:31b` | **dead** | — | — | 2026-11-02 |
| `glm-5.2` | **dead** | — | — | 2026-11-02 |
| `gpt-oss:20b` | **active** | 377ms | — | 2026-11-02 |
| `minimax-m2.7` | **active** | 759ms | — | 2026-11-02 |
| `minimax-m3` | **dead** | — | — | 2026-11-02 |
| `mistral-Nemo-Instruct-2407` | **active** | 706ms | — | 2026-11-02 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-11-02 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `stepfun-ai/step-5-preview` (nvidia) — 1,048,576 tokens
3. `mistral-large-4` (mistral) — 1,048,576 tokens
4. `mistral-large-4-0` (mistral) — 1,048,576 tokens
5. `deepseek-ai/deepseek-v4.1-flash` (nvidia) — 1,000,000 tokens
6. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
7. `z-ai/glm-5.3-flash` (nvidia) — 1,000,000 tokens
8. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
9. `minimaxai/minimax-m3.1-flash` (nvidia) — 262,144 tokens
10. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
11. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
12. `ministral-14b-2512` (mistral) — 262,144 tokens
13. `ministral-8b-2512` (mistral) — 262,144 tokens
14. `ministral-8b-latest` (mistral) — 262,144 tokens
15. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
16. `codestral-2508` (mistral) — 256,000 tokens
17. `codestral-latest` (mistral) — 256,000 tokens
18. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
19. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
20. `glm-4.7-flash` (zai) — 200,000 tokens
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
1. `qwen/qwen3.8-27b` (groq) — 76ms probe
2. `openai/gpt-oss-20b` (groq) — 170ms probe
3. `poolside/laguna-xs-2.1` (nvidia) — 206ms probe
4. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 224ms probe
5. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 226ms probe
6. `nvidia/nemotron-parse-2.0` (nvidia) — 229ms probe
7. `openai/gpt-oss-120b` (groq) — 247ms probe
8. `allam-2-7b` (groq) — 272ms probe
9. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 280ms probe
10. `google/diffusiongemma-26b-a4b-it` (nvidia) — 360ms probe
11. `ministral-3b-2512` (mistral) — 368ms probe
12. `gpt-oss:20b` (llm7) — 377ms probe
13. `ministral-3b-latest` (mistral) — 383ms probe
14. `voxtral-small-2507` (mistral) — 387ms probe
15. `glm-4.6v-flash` (zai) — 391ms probe
16. `codestral-2508` (mistral) — 394ms probe
17. `nemotron-3-super` (ollama) — 395ms probe
18. `gemma4:31b` (ollama) — 417ms probe
19. `gpt-oss:120b` (ollama) — 418ms probe
20. `mistral-code-fim-latest` (mistral) — 424ms probe
21. `nemotron-3-nano:30b` (ollama) — 434ms probe
22. `ministral-14b-2512` (mistral) — 435ms probe
23. `minimaxai/minimax-m3.1-flash` (nvidia) — 437ms probe
24. `voxtral-small-latest` (mistral) — 447ms probe
25. `gpt-oss:20b` (ollama) — 453ms probe
26. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 471ms probe
27. `ministral-14b-latest` (mistral) — 480ms probe
28. `nvidia/ising-calibration-1.5-31b` (nvidia) — 487ms probe
29. `codestral-latest` (mistral) — 512ms probe
30. `ministral-8b-2512` (mistral) — 515ms probe
31. `beam` (ollama) — 533ms probe
32. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 610ms probe
33. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 622ms probe
34. `mistral-large-4` (mistral) — 680ms probe
35. `mistral-Nemo-Instruct-2407` (llm7) — 706ms probe
36. `codestral-latest` (llm7) — 716ms probe
37. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 718ms probe
38. `ministral-8b-latest` (mistral) — 758ms probe
39. `minimax-m2.7` (llm7) — 759ms probe
40. `mistral-large-4-0` (mistral) — 803ms probe
41. `dots-studio/dots-3-note-preview:free` (openrouter) — 841ms probe
42. `nemotron-3-ultra` (ollama) — 847ms probe
43. `deepseek-ai/deepseek-v4.1-flash` (nvidia) — 945ms probe
44. `cohere/north-mini-code:free` (openrouter) — 1119ms probe
45. `glm-4.5-flash` (zai) — 1213ms probe
46. `meta/muse-glimmer-30b` (nvidia) — 1681ms probe
47. `mistral-code-latest` (mistral) — 1862ms probe
48. `z-ai/glm-5.3-flash` (nvidia) — 6618ms probe
49. `stepfun-ai/step-5-preview` (nvidia) — 8444ms probe
50. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 9550ms probe
51. `glm-4.7-flash` (zai) — 13062ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `mistral-large-4` (mistral) — 1048k ctx
4. `mistral-large-4-0` (mistral) — 1048k ctx
5. `deepseek-ai/deepseek-v4.1-flash` (nvidia) — 1000k ctx
6. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
7. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
8. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
9. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
10. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
11. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
12. `ministral-14b-2512` (mistral) — 262k ctx
13. `ministral-8b-2512` (mistral) — 262k ctx
14. `ministral-8b-latest` (mistral) — 262k ctx
15. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
16. `codestral-2508` (mistral) — 256k ctx
17. `codestral-latest` (mistral) — 256k ctx
18. `cohere/north-mini-code:free` (openrouter) — 256k ctx
19. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
20. `glm-4.7-flash` (zai) — 200k ctx
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
5. `deepseek-ai/deepseek-v4.1-flash` (nvidia) — 1000k ctx
6. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
7. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
8. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
9. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
10. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
11. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
13. `cohere/north-mini-code:free` (openrouter) — 256k ctx
14. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
15. `glm-4.7-flash` (zai) — 200k ctx
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
5. `deepseek-ai/deepseek-v4.1-flash` (nvidia) — 1000k ctx
6. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
7. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
8. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
9. `ministral-14b-2512` (mistral) — 262k ctx
10. `ministral-8b-2512` (mistral) — 262k ctx
11. `ministral-8b-latest` (mistral) — 262k ctx
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
13. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
14. `qwen/qwen3.8-27b` (groq) — 131k ctx
15. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
16. `ministral-3b-2512` (mistral) — 131k ctx
17. `ministral-3b-latest` (mistral) — 131k ctx
18. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
19. `glm-4.6v-flash` (zai) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (570ms) | 1 day(s) |


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
