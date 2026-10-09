# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-10-09T05:17:51Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-10-09 |
| `openai/gpt-oss-20b` | **active** | 122ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `allam-2-7b` | **active** | 278ms | ctx 4k | 2026-10-09 |
| `whisper-large-v3-turbo` | **not-chat** | — | — | 2026-10-09 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-10-09 |
| `openai/gpt-oss-120b` | **active** | 109ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `qwen/qwen3.8-27b` | **active** | 99ms | ctx 131k, tools, reasoning, vision | 2026-10-09 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-10-09 |
| `whisper-large-v3` | **not-chat** | — | — | 2026-10-09 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-10-09 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-10-09 |

</details>

<details><summary><b>nvidia</b> — 14/80 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `01-ai/yi-large` | **dead** | — | — | 2026-10-09 |
| `adept/fuyu-8b` | **dead** | — | — | 2026-10-09 |
| `ai21labs/jamba-1.5-large-instruct` | **dead** | — | — | 2026-10-09 |
| `aisingapore/sea-lion-7b-instruct` | **dead** | — | — | 2026-10-09 |
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-10-09 |
| `databricks/dbrx-instruct` | **dead** | — | — | 2026-10-09 |
| `deepseek-ai/deepseek-coder-6.7b-instruct` | **dead** | — | — | 2026-10-09 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-10-09 |
| `google/codegemma-1.1-7b` | **dead** | — | — | 2026-10-09 |
| `google/codegemma-7b` | **dead** | — | — | 2026-10-09 |
| `google/deplot` | **dead** | — | — | 2026-10-09 |
| `google/diffusiongemma-26b-a4b-it` | **active** | 629ms | ctx 250k, tools, reasoning, vision | 2026-10-09 |
| `google/gemma-2b` | **dead** | — | — | 2026-10-09 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-09 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-10-09 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-09 |
| `google/recurrentgemma-2b` | **dead** | — | — | 2026-10-09 |
| `ibm/granite-3.0-3b-a800m-instruct` | **dead** | — | — | 2026-10-09 |
| `ibm/granite-3.0-8b-instruct` | **dead** | — | — | 2026-10-09 |
| `ibm/granite-34b-code-instruct` | **dead** | — | — | 2026-10-09 |
| `ibm/granite-8b-code-instruct` | **dead** | — | — | 2026-10-09 |
| `meta/codellama-70b` | **dead** | — | — | 2026-10-09 |
| `meta/llama-3.2-11b-vision-instruct` | **active** | 16249ms | ctx 128k, tools, vision | 2026-10-09 |
| `meta/llama-3.2-90b-vision-instruct` | **active** | 4644ms | ctx 128k, tools, vision | 2026-10-09 |
| `meta/llama-guard-4-12b` | **not-chat** | — | ctx 128k, vision | 2026-10-09 |
| `meta/llama2-70b` | **dead** | — | — | 2026-10-09 |
| `meta/muse-glimmer-30b` | **active** | 2193ms | ctx 131k, tools, reasoning, vision | 2026-10-09 |
| `microsoft/kosmos-2` | **dead** | — | — | 2026-10-09 |
| `microsoft/phi-3-vision-128k-instruct` | **dead** | — | — | 2026-10-09 |
| `microsoft/phi-3.5-moe-instruct` | **dead** | — | — | 2026-10-09 |
| `mistralai/codestral-22b-instruct-v0.1` | **dead** | — | — | 2026-10-09 |
| `mistralai/mistral-7b-instruct-v0.3` | **dead** | — | ctx 65k, tools | 2026-10-09 |
| `mistralai/mistral-large` | **dead** | — | ctx 262k, tools, vision | 2026-10-09 |
| `mistralai/mistral-large-2-instruct` | **dead** | — | — | 2026-10-09 |
| `mistralai/mixtral-8x22b-v0.1` | **dead** | — | — | 2026-10-09 |
| `moonshotai/kimi-k2.6` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `moonshotai/kimi-k3` | **active** | 789ms | ctx 1048k, tools, reasoning, vision | 2026-10-09 |
| `nv-mistralai/mistral-nemo-12b-instruct` | **dead** | — | — | 2026-10-09 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-10-09 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-10-09 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/ising-calibration-1.5-31b` | **dead** | — | — | 2026-10-09 |
| `nvidia/llama-3.1-nemoguard-8b-content-safety` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/llama-3.1-nemotron-51b-instruct` | **dead** | — | — | 2026-10-09 |
| `nvidia/llama-3.1-nemotron-70b-instruct` | **dead** | — | ctx 128k, tools | 2026-10-09 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-10-09 |
| `nvidia/llama-3.1-nemotron-ultra-253b-v1` | **dead** | — | ctx 128k, tools, reasoning | 2026-10-09 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/llama-nemotron-embed-vl-1b-v2` | **not-chat** | — | ctx 32k, vision | 2026-10-09 |
| `nvidia/llama3-chatqa-1.5-70b` | **dead** | — | — | 2026-10-09 |
| `nvidia/mistral-nemo-minitron-8b-8k-instruct` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 1038ms | ctx 256k, tools, reasoning, vision | 2026-10-09 |
| `nvidia/nemotron-3-super-120b-a12b` | **active** | 286ms | ctx 262k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 782ms | ctx 1000k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-09 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 314ms | ctx 262k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-4-340b-instruct` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-4-340b-reward` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-nano-3-30b-a3b` | **dead** | — | — | 2026-10-09 |
| `nvidia/nemotron-parse` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/nemotron-parse-2.0` | **dead** | — | — | 2026-10-09 |
| `nvidia/neva-22b` | **dead** | — | — | 2026-10-09 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-10-09 |
| `nvidia/nvclip` | **dead** | — | — | 2026-10-09 |
| `nvidia/riva-translate-4b-instruct` | **dead** | — | ctx 128k | 2026-10-09 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 3542ms | — | 2026-10-09 |
| `nvidia/vila` | **dead** | — | — | 2026-10-09 |
| `openai/gpt-oss-20b` | **active** | 513ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `poolside/laguna-xs-2.1` | **active** | 3976ms | ctx 262k, tools, reasoning | 2026-10-09 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-10-09 |
| `writer/palmyra-creative-122b` | **dead** | — | — | 2026-10-09 |
| `writer/palmyra-fin-70b-32k` | **dead** | — | — | 2026-10-09 |
| `writer/palmyra-med-70b` | **dead** | — | — | 2026-10-09 |
| `writer/palmyra-med-70b-32k` | **dead** | — | — | 2026-10-09 |
| `z-ai/glm-5.3` | **active** | 2005ms | ctx 1000k, tools, reasoning | 2026-10-09 |
| `z-ai/glm-5.3-flash` | **active** | 5547ms | ctx 1000k, tools, reasoning, vision | 2026-10-09 |
| `zyphra/zamba2-7b-instruct` | **dead** | — | — | 2026-10-09 |

</details>

<details><summary><b>mistral</b> — 12/46 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 393ms | ctx 256k, tools | 2026-10-09 |
| `codestral-latest` | **active** | 361ms | ctx 256k, tools | 2026-10-09 |
| `mistral-code-latest` | **active** | 464ms | — | 2026-10-09 |
| `mistral-code-fim-latest` | **active** | 392ms | — | 2026-10-09 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `ministral-14b-2512` | **active** | 1051ms | ctx 262k, tools, vision | 2026-10-09 |
| `ministral-14b-latest` | **active** | 463ms | — | 2026-10-09 |
| `ministral-3b-2512` | **active** | 376ms | ctx 131k, tools, vision | 2026-10-09 |
| `ministral-3b-latest` | **active** | 294ms | ctx 131k, tools, vision | 2026-10-09 |
| `ministral-8b-2512` | **active** | 342ms | ctx 262k, tools, vision | 2026-10-09 |
| `ministral-8b-latest` | **active** | 381ms | ctx 262k, tools, vision | 2026-10-09 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, vision | 2026-10-09 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-10-09 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-10-09 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-10-09 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-10-09 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-10-09 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-10-09 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-10-09 |
| `voxtral-small-2507` | **active** | 431ms | ctx 32k, tools | 2026-10-09 |
| `voxtral-small-latest` | **active** | 379ms | ctx 32k, tools | 2026-10-09 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-10-09 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-10-09 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-10-09 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-10-09 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-4-0` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-10-09 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-10-09 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-10-09 |

