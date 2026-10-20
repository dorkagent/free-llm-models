# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-20T14:29:26Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-20 |
| `allam-2-7b` | **active** | 263ms | ctx 4k | 2026-10-20 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-20 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-20 |
| `openai/gpt-oss-20b` | **active** | 151ms | ctx 131k, tools, reasoning | 2026-10-20 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-20 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-20 |
| `openai/gpt-oss-120b` | **active** | 201ms | ctx 131k, tools, reasoning | 2026-10-20 |
| `qwen/qwen3.8-27b` | **active** | 157ms | ctx 131k, tools, reasoning, vision | 2026-10-20 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-20 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-20 |

</details>

<details><summary><b>nvidia</b> — 12/81 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-20 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-20 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-20 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-20 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-20 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-20 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-20 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-20 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-20 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-20 |
| `google/deplot` | **dead** | — | — | 2026-10-20 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 2408ms | ctx 250k, tools, reasoning, vision | 2026-10-20 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-20 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-20 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-20 |
| `google/gemma-4-31b-it` | **active** | 22281ms | ctx 256k, tools, reasoning, vision | 2026-10-20 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-20 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-20 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-20 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-20 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-20 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-20 |
| `meta/llama-3.2-11b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-20 |
| `meta/llama-3.2-90b-vision-instruct` | **dead** | — | ctx 128k, tools, vision | 2026-10-20 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-20 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-20 |
| `meta/muse-glimmer-30b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-20 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-20 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-20 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-20 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-20 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-20 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-20 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-20 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-20 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-20 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-20 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-20 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-20 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-20 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 1329ms | — | 2026-10-20 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-20 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-20 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-20 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-20 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-20 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-20 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-20 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-20 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-20 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-20 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-20 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-20 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 3025ms | ctx 256k, tools, reasoning, vision | 2026-10-20 |
| `nvidia/nemotron-3-super-120b-a12b` | **dead** | — | — | 2026-10-20 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 10114ms | ctx 1000k, tools, reasoning | 2026-10-20 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-20 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 240ms | ctx 262k, tools, reasoning | 2026-10-20 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-20 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-20 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-20 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-20 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-20 |
| `nvidia/nemotron-parse-2.0` | **active** | 131ms | — | 2026-10-20 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-20 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-20 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-20 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-20 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 9796ms | — | 2026-10-20 |
| `nvidia/vila` | **dead** | — | — | 2026-10-20 |
| `openai/gpt-oss-20b` | **active** | 268ms | ctx 131k, tools, reasoning | 2026-10-20 |
| `poolside/laguna-xs-2.1` | **active** | 638ms | ctx 262k, tools, reasoning | 2026-10-20 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-20 |
| `stepfun-ai/step-5-preview` | **active** | 757ms | ctx 1048k, tools, reasoning, vision | 2026-10-20 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-20 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-20 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-20 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-20 |
| `z-ai/glm-5.3` | **active** | 20614ms | ctx 1000k, tools, reasoning | 2026-10-20 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-20 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-20 |

</details>

<details><summary><b>mistral</b> — 12/45 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 379ms | ctx 256k, tools | 2026-10-20 |
| `codestral-latest` | **active** | 312ms | ctx 256k, tools | 2026-10-20 |
| `mistral-code-latest` | **active** | 738ms | — | 2026-10-20 |
| `mistral-code-fim-latest` | **active** | 339ms | — | 2026-10-20 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-20 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-20 |
| `ministral-14b-2512` | **active** | 415ms | ctx 262k, tools, vision | 2026-10-20 |
| `ministral-14b-latest` | **active** | 382ms | — | 2026-10-20 |
| `ministral-3b-2512` | **active** | 371ms | ctx 131k, tools, vision | 2026-10-20 |
| `ministral-3b-latest` | **active** | 385ms | ctx 131k, tools, vision | 2026-10-20 |
| `ministral-8b-2512` | **active** | 444ms | ctx 262k, tools, vision | 2026-10-20 |
| `ministral-8b-latest` | **active** | 497ms | ctx 262k, tools, vision | 2026-10-20 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-20 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-20 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-20 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-20 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-20 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-20 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-20 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-20 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-20 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-20 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-20 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-20 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-20 |
| `voxtral-small-2507` | **active** | 342ms | ctx 32k, tools | 2026-10-20 |
| `voxtral-small-latest` | **active** | 1582ms | ctx 32k, tools | 2026-10-20 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-20 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-20 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-20 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-20 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-20 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-20 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-20 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-20 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-20 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-20 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-20 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-20 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-20 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-20 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-20 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-20 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-20 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-20 |

</details>

<details><summary><b>zai</b> — 1/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-10-20 |
| `glm-4.5-flash` | **active** | 766ms | ctx 131k, tools, reasoning | 2026-10-20 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-20 |

</details>

