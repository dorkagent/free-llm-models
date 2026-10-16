# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-16T14:30:07Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `allam-2-7b` | **active** | 323ms | ctx 4k | 2026-10-16 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-16 |
| `qwen/qwen3.8-27b` | **active** | 145ms | ctx 131k, tools, reasoning, vision | 2026-10-16 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-16 |
| `openai/gpt-oss-120b` | **active** | 1066ms | ctx 131k, tools, reasoning | 2026-10-16 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-16 |
| `openai/gpt-oss-20b` | **active** | 686ms | ctx 131k, tools, reasoning | 2026-10-16 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-16 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-16 |
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-16 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-16 |

</details>

<details><summary><b>nvidia</b> — 11/81 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-16 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-16 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-16 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-16 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-16 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-16 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-16 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-16 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-16 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-16 |
| `google/deplot` | **dead** | — | — | 2026-10-16 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 1214ms | ctx 250k, tools, reasoning, vision | 2026-10-16 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-16 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-16 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-16 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-16 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-16 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-16 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-16 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-16 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-16 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-16 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 240ms | ctx 128k, tools, vision | 2026-10-16 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-16 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-16 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-16 |
| `meta/muse-glimmer-30b` | **active** | 904ms | ctx 131k, tools, reasoning, vision | 2026-10-16 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-16 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-16 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-16 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-16 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-16 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-16 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-16 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-16 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-16 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-16 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-16 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-16 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-16 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 534ms | — | 2026-10-16 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-16 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-16 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-16 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-16 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-16 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-16 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-16 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-16 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-16 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-16 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-16 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-16 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-16 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 687ms | — | 2026-10-16 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-16 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-16 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-16 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 287ms | ctx 1048k, tools, reasoning, vision | 2026-10-16 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-16 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-16 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-16 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-16 |
| `nvidia/nemotron-parse-2.0` | **active** | 131ms | — | 2026-10-16 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-16 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-16 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-16 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-16 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 11105ms | — | 2026-10-16 |
| `nvidia/vila` | **dead** | — | — | 2026-10-16 |
| `openai/gpt-oss-20b` | **active** | 145ms | ctx 131k, tools, reasoning | 2026-10-16 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-16 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-16 |
| `stepfun-ai/step-5-preview` | **active** | 304ms | — | 2026-10-16 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-16 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-16 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-16 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-16 |
| `z-ai/glm-5.3` | **active** | 22767ms | ctx 1000k, tools, reasoning | 2026-10-16 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-16 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-16 |

</details>

<details><summary><b>mistral</b> — 12/45 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 345ms | ctx 256k, tools | 2026-10-16 |
| `codestral-latest` | **active** | 355ms | ctx 256k, tools | 2026-10-16 |
| `mistral-code-latest` | **active** | 415ms | — | 2026-10-16 |
| `mistral-code-fim-latest` | **active** | 373ms | — | 2026-10-16 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-16 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-16 |
| `ministral-14b-2512` | **active** | 653ms | ctx 262k, tools, vision | 2026-10-16 |
| `ministral-14b-latest` | **active** | 406ms | — | 2026-10-16 |
| `ministral-3b-2512` | **active** | 287ms | ctx 131k, tools, vision | 2026-10-16 |
| `ministral-3b-latest` | **active** | 341ms | ctx 131k, tools, vision | 2026-10-16 |
| `ministral-8b-2512` | **active** | 365ms | ctx 262k, tools, vision | 2026-10-16 |
| `ministral-8b-latest` | **active** | 541ms | ctx 262k, tools, vision | 2026-10-16 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-16 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-16 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-16 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-16 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-16 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-16 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-16 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-16 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-16 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-16 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-16 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-16 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-16 |
| `voxtral-small-2507` | **active** | 436ms | ctx 32k, tools | 2026-10-16 |
| `voxtral-small-latest` | **active** | 307ms | ctx 32k, tools | 2026-10-16 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-16 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-16 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-16 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-16 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-16 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-16 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-16 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-16 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-16 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-16 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-16 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-16 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-16 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-16 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-16 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-16 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-16 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-16 |

</details>

