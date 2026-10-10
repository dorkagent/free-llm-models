# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-10T14:13:43Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-10 |
| `openai/gpt-oss-20b` | **active** | 67ms | ctx 131k, tools, reasoning | 2026-10-10 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-10 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-10 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-10 |
| `qwen/qwen3.8-27b` | **active** | 131ms | ctx 131k, tools, reasoning, vision | 2026-10-10 |
| `openai/gpt-oss-120b` | **active** | 242ms | ctx 131k, tools, reasoning | 2026-10-10 |
| `allam-2-7b` | **active** | 263ms | ctx 4k | 2026-10-10 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-10 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-10 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-10 |

</details>

<details><summary><b>nvidia</b> — 15/80 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-10 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-10 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-10 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-10 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-10 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-10 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-10 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-10 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-10 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-10 |
| `google/deplot` | **dead** | — | — | 2026-10-10 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 529ms | ctx 250k, tools, reasoning, vision | 2026-10-10 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-10 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-10 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-10 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-10 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-10 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-10 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-10 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-10 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-10 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-10 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 1371ms | ctx 128k, tools, vision | 2026-10-10 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 16500ms | ctx 128k, tools, vision | 2026-10-10 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-10 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-10 |
| `meta/muse-glimmer-30b` | **active** | 1543ms | ctx 131k, tools, reasoning, vision | 2026-10-10 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-10 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-10 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-10 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-10 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-10 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-10 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-10 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-10 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-10 |
| `moonshotai/kimi-k3` | **active** | 1872ms | ctx 1048k, tools, reasoning, vision | 2026-10-10 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-10 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-10 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-10 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-10 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 399ms | — | 2026-10-10 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-10 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-10 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-10 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-10 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-10 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-10 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-10 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-10 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-10 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-10 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-10 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-10 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 827ms | ctx 256k, tools, reasoning, vision | 2026-10-10 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 314ms | ctx 262k, tools, reasoning | 2026-10-10 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 680ms | ctx 1000k, tools, reasoning | 2026-10-10 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-10 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 265ms | ctx 262k, tools, reasoning | 2026-10-10 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-10 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-10 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-10 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-10 |
| `nvidia/nemotron-parse-2.0` | **active** | 212ms | — | 2026-10-10 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-10 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-10 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-10 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-10 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 13075ms | — | 2026-10-10 |
| `nvidia/vila` | **dead** | — | — | 2026-10-10 |
| `openai/gpt-oss-20b` | **active** | 490ms | ctx 131k, tools, reasoning | 2026-10-10 |
| `poolside/laguna-xs-2.1` | **active** | 1192ms | ctx 262k, tools, reasoning | 2026-10-10 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-10 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-10 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-10 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-10 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-10 |
| `z-ai/glm-5.3` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-10 |
| `z-ai/glm-5.3-flash` | **active** | 391ms | ctx 1000k, tools, reasoning, vision | 2026-10-10 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-10 |

</details>

<details><summary><b>mistral</b> — 12/46 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 349ms | ctx 256k, tools | 2026-10-10 |
| `codestral-latest` | **active** | 299ms | ctx 256k, tools | 2026-10-10 |
| `mistral-code-latest` | **active** | 311ms | — | 2026-10-10 |
| `mistral-code-fim-latest` | **active** | 361ms | — | 2026-10-10 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-10 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-10 |
| `ministral-14b-2512` | **active** | 362ms | ctx 262k, tools, vision | 2026-10-10 |
| `ministral-14b-latest` | **active** | 491ms | — | 2026-10-10 |
| `ministral-3b-2512` | **active** | 308ms | ctx 131k, tools, vision | 2026-10-10 |
| `ministral-3b-latest` | **active** | 309ms | ctx 131k, tools, vision | 2026-10-10 |
| `ministral-8b-2512` | **active** | 319ms | ctx 262k, tools, vision | 2026-10-10 |
| `ministral-8b-latest` | **active** | 346ms | ctx 262k, tools, vision | 2026-10-10 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-10 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-10 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-10 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-10 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-10 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-10 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-10 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-10 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-10 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-10 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-10 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-10 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-10 |
| `voxtral-small-2507` | **active** | 368ms | ctx 32k, tools | 2026-10-10 |
| `voxtral-small-latest` | **active** | 294ms | ctx 32k, tools | 2026-10-10 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-10 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-10 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-10 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-10 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-10 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-10 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-10 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-10 |
| `mistral-ocr-4-0` | **not-chat** | — | — | 2026-10-10 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-10 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-10 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-10 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-10 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-10 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-10 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-10 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-10 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-10 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-10 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 20979ms | ctx 200k, tools, reasoning | 2026-10-10 |
| `glm-4.5-flash` | **active** | 1000ms | ctx 131k, tools, reasoning | 2026-10-10 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-10-10 |

