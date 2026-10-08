# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-08T22:13:43Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `openai/gpt-oss-120b` | **active** | 246ms | ctx 131k, tools, reasoning | 2026-10-08 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-08 |
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-08 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-08 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-08 |
| `openai/gpt-oss-20b` | **active** | 82ms | ctx 131k, tools, reasoning | 2026-10-08 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-08 |
| `allam-2-7b` | **active** | 272ms | ctx 4k | 2026-10-08 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-08 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-08 |
| `qwen/qwen3.8-27b` | **active** | 101ms | ctx 131k, tools, reasoning, vision | 2026-10-08 |

</details>

<details><summary><b>nvidia</b> — 15/80 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-08 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-08 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-08 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-08 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-08 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-08 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-08 |
| `deepseek-ai/deepseek-v4.1-flash` | **active** | 884ms | ctx 1000k, tools, reasoning, vision | 2026-10-08 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-08 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-08 |
| `google/deplot` | **dead** | — | — | 2026-10-08 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 274ms | ctx 250k, tools, reasoning, vision | 2026-10-08 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-08 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-08 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-08 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-08 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-08 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-08 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-08 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-08 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-08 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-08 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 1407ms | ctx 128k, tools, vision | 2026-10-08 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 866ms | ctx 128k, tools, vision | 2026-10-08 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-08 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-08 |
| `meta/muse-glimmer-30b` | **active** | 1368ms | ctx 131k, tools, reasoning, vision | 2026-10-08 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-08 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-08 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-08 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-08 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-08 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-08 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-08 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-08 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-08 |
| `moonshotai/kimi-k3` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-08 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-08 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-08 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-08 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-08 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 12046ms | — | 2026-10-08 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-08 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-08 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-08 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-08 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-08 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-08 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-08 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-08 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-08 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-08 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-08 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-08 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 420ms | ctx 256k, tools, reasoning, vision | 2026-10-08 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 258ms | ctx 262k, tools, reasoning | 2026-10-08 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 831ms | ctx 1000k, tools, reasoning | 2026-10-08 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-08 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 276ms | ctx 262k, tools, reasoning | 2026-10-08 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-08 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-08 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-08 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-08 |
| `nvidia/nemotron-parse-2.0` | **active** | 251ms | — | 2026-10-08 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-08 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-08 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-08 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-08 |
| `nvidia/riva-translate-4b-instruct-v2` | **dead** | — | — | 2026-10-08 |
| `nvidia/vila` | **dead** | — | — | 2026-10-08 |
| `openai/gpt-oss-20b` | **active** | 254ms | ctx 131k, tools, reasoning | 2026-10-08 |
| `poolside/laguna-xs-2.1` | **active** | 278ms | ctx 262k, tools, reasoning | 2026-10-08 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-08 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-08 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-08 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-08 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-08 |
| `z-ai/glm-5.3` | **active** | 536ms | ctx 1000k, tools, reasoning | 2026-10-08 |
| `z-ai/glm-5.3-flash` | **active** | 9530ms | ctx 1000k, tools, reasoning, vision | 2026-10-08 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-08 |

</details>

<details><summary><b>mistral</b> — 12/46 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 351ms | ctx 256k, tools | 2026-10-08 |
| `codestral-latest` | **active** | 325ms | ctx 256k, tools | 2026-10-08 |
| `mistral-code-latest` | **active** | 388ms | — | 2026-10-08 |
| `mistral-code-fim-latest` | **active** | 393ms | — | 2026-10-08 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-08 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-08 |
| `ministral-14b-2512` | **active** | 821ms | ctx 262k, tools, vision | 2026-10-08 |
| `ministral-14b-latest` | **active** | 727ms | — | 2026-10-08 |
| `ministral-3b-2512` | **active** | 402ms | ctx 131k, tools, vision | 2026-10-08 |
| `ministral-3b-latest` | **active** | 394ms | ctx 131k, tools, vision | 2026-10-08 |
| `ministral-8b-2512` | **active** | 365ms | ctx 262k, tools, vision | 2026-10-08 |
| `ministral-8b-latest` | **active** | 368ms | ctx 262k, tools, vision | 2026-10-08 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-08 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-08 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-08 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-08 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-08 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-08 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-08 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-08 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-08 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-08 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-08 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-08 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-08 |
| `voxtral-small-2507` | **active** | 339ms | ctx 32k, tools | 2026-10-08 |
| `voxtral-small-latest` | **active** | 302ms | ctx 32k, tools | 2026-10-08 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-08 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-08 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-08 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-08 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-08 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-08 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-08 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-08 |
| `mistral-ocr-4-0` | **not-chat** | — | — | 2026-10-08 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-08 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-08 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-08 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-08 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-08 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-08 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-08 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-08 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-08 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-08 |