<details><summary><b>zai</b> — 1/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-10-16 |
| `glm-4.5-flash` | **active** | 830ms | ctx 131k, tools, reasoning | 2026-10-16 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-16 |

</details>

<details><summary><b>ollama</b> — 7/21 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-16 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-16 |
| `gpt-oss:20b` | **active** | 451ms | — | 2026-10-16 |
| `beam` | **active** | 1257ms | — | 2026-10-16 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-16 |
| `muse-spark-open` | **dead** | — | — | 2026-10-16 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-16 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-16 |
| `gpt-oss:120b` | **active** | 335ms | — | 2026-10-16 |
| `nemotron-3-nano:30b` | **active** | 311ms | — | 2026-10-16 |
| `minimax-m3` | **dead** | — | — | 2026-10-16 |
| `nemotron-3-super` | **active** | 661ms | — | 2026-10-16 |
| `gemma4:31b` | **active** | 367ms | — | 2026-10-16 |
| `nemotron-3-ultra` | **active** | 1074ms | — | 2026-10-16 |
| `glm-5.3` | **dead** | — | — | 2026-10-16 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-16 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-16 |
| `glm-5.2` | **dead** | — | — | 2026-10-16 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-16 |
| `mistral-large-4` | **dead** | — | — | 2026-10-16 |
| `clef:27b` | **not-chat** | — | — | 2026-10-16 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 220ms | ctx 128k, tools | 2026-10-16 |

</details>

