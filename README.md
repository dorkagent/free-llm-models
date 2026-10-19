# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-19T14:34:13Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `allam-2-7b` | **active** | 312ms | ctx 4k | 2026-10-19 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-19 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-19 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-19 |
| `openai/gpt-oss-120b` | **active** | 223ms | ctx 131k, tools, reasoning | 2026-10-19 |
| `qwen/qwen3.8-27b` | **active** | 116ms | ctx 131k, tools, reasoning, vision | 2026-10-19 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-19 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-19 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-19 |
| `openai/gpt-oss-20b` | **active** | 283ms | ctx 131k, tools, reasoning | 2026-10-19 |
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-19 |

</details>

<details><summary><b>nvidia</b> — 13/81 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-19 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-19 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-19 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-19 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-19 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-19 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-19 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-19 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-19 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-19 |
| `google/deplot` | **dead** | — | — | 2026-10-19 |
| `google/diffusiongemma-26b-a4b-it` | **dead** | — | ctx 250k, tools, reasoning, vision | 2026-10-19 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-19 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-19 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-19 |
| `google/gemma-4-31b-it` | **active** | 4537ms | ctx 256k, tools, reasoning, vision | 2026-10-19 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-19 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-19 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-19 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-19 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-19 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-19 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 474ms | ctx 128k, tools, vision | 2026-10-19 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 4703ms | ctx 128k, tools, vision | 2026-10-19 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-19 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-19 |
| `meta/muse-glimmer-30b` | **active** | 9795ms | ctx 131k, tools, reasoning, vision | 2026-10-19 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-19 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-19 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-19 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-19 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-19 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-19 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-19 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-19 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-19 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-19 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-19 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-19 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-19 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 430ms | — | 2026-10-19 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-19 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-19 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-19 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-19 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-19 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-19 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-19 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-19 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-19 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-19 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-19 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-19 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 811ms | ctx 256k, tools, reasoning, vision | 2026-10-19 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 1011ms | — | 2026-10-19 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 719ms | ctx 1000k, tools, reasoning | 2026-10-19 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-19 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 294ms | ctx 262k, tools, reasoning | 2026-10-19 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 4426ms | ctx 1048k, tools, reasoning, vision | 2026-10-19 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-19 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-19 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-19 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-19 |
| `nvidia/nemotron-parse-2.0` | **active** | 311ms | — | 2026-10-19 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-19 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-19 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-19 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-19 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 513ms | — | 2026-10-19 |
| `nvidia/vila` | **dead** | — | — | 2026-10-19 |
| `openai/gpt-oss-20b` | **active** | 342ms | ctx 131k, tools, reasoning | 2026-10-19 |
| `poolside/laguna-xs-2.1` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-19 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-19 |
| `stepfun-ai/step-5-preview` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-19 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-19 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-19 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-19 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-19 |
| `z-ai/glm-5.3` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-19 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-19 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-19 |

</details>

<details><summary><b>mistral</b> — 12/45 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 447ms | ctx 256k, tools | 2026-10-19 |
| `codestral-latest` | **active** | 438ms | ctx 256k, tools | 2026-10-19 |
| `mistral-code-latest` | **active** | 500ms | — | 2026-10-19 |
| `mistral-code-fim-latest` | **active** | 977ms | — | 2026-10-19 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-19 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-19 |
| `ministral-14b-2512` | **active** | 654ms | ctx 262k, tools, vision | 2026-10-19 |
| `ministral-14b-latest` | **active** | 518ms | — | 2026-10-19 |
| `ministral-3b-2512` | **active** | 385ms | ctx 131k, tools, vision | 2026-10-19 |
| `ministral-3b-latest` | **active** | 406ms | ctx 131k, tools, vision | 2026-10-19 |
| `ministral-8b-2512` | **active** | 518ms | ctx 262k, tools, vision | 2026-10-19 |
| `ministral-8b-latest` | **active** | 454ms | ctx 262k, tools, vision | 2026-10-19 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-19 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-19 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-19 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-19 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-19 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-19 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-19 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-19 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-19 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-19 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-19 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-19 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-19 |
| `voxtral-small-2507` | **active** | 426ms | ctx 32k, tools | 2026-10-19 |
| `voxtral-small-latest` | **active** | 378ms | ctx 32k, tools | 2026-10-19 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-19 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-19 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-19 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-19 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-19 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-19 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-19 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-19 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-19 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-19 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-19 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-19 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-19 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-19 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-19 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-19 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-19 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-19 |

</details>