</details>

<details><summary><b>zai</b> — 1/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **dead** | — | ctx 200k, tools, reasoning | 2026-10-08 |
| `glm-4.5-flash` | **active** | 878ms | ctx 131k, tools, reasoning | 2026-10-08 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-08 |

</details>

<details><summary><b>ollama</b> — 6/18 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-08 |
| `gpt-oss:120b` | **active** | 422ms | — | 2026-10-08 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-08 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-08 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-08 |
| `nemotron-3-nano:30b` | **active** | 599ms | — | 2026-10-08 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-08 |
| `mistral-large-4` | **dead** | — | — | 2026-10-08 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-08 |
| `gpt-oss:20b` | **active** | 625ms | — | 2026-10-08 |
| `minimax-m3` | **dead** | — | — | 2026-10-08 |
| `glm-5.2` | **dead** | — | — | 2026-10-08 |
| `gemma4:31b` | **active** | 513ms | — | 2026-10-08 |
| `glm-5.3` | **dead** | — | — | 2026-10-08 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-08 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-08 |
| `nemotron-3-super` | **active** | 594ms | — | 2026-10-08 |
| `nemotron-3-ultra` | **active** | 750ms | — | 2026-10-08 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 229ms | ctx 128k, tools | 2026-10-08 |

</details>

<details><summary><b>openrouter</b> — 3/15 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `apodex/apodex-1.1-mini:free` | **active** | 663ms | ctx 262k, tools, reasoning | 2026-10-08 |
| `dots-studio/dots-3-note-preview:free` | **active** | 1061ms | ctx 512k, tools, reasoning, vision | 2026-10-08 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-08 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-08 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-08 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-08 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-08 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-08 |
| `cohere/north-mini-code:free` | **active** | 216ms | ctx 256k, tools, reasoning | 2026-10-08 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-08 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-08 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-08 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-08 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-08 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-08 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `deepseek-ai/deepseek-v4.1-flash` (nvidia) — 1,000,000 tokens
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
3. `z-ai/glm-5.3` (nvidia) — 1,000,000 tokens
4. `z-ai/glm-5.3-flash` (nvidia) — 1,000,000 tokens
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
6. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262,144 tokens
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
8. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
9. `ministral-14b-2512` (mistral) — 262,144 tokens
10. `ministral-8b-2512` (mistral) — 262,144 tokens
11. `ministral-8b-latest` (mistral) — 262,144 tokens
12. `apodex/apodex-1.1-mini:free` (openrouter) — 262,144 tokens
13. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
14. `codestral-2508` (mistral) — 256,000 tokens
15. `codestral-latest` (mistral) — 256,000 tokens
16. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
17. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
18. `openai/gpt-oss-120b` (groq) — 131,072 tokens
19. `openai/gpt-oss-20b` (groq) — 131,072 tokens
20. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
21. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
22. `ministral-3b-2512` (mistral) — 131,072 tokens
23. `ministral-3b-latest` (mistral) — 131,072 tokens
24. `glm-4.5-flash` (zai) — 131,072 tokens
25. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
26. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
27. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
28. `voxtral-small-2507` (mistral) — 32,768 tokens
29. `voxtral-small-latest` (mistral) — 32,768 tokens
30. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `openai/gpt-oss-20b` (groq) — 82ms probe
2. `qwen/qwen3.8-27b` (groq) — 101ms probe
3. `cohere/north-mini-code:free` (openrouter) — 216ms probe
4. `openai/gpt-oss-120b` (groq) — 246ms probe
5. `nvidia/nemotron-parse-2.0` (nvidia) — 251ms probe
6. `openai/gpt-oss-20b` (nvidia) — 254ms probe
7. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 258ms probe
8. `allam-2-7b` (groq) — 272ms probe
9. `google/diffusiongemma-26b-a4b-it` (nvidia) — 274ms probe
10. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 276ms probe
11. `poolside/laguna-xs-2.1` (nvidia) — 278ms probe
12. `voxtral-small-latest` (mistral) — 302ms probe
13. `codestral-latest` (mistral) — 325ms probe
14. `voxtral-small-2507` (mistral) — 339ms probe
15. `codestral-2508` (mistral) — 351ms probe
16. `ministral-8b-2512` (mistral) — 365ms probe
17. `ministral-8b-latest` (mistral) — 368ms probe
18. `mistral-code-latest` (mistral) — 388ms probe
19. `mistral-code-fim-latest` (mistral) — 393ms probe
20. `ministral-3b-latest` (mistral) — 394ms probe
21. `ministral-3b-2512` (mistral) — 402ms probe
22. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 420ms probe
23. `gpt-oss:120b` (ollama) — 422ms probe
24. `gemma4:31b` (ollama) — 513ms probe
25. `z-ai/glm-5.3` (nvidia) — 536ms probe
26. `nemotron-3-super` (ollama) — 594ms probe
27. `nemotron-3-nano:30b` (ollama) — 599ms probe
28. `gpt-oss:20b` (ollama) — 625ms probe
29. `apodex/apodex-1.1-mini:free` (openrouter) — 663ms probe
30. `ministral-14b-latest` (mistral) — 727ms probe
31. `nemotron-3-ultra` (ollama) — 750ms probe
32. `ministral-14b-2512` (mistral) — 821ms probe
33. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 831ms probe
34. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 866ms probe
35. `glm-4.5-flash` (zai) — 878ms probe
36. `deepseek-ai/deepseek-v4.1-flash` (nvidia) — 884ms probe
37. `dots-studio/dots-3-note-preview:free` (openrouter) — 1061ms probe
38. `meta/muse-glimmer-30b` (nvidia) — 1368ms probe
39. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 1407ms probe
40. `z-ai/glm-5.3-flash` (nvidia) — 9530ms probe
41. `nvidia/ising-calibration-1.5-31b` (nvidia) — 12046ms probe