<details><summary><b>openrouter</b> — 2/15 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-16 |
| `dots-studio/dots-3-note-preview:free` | **active** | 10249ms | ctx 512k, tools, reasoning, vision | 2026-10-16 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-16 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-16 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-16 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-16 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-16 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-16 |
| `cohere/north-mini-code:free` | **active** | 316ms | ctx 256k, tools, reasoning | 2026-10-16 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-16 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-16 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-16 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-16 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-16 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-16 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-16 |
| `GLM-5.3-Flash` | **active** | 496ms | — | 2026-10-16 |
| `codestral-latest` | **active** | 273ms | — | 2026-10-16 |
| `gemma4:31b` | **dead** | — | — | 2026-10-16 |
| `glm-5.2` | **dead** | — | — | 2026-10-16 |
| `gpt-oss:20b` | **active** | 902ms | — | 2026-10-16 |
| `minimax-m2.7` | **active** | 295ms | — | 2026-10-16 |
| `minimax-m3` | **dead** | — | — | 2026-10-16 |
| `mistral-Nemo-Instruct-2407` | **rate-limited** | — | — | 2026-10-16 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-10-16 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `z-ai/glm-5.3` (nvidia) — 1,000,000 tokens
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
4. `ministral-14b-2512` (mistral) — 262,144 tokens
5. `ministral-8b-2512` (mistral) — 262,144 tokens
6. `ministral-8b-latest` (mistral) — 262,144 tokens
7. `codestral-2508` (mistral) — 256,000 tokens
8. `codestral-latest` (mistral) — 256,000 tokens
9. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
10. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
11. `openai/gpt-oss-120b` (groq) — 131,072 tokens
12. `openai/gpt-oss-20b` (groq) — 131,072 tokens
13. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
14. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
15. `ministral-3b-2512` (mistral) — 131,072 tokens
16. `ministral-3b-latest` (mistral) — 131,072 tokens
17. `glm-4.5-flash` (zai) — 131,072 tokens
18. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
19. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
20. `voxtral-small-2507` (mistral) — 32,768 tokens
21. `voxtral-small-latest` (mistral) — 32,768 tokens
22. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `nvidia/nemotron-parse-2.0` (nvidia) — 131ms probe
2. `qwen/qwen3.8-27b` (groq) — 145ms probe
3. `openai/gpt-oss-20b` (nvidia) — 145ms probe
4. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 240ms probe
5. `codestral-latest` (llm7) — 273ms probe
6. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 287ms probe
7. `ministral-3b-2512` (mistral) — 287ms probe
8. `minimax-m2.7` (llm7) — 295ms probe
9. `stepfun-ai/step-5-preview` (nvidia) — 304ms probe
10. `voxtral-small-latest` (mistral) — 307ms probe
11. `nemotron-3-nano:30b` (ollama) — 311ms probe
12. `cohere/north-mini-code:free` (openrouter) — 316ms probe
13. `allam-2-7b` (groq) — 323ms probe
14. `gpt-oss:120b` (ollama) — 335ms probe
15. `ministral-3b-latest` (mistral) — 341ms probe
16. `codestral-2508` (mistral) — 345ms probe
17. `codestral-latest` (mistral) — 355ms probe
18. `ministral-8b-2512` (mistral) — 365ms probe
19. `gemma4:31b` (ollama) — 367ms probe
20. `mistral-code-fim-latest` (mistral) — 373ms probe
21. `ministral-14b-latest` (mistral) — 406ms probe
22. `mistral-code-latest` (mistral) — 415ms probe
23. `voxtral-small-2507` (mistral) — 436ms probe
24. `gpt-oss:20b` (ollama) — 451ms probe
25. `GLM-5.3-Flash` (llm7) — 496ms probe
26. `nvidia/ising-calibration-1.5-31b` (nvidia) — 534ms probe
27. `ministral-8b-latest` (mistral) — 541ms probe
28. `ministral-14b-2512` (mistral) — 653ms probe
29. `nemotron-3-super` (ollama) — 661ms probe
30. `openai/gpt-oss-20b` (groq) — 686ms probe
31. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 687ms probe
32. `glm-4.5-flash` (zai) — 830ms probe
33. `gpt-oss:20b` (llm7) — 902ms probe
34. `meta/muse-glimmer-30b` (nvidia) — 904ms probe
35. `openai/gpt-oss-120b` (groq) — 1066ms probe
36. `nemotron-3-ultra` (ollama) — 1074ms probe
37. `google/diffusiongemma-26b-a4b-it` (nvidia) — 1214ms probe
38. `beam` (ollama) — 1257ms probe
39. `dots-studio/dots-3-note-preview:free` (openrouter) — 10249ms probe
40. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 11105ms probe
41. `z-ai/glm-5.3` (nvidia) — 22767ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `z-ai/glm-5.3` (nvidia) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `ministral-14b-2512` (mistral) — 262k ctx
5. `ministral-8b-2512` (mistral) — 262k ctx
6. `ministral-8b-latest` (mistral) — 262k ctx
7. `codestral-2508` (mistral) — 256k ctx
8. `codestral-latest` (mistral) — 256k ctx
9. `cohere/north-mini-code:free` (openrouter) — 256k ctx
10. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
11. `openai/gpt-oss-120b` (groq) — 131k ctx
12. `openai/gpt-oss-20b` (groq) — 131k ctx
13. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
14. `openai/gpt-oss-20b` (nvidia) — 131k ctx
15. `ministral-3b-2512` (mistral) — 131k ctx
16. `ministral-3b-latest` (mistral) — 131k ctx
17. `glm-4.5-flash` (zai) — 131k ctx
18. `qwen/qwen3.8-27b` (groq) — 131k ctx
19. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
20. `voxtral-small-2507` (mistral) — 32k ctx
21. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `z-ai/glm-5.3` (nvidia) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `cohere/north-mini-code:free` (openrouter) — 256k ctx
5. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
6. `openai/gpt-oss-120b` (groq) — 131k ctx
7. `openai/gpt-oss-20b` (groq) — 131k ctx
8. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
9. `openai/gpt-oss-20b` (nvidia) — 131k ctx
10. `glm-4.5-flash` (zai) — 131k ctx
11. `qwen/qwen3.8-27b` (groq) — 131k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
3. `ministral-14b-2512` (mistral) — 262k ctx
4. `ministral-8b-2512` (mistral) — 262k ctx
5. `ministral-8b-latest` (mistral) — 262k ctx
6. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
7. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
8. `ministral-3b-2512` (mistral) — 131k ctx
9. `ministral-3b-latest` (mistral) — 131k ctx
10. `qwen/qwen3.8-27b` (groq) — 131k ctx
11. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (412ms) | 1 day(s) |


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