</details>

<details><summary><b>ollama</b> — 6/18 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-5.2` | **dead** | — | — | 2026-10-10 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-10 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-10 |
| `glm-5.3` | **dead** | — | — | 2026-10-10 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-10 |
| `gemma4:31b` | **active** | 392ms | — | 2026-10-10 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-10 |
| `nemotron-3-nano:30b` | **active** | 732ms | — | 2026-10-10 |
| `nemotron-3-super` | **active** | 518ms | — | 2026-10-10 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-10 |
| `gpt-oss:120b` | **active** | 367ms | — | 2026-10-10 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-10 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-10 |
| `gpt-oss:20b` | **active** | 482ms | — | 2026-10-10 |
| `minimax-m3` | **dead** | — | — | 2026-10-10 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-10 |
| `mistral-large-4` | **dead** | — | — | 2026-10-10 |
| `nemotron-3-ultra` | **active** | 714ms | — | 2026-10-10 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 261ms | ctx 128k, tools | 2026-10-10 |

</details>

<details><summary><b>openrouter</b> — 3/15 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `apodex/apodex-1.1-mini:free` | **active** | 765ms | ctx 262k, tools, reasoning | 2026-10-10 |
| `dots-studio/dots-3-note-preview:free` | **active** | 1194ms | ctx 512k, tools, reasoning, vision | 2026-10-10 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-10 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-10 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-10 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-10 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-10 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-10 |
| `cohere/north-mini-code:free` | **active** | 206ms | ctx 256k, tools, reasoning | 2026-10-10 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-10 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-10 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-10 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-10 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-10 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-10 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-10 |
| `GLM-5.3-Flash` | **dead** | — | — | 2026-10-10 |
| `codestral-latest` | **active** | 400ms | — | 2026-10-10 |
| `gemma4:31b` | **dead** | — | — | 2026-10-10 |
| `glm-5.2` | **dead** | — | — | 2026-10-10 |
| `gpt-oss:20b` | **active** | 770ms | — | 2026-10-10 |
| `minimax-m2.7` | **not-chat** | — | — | 2026-10-10 |
| `minimax-m3` | **dead** | — | — | 2026-10-10 |
| `mistral-Nemo-Instruct-2407` | **active** | 626ms | — | 2026-10-10 |
| `nemotron-3-nano:30b` | **active** | 1257ms | — | 2026-10-10 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1,048,576 tokens
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
3. `z-ai/glm-5.3-flash` (nvidia) — 1,000,000 tokens
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262,144 tokens
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
7. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
8. `ministral-14b-2512` (mistral) — 262,144 tokens
9. `ministral-8b-2512` (mistral) — 262,144 tokens
10. `ministral-8b-latest` (mistral) — 262,144 tokens
11. `apodex/apodex-1.1-mini:free` (openrouter) — 262,144 tokens
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
13. `codestral-2508` (mistral) — 256,000 tokens
14. `codestral-latest` (mistral) — 256,000 tokens
15. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
16. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250,000 tokens
17. `glm-4.7-flash` (zai) — 200,000 tokens
18. `openai/gpt-oss-20b` (groq) — 131,072 tokens
19. `openai/gpt-oss-120b` (groq) — 131,072 tokens
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
1. `openai/gpt-oss-20b` (groq) — 67ms probe
2. `qwen/qwen3.8-27b` (groq) — 131ms probe
3. `cohere/north-mini-code:free` (openrouter) — 206ms probe
4. `nvidia/nemotron-parse-2.0` (nvidia) — 212ms probe
5. `openai/gpt-oss-120b` (groq) — 242ms probe
6. `allam-2-7b` (groq) — 263ms probe
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 265ms probe
8. `voxtral-small-latest` (mistral) — 294ms probe
9. `codestral-latest` (mistral) — 299ms probe
10. `ministral-3b-2512` (mistral) — 308ms probe
11. `ministral-3b-latest` (mistral) — 309ms probe
12. `mistral-code-latest` (mistral) — 311ms probe
13. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 314ms probe
14. `ministral-8b-2512` (mistral) — 319ms probe
15. `ministral-8b-latest` (mistral) — 346ms probe
16. `codestral-2508` (mistral) — 349ms probe
17. `mistral-code-fim-latest` (mistral) — 361ms probe
18. `ministral-14b-2512` (mistral) — 362ms probe
19. `gpt-oss:120b` (ollama) — 367ms probe
20. `voxtral-small-2507` (mistral) — 368ms probe
21. `z-ai/glm-5.3-flash` (nvidia) — 391ms probe
22. `gemma4:31b` (ollama) — 392ms probe
23. `nvidia/ising-calibration-1.5-31b` (nvidia) — 399ms probe
24. `codestral-latest` (llm7) — 400ms probe
25. `gpt-oss:20b` (ollama) — 482ms probe
26. `openai/gpt-oss-20b` (nvidia) — 490ms probe
27. `ministral-14b-latest` (mistral) — 491ms probe
28. `nemotron-3-super` (ollama) — 518ms probe
29. `google/diffusiongemma-26b-a4b-it` (nvidia) — 529ms probe
30. `mistral-Nemo-Instruct-2407` (llm7) — 626ms probe
31. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 680ms probe
32. `nemotron-3-ultra` (ollama) — 714ms probe
33. `nemotron-3-nano:30b` (ollama) — 732ms probe
34. `apodex/apodex-1.1-mini:free` (openrouter) — 765ms probe
35. `gpt-oss:20b` (llm7) — 770ms probe
36. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 827ms probe
37. `glm-4.5-flash` (zai) — 1000ms probe
38. `poolside/laguna-xs-2.1` (nvidia) — 1192ms probe
39. `dots-studio/dots-3-note-preview:free` (openrouter) — 1194ms probe
40. `nemotron-3-nano:30b` (llm7) — 1257ms probe
41. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 1371ms probe
42. `meta/muse-glimmer-30b` (nvidia) — 1543ms probe
43. `moonshotai/kimi-k3` (nvidia) — 1872ms probe
44. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 13075ms probe
45. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 16500ms probe
46. `glm-4.7-flash` (zai) — 20979ms probe

**Tool calling** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
8. `ministral-14b-2512` (mistral) — 262k ctx
9. `ministral-8b-2512` (mistral) — 262k ctx
10. `ministral-8b-latest` (mistral) — 262k ctx
11. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
13. `codestral-2508` (mistral) — 256k ctx
14. `codestral-latest` (mistral) — 256k ctx
15. `cohere/north-mini-code:free` (openrouter) — 256k ctx
16. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
17. `glm-4.7-flash` (zai) — 200k ctx
18. `openai/gpt-oss-20b` (groq) — 131k ctx
19. `openai/gpt-oss-120b` (groq) — 131k ctx
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
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
2. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
3. `z-ai/glm-5.3-flash` (nvidia) — 1000k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 262k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
8. `apodex/apodex-1.1-mini:free` (openrouter) — 262k ctx
9. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
10. `cohere/north-mini-code:free` (openrouter) — 256k ctx
11. `google/diffusiongemma-26b-a4b-it` (nvidia) — 250k ctx
12. `glm-4.7-flash` (zai) — 200k ctx
13. `openai/gpt-oss-20b` (groq) — 131k ctx
14. `openai/gpt-oss-120b` (groq) — 131k ctx
15. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
16. `openai/gpt-oss-20b` (nvidia) — 131k ctx
17. `glm-4.5-flash` (zai) — 131k ctx
18. `qwen/qwen3.8-27b` (groq) — 131k ctx

**Vision (image input)** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
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


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (300ms) | 1 day(s) |


## Lane quotas (daily snapshot)

Where each lane stands on its free allowance. Quota comes from rate-limit headers captured off the probe responses (zero extra requests), except OpenRouter which needs one daily call to its key endpoint. Keys never leave the private verifier repo; only aggregate remaining counts are published here.

| Lane | Source | Requests remaining | Request limit | Reset / note |
|---|---|---|---|---|
| groq | response-headers | 6999 | 7000 | resets in 12.342s |
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