**Tool calling** (ranked):
1. `deepseek-ai/deepseek-v4.1-flash` (nvidia) — 1000k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3` (nvidia) — 1000k ctx
4. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
8. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
9. `ministral-14b-2512` (mistral) — 262k ctx
10. `ministral-8b-2512` (mistral) — 262k ctx
11. `ministral-8b-latest` (mistral) — 262k ctx
12. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
13. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
14. `codestral-2508` (mistral) — 256k ctx
15. `codestral-latest` (mistral) — 256k ctx
16. `cohere/north-mini-code:free` (openrouter) — 256k ctx
17. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
18. `openai/gpt-oss-120b` (groq) — 131k ctx
19. `openai/gpt-oss-20b` (groq) — 131k ctx
20. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
21. `openai/gpt-oss-20b` (nvidia) — 131k ctx
22. `ministral-3b-2512` (mistral) — 131k ctx
23. `ministral-3b-latest` (mistral) — 131k ctx
24. `glm-4.5-flash` (zai) — 131k ctx
25. `qwen/qwen3.8-27b` (groq) — 131k ctx
26. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
27. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
28. `voxtral-small-2507` (mistral) — 32k ctx
29. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `deepseek-ai/deepseek-v4.1-flash` (nvidia) — 1000k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3` (nvidia) — 1000k ctx
4. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
8. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
9. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
10. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
11. `cohere/north-mini-code:free` (openrouter) — 256k ctx
12. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
13. `openai/gpt-oss-120b` (groq) — 131k ctx
14. `openai/gpt-oss-20b` (groq) — 131k ctx
15. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
16. `openai/gpt-oss-20b` (nvidia) — 131k ctx
17. `glm-4.5-flash` (zai) — 131k ctx
18. `qwen/qwen3.8-27b` (groq) — 131k ctx

**Vision (image input)** (ranked):
1. `deepseek-ai/deepseek-v4.1-flash` (nvidia) — 1000k ctx
2. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `ministral-14b-2512` (mistral) — 262k ctx
5. `ministral-8b-2512` (mistral) — 262k ctx
6. `ministral-8b-latest` (mistral) — 262k ctx
7. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
8. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
9. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
10. `ministral-3b-2512` (mistral) — 131k ctx
11. `ministral-3b-latest` (mistral) — 131k ctx
12. `qwen/qwen3.8-27b` (groq) — 131k ctx
13. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
14. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Methodology

1. Check [aimodelwatch](https://aimodelwatch.dev) deprecations (free, keyless). Retired models skip probing — no point calling a corpse.
2. Snapshot each lane's `/v1/models` catalog.
3. Probe survivors with a tiny `hi` completion on a real free-tier key. The probe is the ground truth.
4. Three consecutive probe failures -> `unhealthy` (flagged, not silently kept).

## Disclaimer

Independent community resource, not affiliated with any provider. Free tiers change fast — verify before relying on this for anything that matters.