</details>

<details><summary><b>zai</b> — 3/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 1260ms | ctx 200k, tools, reasoning | 2026-10-09 |
| `glm-4.5-flash` | **active** | 747ms | ctx 131k, tools, reasoning | 2026-10-09 |
| `glm-4.6v-flash` | **active** | 740ms | ctx 128k, tools, reasoning, vision | 2026-10-09 |

</details>

<details><summary><b>ollama</b> — 6/18 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `gpt-oss:20b` | **active** | 506ms | — | 2026-10-09 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-10-09 |
| `mistral-large-4` | **dead** | — | — | 2026-10-09 |
| `minimax-m2.7` | **dead** | — | — | 2026-10-09 |
| `gemma4:31b` | **active** | 419ms | — | 2026-10-09 |
| `glm-5.3` | **dead** | — | — | 2026-10-09 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-10-09 |
| `nemotron-3-nano:30b` | **active** | 705ms | — | 2026-10-09 |
| `nemotron-3-super` | **active** | 547ms | — | 2026-10-09 |
| `glm-5.2` | **dead** | — | — | 2026-10-09 |
| `glm-5.3-flash` | **dead** | — | — | 2026-10-09 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-10-09 |
| `minimax-m3` | **dead** | — | — | 2026-10-09 |
| `mistral-large-3:675b` | **dead** | — | — | 2026-10-09 |
| `gpt-oss:120b` | **active** | 417ms | — | 2026-10-09 |
| `nemotron-3-ultra` | **active** | 1947ms | — | 2026-10-09 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-10-09 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-10-09 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 226ms | ctx 128k, tools | 2026-10-09 |

