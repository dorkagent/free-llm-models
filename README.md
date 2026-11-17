# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-17T22:07:36Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `openai/gpt-oss-120b` | **active** | 322ms | ctx 131k, tools, reasoning | 2026-11-17 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-17 |
| `allam-2-7b` | **active** | 281ms | ctx 4k | 2026-11-17 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-17 |
| `qwen/qwen3.8-27b` | **active** | 306ms | ctx 131k, tools, reasoning, vision | 2026-11-17 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-17 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-17 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-17 |
| `openai/gpt-oss-20b` | **active** | 292ms | ctx 131k, tools, reasoning | 2026-11-17 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-17 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-17 |

</details>

<details><summary><b>nvidia</b> — 11/32 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-17 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-17 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-17 |
| `google/gemma-4-31b-it` | **active** | 16670ms | ctx 256k, tools, reasoning, vision | 2026-11-17 |
| `meta/muse-glimmer-30b` | **active** | 14781ms | ctx 131k, tools, reasoning, vision | 2026-11-17 |
| `minimaxai/minimax-m3.1-flash` | **active** | 616ms | ctx 262k, tools, reasoning, vision | 2026-11-17 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 319ms | ctx 1000k | 2026-11-17 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-17 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-17 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-17 |
| `nvidia/ising-calibration-1.5-31b` | **dead** | — | — | 2026-11-17 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-17 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-17 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-17 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-17 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-11-17 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 269ms | ctx 256k, tools, reasoning, vision | 2026-11-17 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 1370ms | ctx 1000k, tools, reasoning | 2026-11-17 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 279ms | — | 2026-11-17 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-17 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-17 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-17 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 218ms | ctx 262k, tools, reasoning | 2026-11-17 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 379ms | ctx 1048k, tools, reasoning, vision | 2026-11-17 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-17 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-17 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 296ms | — | 2026-11-17 |
| `openai/gpt-oss-20b` | **dead** | — | ctx 131k, tools, reasoning | 2026-11-17 |
| `poolside/laguna-xs-2.1` | **active** | 242ms | ctx 262k, tools, reasoning | 2026-11-17 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-17 |
| `stepfun-ai/step-5-preview` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-17 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-17 |

</details>

<details><summary><b>mistral</b> — 10/53 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 369ms | ctx 256k, tools | 2026-11-17 |
| `codestral-latest` | **active** | 321ms | ctx 256k, tools | 2026-11-17 |
| `mistral-code-latest` | **rate-limited** | — | — | 2026-11-17 |
| `mistral-code-fim-latest` | **rate-limited** | — | — | 2026-11-17 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-17 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-17 |
| `ministral-14b-2512` | **active** | 335ms | ctx 262k, tools, vision | 2026-11-17 |
| `ministral-14b-latest` | **active** | 384ms | — | 2026-11-17 |
| `ministral-3b-2512` | **active** | 454ms | ctx 131k, tools, vision | 2026-11-17 |
| `ministral-3b-latest` | **active** | 371ms | ctx 131k, tools, vision | 2026-11-17 |
| `ministral-8b-2512` | **active** | 315ms | ctx 262k, tools, vision | 2026-11-17 |
| `ministral-8b-latest` | **active** | 402ms | ctx 262k, tools, vision | 2026-11-17 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-17 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-17 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-17 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-17 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-17 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-17 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-17 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-17 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-17 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-17 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-17 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-17 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-17 |
| `voxtral-small-2507` | **active** | 624ms | ctx 32k, tools | 2026-11-17 |
| `voxtral-small-latest` | **active** | 388ms | ctx 32k, tools | 2026-11-17 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-17 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-17 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-17 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-17 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-17 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-17 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-17 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-17 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-17 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-17 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-17 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-17 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **dead** | — | ctx 200k, tools, reasoning | 2026-11-17 |
| `glm-4.5-flash` | **active** | 798ms | ctx 131k, tools, reasoning | 2026-11-17 |
| `glm-4.6v-flash` | **active** | 693ms | ctx 128k, tools, reasoning, vision | 2026-11-17 |

</details>