<details><summary><b>ollama</b> — 2/23 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `minimax-m2.7` | **dead** | — | — | 2026-10-20 |
| `muse-spark-open` | **dead** | — | — | 2026-10-20 |
| `glm-5.2` | **dead** | — | — | 2026-10-20 |
| `glm-5.3` | **dead** | — | — | 2026-10-20 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-20 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-20 |
| `nemotron-3-nano:30b` | **active** | 313ms | — | 2026-10-20 |
| `minimax-m3.1-flash` | **active** | 1086ms | — | 2026-10-20 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-20 |
| `minimax-m3` | **dead** | — | — | 2026-10-20 |
| `nemotron-3-super` | **dead** | — | — | 2026-10-20 |
| `clef:27b` | **dead** | — | — | 2026-10-20 |
| `beam` | **dead** | — | — | 2026-10-20 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-20 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-20 |
| `deepseek-v4.1-flash:1017` | **rate-limited** | — | — | 2026-10-20 |
| `mistral-large-3:675b` | **rate-limited** | — | — | 2026-10-20 |
| `mistral-large-4` | **rate-limited** | — | — | 2026-10-20 |
| `deepseek-v4-pro:0813` | **rate-limited** | — | ctx 1000k | 2026-10-20 |
| `gpt-oss:120b` | **rate-limited** | — | — | 2026-10-20 |
| `gpt-oss:20b` | **rate-limited** | — | — | 2026-10-20 |
| `gemma4:31b` | **rate-limited** | — | — | 2026-10-20 |
| `nemotron-3-ultra` | **rate-limited** | — | — | 2026-10-20 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 197ms | ctx 128k, tools | 2026-10-20 |

</details>

<details><summary><b>openrouter</b> — 3/17 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `minimax/minimax-m3.1-flash:free` | **active** | 695ms | ctx 1000k, tools, reasoning, vision | 2026-10-20 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **rate-limited** | — | ctx 262k, tools, reasoning | 2026-10-20 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-20 |
| `dots-studio/dots-3-note-preview:free` | **active** | 880ms | ctx 512k, tools, reasoning, vision | 2026-10-20 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-20 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-20 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-20 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-20 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-20 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-20 |
| `cohere/north-mini-code:free` | **active** | 377ms | ctx 256k, tools, reasoning | 2026-10-20 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-20 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-20 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-20 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-20 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-20 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-20 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-20 |
| `GLM-5.3-Flash` | **dead** | — | — | 2026-10-20 |
| `codestral-latest` | **active** | 473ms | — | 2026-10-20 |
| `gemma4:31b` | **dead** | — | — | 2026-10-20 |
| `glm-5.2` | **dead** | — | — | 2026-10-20 |
| `gpt-oss:20b` | **active** | 298ms | — | 2026-10-20 |
| `minimax-m2.7` | **active** | 213ms | — | 2026-10-20 |
| `minimax-m3` | **dead** | — | — | 2026-10-20 |
| `mistral-Nemo-Instruct-2407` | **active** | 274ms | — | 2026-10-20 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-10-20 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `stepfun-ai/step-5-preview` (nvidia) — 1,048,576 tokens
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
3. `z-ai/glm-5.3` (nvidia) — 1,000,000 tokens
4. `minimax/minimax-m3.1-flash:free` (openrouter) — 1,000,000 tokens
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
7. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
8. `ministral-14b-2512` (mistral) — 262,144 tokens
9. `ministral-8b-2512` (mistral) — 262,144 tokens
10. `ministral-8b-latest` (mistral) — 262,144 tokens
11. `google/gemma-4-31b-it` (nvidia) — 256,000 tokens
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
13. `codestral-2508` (mistral) — 256,000 tokens
14. `codestral-latest` (mistral) — 256,000 tokens
15. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
16. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
17. `openai/gpt-oss-20b` (groq) — 131,072 tokens
18. `openai/gpt-oss-120b` (groq) — 131,072 tokens
19. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
20. `ministral-3b-2512` (mistral) — 131,072 tokens
21. `ministral-3b-latest` (mistral) — 131,072 tokens
22. `glm-4.5-flash` (zai) — 131,072 tokens
23. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
24. `voxtral-small-2507` (mistral) — 32,768 tokens
25. `voxtral-small-latest` (mistral) — 32,768 tokens
26. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `nvidia/nemotron-parse-2.0` (nvidia) — 131ms probe
2. `openai/gpt-oss-20b` (groq) — 151ms probe
3. `qwen/qwen3.8-27b` (groq) — 157ms probe
4. `openai/gpt-oss-120b` (groq) — 201ms probe
5. `minimax-m2.7` (llm7) — 213ms probe
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 240ms probe
7. `allam-2-7b` (groq) — 263ms probe
8. `openai/gpt-oss-20b` (nvidia) — 268ms probe
9. `mistral-Nemo-Instruct-2407` (llm7) — 274ms probe
10. `gpt-oss:20b` (llm7) — 298ms probe
11. `codestral-latest` (mistral) — 312ms probe
12. `nemotron-3-nano:30b` (ollama) — 313ms probe
13. `mistral-code-fim-latest` (mistral) — 339ms probe
14. `voxtral-small-2507` (mistral) — 342ms probe
15. `ministral-3b-2512` (mistral) — 371ms probe
16. `cohere/north-mini-code:free` (openrouter) — 377ms probe
17. `codestral-2508` (mistral) — 379ms probe
18. `ministral-14b-latest` (mistral) — 382ms probe
19. `ministral-3b-latest` (mistral) — 385ms probe
20. `ministral-14b-2512` (mistral) — 415ms probe
21. `ministral-8b-2512` (mistral) — 444ms probe
22. `codestral-latest` (llm7) — 473ms probe
23. `ministral-8b-latest` (mistral) — 497ms probe
24. `poolside/laguna-xs-2.1` (nvidia) — 638ms probe
25. `minimax/minimax-m3.1-flash:free` (openrouter) — 695ms probe
26. `mistral-code-latest` (mistral) — 738ms probe
27. `stepfun-ai/step-5-preview` (nvidia) — 757ms probe
28. `glm-4.5-flash` (zai) — 766ms probe
29. `dots-studio/dots-3-note-preview:free` (openrouter) — 880ms probe
30. `minimax-m3.1-flash` (ollama) — 1086ms probe
31. `nvidia/ising-calibration-1.5-31b` (nvidia) — 1329ms probe
32. `voxtral-small-latest` (mistral) — 1582ms probe
33. `google/diffusiongemma-26b-a4b-it` (nvidia) — 2408ms probe
34. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 3025ms probe
35. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 9796ms probe
36. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 10114ms probe
37. `z-ai/glm-5.3` (nvidia) — 20614ms probe
38. `google/gemma-4-31b-it` (nvidia) — 22281ms probe