</details>

<details><summary><b>openrouter</b> — 3/15 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `apodex/apodex-1.1-mini:free` | **active** | 728ms | ctx 262k, tools, reasoning | 2026-10-09 |
| `dots-studio/dots-3-note-preview:free` | **active** | 824ms | ctx 512k, tools, reasoning, vision | 2026-10-09 |
| `liquid/lfm-2.5-2.6b:free` | **dead** | — | ctx 65k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-09 |
| `thinkingmachines/inkling-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-09 |
| `poolside/laguna-s-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-09 |
| `thinkingmachines/inkling:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-10-09 |
| `poolside/laguna-xs-2.1:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-09 |
| `cohere/north-mini-code:free` | **active** | 222ms | ctx 256k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3.5-content-safety:free` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-10-09 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-10-09 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-10-09 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-10-09 |
| `nvidia/nemotron-3-super-120b-a12b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-10-09 |

</details>

<details><summary><b>llm7</b> — 0/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-10-09 |
| `GLM-5.3-Flash` | **dead** | — | — | 2026-10-09 |
| `codestral-latest` | **rate-limited** | — | — | 2026-10-09 |
| `gemma4:31b` | **rate-limited** | — | — | 2026-10-09 |
| `glm-5.2` | **rate-limited** | — | — | 2026-10-09 |
| `gpt-oss:20b` | **rate-limited** | — | — | 2026-10-09 |
| `minimax-m2.7` | **rate-limited** | — | — | 2026-10-09 |
| `minimax-m3` | **rate-limited** | — | — | 2026-10-09 |
| `mistral-Nemo-Instruct-2407` | **rate-limited** | — | — | 2026-10-09 |
| `nemotron-3-nano:30b` | **rate-limited** | — | — | 2026-10-09 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1,048,576 tokens
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
18. `glm-4.7-flash` (zai) — 200,000 tokens
19. `openai/gpt-oss-20b` (groq) — 131,072 tokens
20. `openai/gpt-oss-120b` (groq) — 131,072 tokens
21. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
22. `openai/gpt-oss-20b` (nvidia) — 131,072 tokens
23. `ministral-3b-2512` (mistral) — 131,072 tokens
24. `ministral-3b-latest` (mistral) — 131,072 tokens
25. `glm-4.5-flash` (zai) — 131,072 tokens
26. `qwen/qwen3.8-27b` (groq) — 131,042 tokens
27. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128,000 tokens
28. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128,000 tokens
29. `glm-4.6v-flash` (zai) — 128,000 tokens
30. `voxtral-small-2507` (mistral) — 32,768 tokens
31. `voxtral-small-latest` (mistral) — 32,768 tokens
32. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `qwen/qwen3.8-27b` (groq) — 99ms probe
2. `openai/gpt-oss-120b` (groq) — 109ms probe
3. `openai/gpt-oss-20b` (groq) — 122ms probe
4. `cohere/north-mini-code:free` (openrouter) — 222ms probe
5. `allam-2-7b` (groq) — 278ms probe
6. `nvidia/nemotron-3-super-120b-a12b` (nvidia) — 286ms probe
7. `ministral-3b-latest` (mistral) — 294ms probe
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 314ms probe
9. `ministral-8b-2512` (mistral) — 342ms probe
10. `codestral-latest` (mistral) — 361ms probe
11. `ministral-3b-2512` (mistral) — 376ms probe
12. `voxtral-small-latest` (mistral) — 379ms probe
13. `ministral-8b-latest` (mistral) — 381ms probe
14. `mistral-code-fim-latest` (mistral) — 392ms probe
15. `codestral-2508` (mistral) — 393ms probe
16. `gpt-oss:120b` (ollama) — 417ms probe
17. `gemma4:31b` (ollama) — 419ms probe
18. `voxtral-small-2507` (mistral) — 431ms probe
19. `ministral-14b-latest` (mistral) — 463ms probe
20. `mistral-code-latest` (mistral) — 464ms probe
21. `gpt-oss:20b` (ollama) — 506ms probe
22. `openai/gpt-oss-20b` (nvidia) — 513ms probe
23. `nemotron-3-super` (ollama) — 547ms probe
24. `google/diffusiongemma-26b-a4b-it` (nvidia) — 629ms probe
25. `nemotron-3-nano:30b` (ollama) — 705ms probe
26. `apodex/apodex-1.1-mini:free` (openrouter) — 728ms probe
27. `glm-4.6v-flash` (zai) — 740ms probe
28. `glm-4.5-flash` (zai) — 747ms probe
29. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 782ms probe
30. `moonshotai/kimi-k3` (nvidia) — 789ms probe
31. `dots-studio/dots-3-note-preview:free` (openrouter) — 824ms probe
32. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 1038ms probe
33. `ministral-14b-2512` (mistral) — 1051ms probe
34. `glm-4.7-flash` (zai) — 1260ms probe
35. `nemotron-3-ultra` (ollama) — 1947ms probe
36. `z-ai/glm-5.3` (nvidia) — 2005ms probe
37. `meta/muse-glimmer-30b` (nvidia) — 2193ms probe
38. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 3542ms probe
39. `poolside/laguna-xs-2.1` (nvidia) — 3976ms probe
40. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 4644ms probe
41. `z-ai/glm-5.3-flash` (nvidia) — 5547ms probe
42. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 16249ms probe