<details><summary><b>ollama</b> — 0/24 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `gpt-oss:120b` | **dead** | — | — | 2026-11-17 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-17 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-17 |
| `glm-5.3` | **dead** | — | — | 2026-11-17 |
| `gpt-oss:20b` | **dead** | — | — | 2026-11-17 |
| `nemotron-3-ultra` | **dead** | — | — | 2026-11-17 |
| `glm-5.2` | **dead** | — | — | 2026-11-17 |
| `minimax-m3` | **dead** | — | — | 2026-11-17 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-17 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-17 |
| `nemotron-3-super` | **dead** | — | — | 2026-11-17 |
| `inkling-2-small` | **dead** | — | — | 2026-11-17 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-17 |
| `kimi-k3.1-pro` | **dead** | — | ctx 1048k | 2026-11-17 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-17 |
| `gemma4:31b` | **dead** | — | — | 2026-11-17 |
| `mistral-large-4` | **dead** | — | ctx 1000k | 2026-11-17 |
| `clef:27b` | **not-chat** | — | — | 2026-11-17 |
| `muse-spark-open` | **dead** | — | — | 2026-11-17 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-17 |
| `beam` | **dead** | — | — | 2026-11-17 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-17 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-17 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-17 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 244ms | ctx 128k, tools | 2026-11-17 |

</details>