<details><summary><b>zai</b> — 1/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-10-19 |
| `glm-4.5-flash` | **active** | 2629ms | ctx 131k, tools, reasoning | 2026-10-19 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-19 |

</details>

<details><summary><b>ollama</b> — 7/23 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-19 |
| `gpt-oss:20b` | **active** | 444ms | — | 2026-10-19 |
| `gemma4:31b` | **active** | 385ms | — | 2026-10-19 |
| `clef:27b` | **not-chat** | — | — | 2026-10-19 |
| `glm-5.2` | **dead** | — | — | 2026-10-19 |
| `nemotron-3-nano:30b` | **active** | 752ms | — | 2026-10-19 |
| `nemotron-3-super` | **active** | 755ms | — | 2026-10-19 |
| `nemotron-3-ultra` | **active** | 913ms | — | 2026-10-19 |
| `muse-spark-open` | **dead** | — | — | 2026-10-19 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-19 |
| `gpt-oss:120b` | **active** | 444ms | — | 2026-10-19 |
| `glm-5.3` | **dead** | — | — | 2026-10-19 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-19 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-19 |
| `mistral-large-4` | **dead** | — | — | 2026-10-19 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-19 |
| `minimax-m3` | **dead** | — | — | 2026-10-19 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-10-19 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-19 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-10-19 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-19 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-19 |
| `beam` | **active** | 431ms | — | 2026-10-19 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 205ms | ctx 128k, tools | 2026-10-19 |

</details>