**Tool calling** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
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
18. `glm-4.7-flash` (zai) — 200k ctx
19. `openai/gpt-oss-20b` (groq) — 131k ctx
20. `openai/gpt-oss-120b` (groq) — 131k ctx
21. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
22. `openai/gpt-oss-20b` (nvidia) — 131k ctx
23. `ministral-3b-2512` (mistral) — 131k ctx
24. `ministral-3b-latest` (mistral) — 131k ctx
25. `glm-4.5-flash` (zai) — 131k ctx
26. `qwen/qwen3.8-27b` (groq) — 131k ctx
27. `meta/llama-3.2-11b-vision-instruct` (nvidia) — 128k ctx
28. `meta/llama-3.2-90b-vision-instruct` (nvidia) — 128k ctx
29. `glm-4.6v-flash` (zai) — 128k ctx
30. `voxtral-small-2507` (mistral) — 32k ctx
31. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `moonshotai/kimi-k3` (nvidia) — 1048k ctx
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
13. `glm-4.7-flash` (zai) — 200k ctx
14. `openai/gpt-oss-20b` (groq) — 131k ctx
15. `openai/gpt-oss-120b` (groq) — 131k ctx
16. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
17. `openai/gpt-oss-20b` (nvidia) — 131k ctx
18. `glm-4.5-flash` (zai) — 131k ctx
19. `qwen/qwen3.8-27b` (groq) — 131k ctx
20. `glm-4.6v-flash` (zai) — 128k ctx

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
15. `glm-4.6v-flash` (zai) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (354ms) | 1 day(s) |


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