**Tool calling** (ranked):
1. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3` (nvidia) — 1000k ctx
4. `minimax/minimax-m3.1-flash:free` (openrouter) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
8. `ministral-14b-2512` (mistral) — 262k ctx
9. `ministral-8b-2512` (mistral) — 262k ctx
10. `ministral-8b-latest` (mistral) — 262k ctx
11. `google/gemma-4-31b-it` (nvidia) — 256k ctx
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
13. `codestral-2508` (mistral) — 256k ctx
14. `codestral-latest` (mistral) — 256k ctx
15. `cohere/north-mini-code:free` (openrouter) — 256k ctx
16. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
17. `openai/gpt-oss-20b` (groq) — 131k ctx
18. `openai/gpt-oss-120b` (groq) — 131k ctx
19. `openai/gpt-oss-20b` (nvidia) — 131k ctx
20. `ministral-3b-2512` (mistral) — 131k ctx
21. `ministral-3b-latest` (mistral) — 131k ctx
22. `glm-4.5-flash` (zai) — 131k ctx
23. `qwen/qwen3.8-27b` (groq) — 131k ctx
24. `voxtral-small-2507` (mistral) — 32k ctx
25. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3` (nvidia) — 1000k ctx
4. `minimax/minimax-m3.1-flash:free` (openrouter) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
8. `google/gemma-4-31b-it` (nvidia) — 256k ctx
9. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
10. `cohere/north-mini-code:free` (openrouter) — 256k ctx
11. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
12. `openai/gpt-oss-20b` (groq) — 131k ctx
13. `openai/gpt-oss-120b` (groq) — 131k ctx
14. `openai/gpt-oss-20b` (nvidia) — 131k ctx
15. `glm-4.5-flash` (zai) — 131k ctx
16. `qwen/qwen3.8-27b` (groq) — 131k ctx

**Vision (image input)** (ranked):
1. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
2. `minimax/minimax-m3.1-flash:free` (openrouter) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `ministral-14b-2512` (mistral) — 262k ctx
5. `ministral-8b-2512` (mistral) — 262k ctx
6. `ministral-8b-latest` (mistral) — 262k ctx
7. `google/gemma-4-31b-it` (nvidia) — 256k ctx
8. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
9. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
10. `ministral-3b-2512` (mistral) — 131k ctx
11. `ministral-3b-latest` (mistral) — 131k ctx
12. `qwen/qwen3.8-27b` (groq) — 131k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (249ms) | 1 day(s) |


## Lane quotas (daily snapshot)

Where each lane stands on its free allowance. Quota comes from rate-limit headers captured off the probe responses (zero extra requests), except OpenRouter which needs one daily call to its key endpoint. Keys never leave the private verifier repo; only aggregate remaining counts are published here.

| Lane | Source | Requests remaining | Request limit | Reset / note |
|---|---|---|---|---|
| groq | response-headers | 999 | 1000 | resets in 1m26.4s |
| nvidia | none | — | — | no quota API; dashboard only |
| mistral | response-headers | 58 | 60 |  |
| zai | none | — | — | no quota API; console only |
| ollama | response-headers | — | — |  |
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