<details><summary><b>openrouter</b> — 4/17 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `minimax/minimax-m3.1-flash:free` | **active** | 807ms | ctx 1000k, tools, reasoning, vision | 2026-10-19 |
| `xingchen-agi/xing4.0-29b-a4b:free` | **active** | 559ms | ctx 262k, tools, reasoning | 2026-10-19 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-19 |
| `dots-studio/dots-3-note-preview:free` | **active** | 642ms | ctx 512k, tools, reasoning, vision | 2026-10-19 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-19 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-19 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-19 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-19 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-19 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-19 |
| `cohere/north-mini-code:free` | **active** | 233ms | ctx 256k, tools, reasoning | 2026-10-19 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-19 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-19 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-19 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-19 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-19 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-19 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-19 |
| `GLM-5.3-Flash` | **active** | 882ms | — | 2026-10-19 |
| `codestral-latest` | **active** | 300ms | — | 2026-10-19 |
| `gemma4:31b` | **dead** | — | — | 2026-10-19 |
| `glm-5.2` | **dead** | — | — | 2026-10-19 |
| `gpt-oss:20b` | **active** | 807ms | — | 2026-10-19 |
| `minimax-m2.7` | **active** | 451ms | — | 2026-10-19 |
| `minimax-m3` | **dead** | — | — | 2026-10-19 |
| `mistral-Nemo-Instruct-2407` | **rate-limited** | — | — | 2026-10-19 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-10-19 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
3. `minimax/minimax-m3.1-flash:free` (openrouter) — 1,000,000 tokens
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
6. `ministral-14b-2512` (mistral) — 262,144 tokens
7. `ministral-8b-2512` (mistral) — 262,144 tokens
8. `ministral-8b-latest` (mistral) — 262,144 tokens
9. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262,144 tokens
10. `google/gemma-4-31b-it` (nvidia) — 256,000 tokens
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
12. `codestral-2508` (mistral) — 256,000 tokens
13. `codestral-latest` (mistral) — 256,000 tokens
14. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
15. `openai/gpt-oss-120b` (groq) — 131,072 tokens
16. `openai/gpt-oss-20b` (groq) — 131,072 tokens
17. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
18. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
19. `ministral-3b-2512` (mistral) — 131,072 tokens
20. `ministral-3b-latest` (mistral) — 131,072 tokens
21. `glm-4.5-flash` (zai) — 131,072 tokens
22. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
23. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
24. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
25. `voxtral-small-2507` (mistral) — 32,768 tokens
26. `voxtral-small-latest` (mistral) — 32,768 tokens
27. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 116ms probe
2. `openai/gpt-oss-120b` (groq) — 223ms probe
3. `cohere/north-mini-code:free` (openrouter) — 233ms probe
4. `openai/gpt-oss-20b` (groq) — 283ms probe
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 294ms probe
6. `codestral-latest` (llm7) — 300ms probe
7. `nvidia/nemotron-parse-2.0` (nvidia) — 311ms probe
8. `allam-2-7b` (groq) — 312ms probe
9. `openai/gpt-oss-20b` (nvidia) — 342ms probe
10. `voxtral-small-latest` (mistral) — 378ms probe
11. `ministral-3b-2512` (mistral) — 385ms probe
12. `gemma4:31b` (ollama) — 385ms probe
13. `ministral-3b-latest` (mistral) — 406ms probe
14. `voxtral-small-2507` (mistral) — 426ms probe
15. `nvidia/ising-calibration-1.5-31b` (nvidia) — 430ms probe
16. `beam` (ollama) — 431ms probe
17. `codestral-latest` (mistral) — 438ms probe
18. `gpt-oss:20b` (ollama) — 444ms probe
19. `gpt-oss:120b` (ollama) — 444ms probe
20. `codestral-2508` (mistral) — 447ms probe
21. `minimax-m2.7` (llm7) — 451ms probe
22. `ministral-8b-latest` (mistral) — 454ms probe
23. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 474ms probe
24. `mistral-code-latest` (mistral) — 500ms probe
25. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 513ms probe
26. `ministral-14b-latest` (mistral) — 518ms probe
27. `ministral-8b-2512` (mistral) — 518ms probe
28. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 559ms probe
29. `dots-studio/dots-3-note-preview:free` (openrouter) — 642ms probe
30. `ministral-14b-2512` (mistral) — 654ms probe
31. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 719ms probe
32. `nemotron-3-nano:30b` (ollama) — 752ms probe
33. `nemotron-3-super` (ollama) — 755ms probe
34. `minimax/minimax-m3.1-flash:free` (openrouter) — 807ms probe
35. `gpt-oss:20b` (llm7) — 807ms probe
36. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 811ms probe
37. `GLM-5.3-Flash` (llm7) — 882ms probe
38. `nemotron-3-ultra` (ollama) — 913ms probe
39. `mistral-code-fim-latest` (mistral) — 977ms probe
40. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 1011ms probe
41. `glm-4.5-flash` (zai) — 2629ms probe
42. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 4426ms probe
43. `google/gemma-4-31b-it` (nvidia) — 4537ms probe
44. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 4703ms probe
45. `meta/muse-glimmer-30b` (nvidia) — 9795ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `minimax/minimax-m3.1-flash:free` (openrouter) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
6. `ministral-14b-2512` (mistral) — 262k ctx
7. `ministral-8b-2512` (mistral) — 262k ctx
8. `ministral-8b-latest` (mistral) — 262k ctx
9. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
10. `google/gemma-4-31b-it` (nvidia) — 256k ctx
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
12. `codestral-2508` (mistral) — 256k ctx
13. `codestral-latest` (mistral) — 256k ctx
14. `cohere/north-mini-code:free` (openrouter) — 256k ctx
15. `openai/gpt-oss-120b` (groq) — 131k ctx
16. `openai/gpt-oss-20b` (groq) — 131k ctx
17. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
18. `openai/gpt-oss-20b` (nvidia) — 131k ctx
19. `ministral-3b-2512` (mistral) — 131k ctx
20. `ministral-3b-latest` (mistral) — 131k ctx
21. `glm-4.5-flash` (zai) — 131k ctx
22. `qwen/qwen3.8-27b` (groq) — 131k ctx
23. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
24. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
25. `voxtral-small-2507` (mistral) — 32k ctx
26. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `minimax/minimax-m3.1-flash:free` (openrouter) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
6. `xingchen-agi/xing4.0-29b-a4b:free` (openrouter) — 262k ctx
7. `google/gemma-4-31b-it` (nvidia) — 256k ctx
8. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
9. `cohere/north-mini-code:free` (openrouter) — 256k ctx
10. `openai/gpt-oss-120b` (groq) — 131k ctx
11. `openai/gpt-oss-20b` (groq) — 131k ctx
12. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
13. `openai/gpt-oss-20b` (nvidia) — 131k ctx
14. `glm-4.5-flash` (zai) — 131k ctx
15. `qwen/qwen3.8-27b` (groq) — 131k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `minimax/minimax-m3.1-flash:free` (openrouter) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `ministral-14b-2512` (mistral) — 262k ctx
5. `ministral-8b-2512` (mistral) — 262k ctx
6. `ministral-8b-latest` (mistral) — 262k ctx
7. `google/gemma-4-31b-it` (nvidia) — 256k ctx
8. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
9. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
10. `ministral-3b-2512` (mistral) — 131k ctx
11. `ministral-3b-latest` (mistral) — 131k ctx
12. `qwen/qwen3.8-27b` (groq) — 131k ctx
13. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
14. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (558ms) | 1 day(s) |


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