<details><summary><b>openrouter</b> — 5/14 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `inclusionai/ling-3.2-flash:free` | **active** | 1241ms | ctx 1048k, tools, reasoning, vision | 2026-11-17 |
| `baidu/ernie-5.5-flash-preview:free` | **active** | 1871ms | ctx 1024k, tools, reasoning | 2026-11-17 |
| `thinkingmachines/inkling-2-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-17 |
| `liquid/lfm-3-1.7b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-17 |
| `particle-ai/particle-1:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-17 |
| `recursive/flint-v1.0:free` | **active** | 509ms | ctx 262k, tools, reasoning | 2026-11-17 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-17 |
| `dots-studio/dots-3-note-preview:free` | **active** | 1117ms | ctx 512k, tools, reasoning, vision | 2026-11-17 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-17 |
| `cohere/north-mini-code:free` | **active** | 313ms | ctx 256k, tools, reasoning | 2026-11-17 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-17 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-17 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-17 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-17 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-17 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-11-17 |
| `codestral-latest` | **active** | 552ms | — | 2026-11-17 |
| `gemma4:31b` | **active** | 1486ms | — | 2026-11-17 |
| `glm-5.2` | **dead** | — | — | 2026-11-17 |
| `gpt-oss:20b` | **active** | 5101ms | — | 2026-11-17 |
| `minimax-m2.7` | **active** | 6432ms | — | 2026-11-17 |
| `minimax-m3` | **dead** | — | — | 2026-11-17 |
| `mistral-Nemo-Instruct-2407` | **rate-limited** | — | — | 2026-11-17 |
| `nemotron-3-nano:30b` | **not-chat** | — | — | 2026-11-17 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `inclusionai/ling-3.2-flash:free` (openrouter) — 1,048,576 tokens
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1,024,000 tokens
4. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 1,000,000 tokens
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
7. `minimaxai/minimax-m3.1-flash` (nvidia) — 262,144 tokens
8. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
9. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
10. `ministral-14b-2512` (mistral) — 262,144 tokens
11. `ministral-8b-2512` (mistral) — 262,144 tokens
12. `ministral-8b-latest` (mistral) — 262,144 tokens
13. `recursive/flint-v1.0:free` (openrouter) — 262,144 tokens
14. `google/gemma-4-31b-it` (nvidia) — 256,000 tokens
15. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
16. `codestral-2508` (mistral) — 256,000 tokens
17. `codestral-latest` (mistral) — 256,000 tokens
18. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
19. `openai/gpt-oss-120b` (groq) — 131,072 tokens
20. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
21. `openai/gpt-oss-20b` (groq) — 131,072 tokens
22. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
23. `ministral-3b-2512` (mistral) — 131,072 tokens
24. `ministral-3b-latest` (mistral) — 131,072 tokens
25. `glm-4.5-flash` (zai) — 131,072 tokens
26. `glm-4.6v-flash` (zai) — 128,000 tokens
27. `voxtral-small-2507` (mistral) — 32,768 tokens
28. `voxtral-small-latest` (mistral) — 32,768 tokens
29. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 218ms probe
2. `poolside/laguna-xs-2.1` (nvidia) — 242ms probe
3. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 269ms probe
4. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 279ms probe
5. `allam-2-7b` (groq) — 281ms probe
6. `openai/gpt-oss-20b` (groq) — 292ms probe
7. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 296ms probe
8. `qwen/qwen3.8-27b` (groq) — 306ms probe
9. `cohere/north-mini-code:free` (openrouter) — 313ms probe
10. `ministral-8b-2512` (mistral) — 315ms probe
11. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 319ms probe
12. `codestral-latest` (mistral) — 321ms probe
13. `openai/gpt-oss-120b` (groq) — 322ms probe
14. `ministral-14b-2512` (mistral) — 335ms probe
15. `codestral-2508` (mistral) — 369ms probe
16. `ministral-3b-latest` (mistral) — 371ms probe
17. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 379ms probe
18. `ministral-14b-latest` (mistral) — 384ms probe
19. `voxtral-small-latest` (mistral) — 388ms probe
20. `ministral-8b-latest` (mistral) — 402ms probe
21. `ministral-3b-2512` (mistral) — 454ms probe
22. `recursive/flint-v1.0:free` (openrouter) — 509ms probe
23. `codestral-latest` (llm7) — 552ms probe
24. `minimaxai/minimax-m3.1-flash` (nvidia) — 616ms probe
25. `voxtral-small-2507` (mistral) — 624ms probe
26. `glm-4.6v-flash` (zai) — 693ms probe
27. `glm-4.5-flash` (zai) — 798ms probe
28. `dots-studio/dots-3-note-preview:free` (openrouter) — 1117ms probe
29. `inclusionai/ling-3.2-flash:free` (openrouter) — 1241ms probe
30. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1370ms probe
31. `gemma4:31b` (llm7) — 1486ms probe
32. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1871ms probe
33. `gpt-oss:20b` (llm7) — 5101ms probe
34. `minimax-m2.7` (llm7) — 6432ms probe
35. `meta/muse-glimmer-30b` (nvidia) — 14781ms probe
36. `google/gemma-4-31b-it` (nvidia) — 16670ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `inclusionai/ling-3.2-flash:free` (openrouter) — 1048k ctx
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
8. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
9. `ministral-14b-2512` (mistral) — 262k ctx
10. `ministral-8b-2512` (mistral) — 262k ctx
11. `ministral-8b-latest` (mistral) — 262k ctx
12. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
13. `google/gemma-4-31b-it` (nvidia) — 256k ctx
14. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
15. `codestral-2508` (mistral) — 256k ctx
16. `codestral-latest` (mistral) — 256k ctx
17. `cohere/north-mini-code:free` (openrouter) — 256k ctx
18. `openai/gpt-oss-120b` (groq) — 131k ctx
19. `qwen/qwen3.8-27b` (groq) — 131k ctx
20. `openai/gpt-oss-20b` (groq) — 131k ctx
21. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
22. `ministral-3b-2512` (mistral) — 131k ctx
23. `ministral-3b-latest` (mistral) — 131k ctx
24. `glm-4.5-flash` (zai) — 131k ctx
25. `glm-4.6v-flash` (zai) — 128k ctx
26. `voxtral-small-2507` (mistral) — 32k ctx
27. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `inclusionai/ling-3.2-flash:free` (openrouter) — 1048k ctx
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
8. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
9. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
10. `google/gemma-4-31b-it` (nvidia) — 256k ctx
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
12. `cohere/north-mini-code:free` (openrouter) — 256k ctx
13. `openai/gpt-oss-120b` (groq) — 131k ctx
14. `qwen/qwen3.8-27b` (groq) — 131k ctx
15. `openai/gpt-oss-20b` (groq) — 131k ctx
16. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
17. `glm-4.5-flash` (zai) — 131k ctx
18. `glm-4.6v-flash` (zai) — 128k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `inclusionai/ling-3.2-flash:free` (openrouter) — 1048k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `minimaxai/minimax-m3.1-flash` (nvidia) — 262k ctx
5. `ministral-14b-2512` (mistral) — 262k ctx
6. `ministral-8b-2512` (mistral) — 262k ctx
7. `ministral-8b-latest` (mistral) — 262k ctx
8. `google/gemma-4-31b-it` (nvidia) — 256k ctx
9. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
10. `qwen/qwen3.8-27b` (groq) — 131k ctx
11. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
12. `ministral-3b-2512` (mistral) — 131k ctx
13. `ministral-3b-latest` (mistral) — 131k ctx
14. `glm-4.6v-flash` (zai) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (2906ms) | 1 day(s) |


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
