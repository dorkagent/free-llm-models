# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-18T21:44:53Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-18 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-18 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-18 |
| `qwen/qwen3.8-27b` | **active** | 663ms | ctx 131k, tools, reasoning, vision | 2026-11-18 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-18 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-18 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-18 |
| `openai/gpt-oss-20b` | **active** | 211ms | ctx 131k, tools, reasoning | 2026-11-18 |
| `allam-2-7b` | **active** | 389ms | ctx 4k | 2026-11-18 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-18 |
| `openai/gpt-oss-120b` | **active** | 197ms | ctx 131k, tools, reasoning | 2026-11-18 |

</details>

<details><summary><b>nvidia</b> — 12/32 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-18 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-18 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-18 |
| `google/gemma-4-31b-it` | **active** | 547ms | ctx 256k, tools, reasoning, vision | 2026-11-18 |
| `meta/muse-glimmer-30b` | **active** | 1229ms | ctx 131k, tools, reasoning, vision | 2026-11-18 |
| `minimaxai/minimax-m3.1-flash` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-18 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 1815ms | ctx 1000k | 2026-11-18 |
| `moonshotai/kimi-k3.1-pro` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-18 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-18 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-18 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-18 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 968ms | — | 2026-11-18 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-18 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-18 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-18 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-18 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-11-18 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 239ms | ctx 256k, tools, reasoning, vision | 2026-11-18 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 577ms | ctx 1000k, tools, reasoning | 2026-11-18 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 321ms | — | 2026-11-18 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-18 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-18 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-18 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 262ms | ctx 262k, tools, reasoning | 2026-11-18 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 392ms | ctx 1048k, tools, reasoning, vision | 2026-11-18 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-18 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-18 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 307ms | — | 2026-11-18 |
| `poolside/laguna-xs-2.1` | **active** | 538ms | ctx 262k, tools, reasoning | 2026-11-18 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-18 |
| `stepfun-ai/step-5-preview` | **active** | 440ms | ctx 1048k, tools, reasoning, vision | 2026-11-18 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-18 |

</details>

<details><summary><b>mistral</b> — 10/51 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 354ms | ctx 256k, tools | 2026-11-18 |
| `codestral-latest` | **active** | 331ms | ctx 256k, tools | 2026-11-18 |
| `mistral-code-latest` | **rate-limited** | — | — | 2026-11-18 |
| `mistral-code-fim-latest` | **rate-limited** | — | — | 2026-11-18 |
| `ministral-14b-2512` | **active** | 347ms | ctx 262k, tools, vision | 2026-11-18 |
| `ministral-14b-latest` | **active** | 528ms | — | 2026-11-18 |
| `ministral-3b-2512` | **active** | 414ms | ctx 131k, tools, vision | 2026-11-18 |
| `ministral-3b-latest` | **active** | 326ms | ctx 131k, tools, vision | 2026-11-18 |
| `ministral-8b-2512` | **active** | 390ms | ctx 262k, tools, vision | 2026-11-18 |
| `ministral-8b-latest` | **active** | 380ms | ctx 262k, tools, vision | 2026-11-18 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-18 |
| `mistral-medium` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-18 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-18 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-18 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-18 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-18 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-18 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-18 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-18 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-18 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-18 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-18 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-18 |
| `voxtral-small-2507` | **active** | 314ms | ctx 32k, tools | 2026-11-18 |
| `voxtral-small-latest` | **active** | 366ms | ctx 32k, tools | 2026-11-18 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-18 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-18 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-18 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-18 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-18 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-18 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-18 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-18 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-18 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-18 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-18 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-18 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **active** | 1312ms | ctx 200k, tools, reasoning | 2026-11-18 |
| `glm-4.5-flash` | **active** | 657ms | ctx 131k, tools, reasoning | 2026-11-18 |
| `glm-4.6v-flash` | **rate-limited** | — | ctx 128k, tools, reasoning, vision | 2026-11-18 |

</details>

<details><summary><b>ollama</b> — 0/24 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-5.2` | **dead** | — | — | 2026-11-18 |
| `beam` | **dead** | — | — | 2026-11-18 |
| `inkling-2-small` | **dead** | — | — | 2026-11-18 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-18 |
| `minimax-m3` | **dead** | — | — | 2026-11-18 |
| `gemma4:31b` | **dead** | — | — | 2026-11-18 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-18 |
| `gpt-oss:120b` | **dead** | — | — | 2026-11-18 |
| `nemotron-3-super` | **dead** | — | — | 2026-11-18 |
| `muse-spark-open` | **dead** | — | — | 2026-11-18 |
| `gpt-oss:20b` | **dead** | — | — | 2026-11-18 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-18 |
| `glm-5.3` | **dead** | — | — | 2026-11-18 |
| `kimi-k3.1-pro` | **dead** | — | ctx 1048k | 2026-11-18 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-18 |
| `nemotron-3-ultra` | **dead** | — | — | 2026-11-18 |
| `mistral-large-4` | **dead** | — | ctx 1000k | 2026-11-18 |
| `clef:27b` | **not-chat** | — | — | 2026-11-18 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-18 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-18 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-18 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-18 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-18 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-18 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 260ms | ctx 128k, tools | 2026-11-18 |

</details>

<details><summary><b>openrouter</b> — 5/14 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `inclusionai/ling-3.2-flash:free` | **active** | 1061ms | ctx 1048k, tools, reasoning, vision | 2026-11-18 |
| `baidu/ernie-5.5-flash-preview:free` | **active** | 801ms | ctx 1024k, tools, reasoning | 2026-11-18 |
| `thinkingmachines/inkling-2-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-18 |
| `liquid/lfm-3-1.7b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-18 |
| `particle-ai/particle-1:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-18 |
| `recursive/flint-v1.0:free` | **active** | 307ms | ctx 262k, tools, reasoning | 2026-11-18 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-18 |
| `dots-studio/dots-3-note-preview:free` | **active** | 883ms | ctx 512k, tools, reasoning, vision | 2026-11-18 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-18 |
| `cohere/north-mini-code:free` | **active** | 338ms | ctx 256k, tools, reasoning | 2026-11-18 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-18 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-18 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-18 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-18 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-18 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-11-18 |
| `codestral-latest` | **active** | 2359ms | — | 2026-11-18 |
| `gemma4:31b` | **active** | 4173ms | — | 2026-11-18 |
| `glm-5.2` | **dead** | — | — | 2026-11-18 |
| `gpt-oss:20b` | **active** | 2027ms | — | 2026-11-18 |
| `minimax-m2.7` | **not-chat** | — | — | 2026-11-18 |
| `minimax-m3` | **dead** | — | — | 2026-11-18 |
| `mistral-Nemo-Instruct-2407` | **active** | 3485ms | — | 2026-11-18 |
| `nemotron-3-nano:30b` | **not-chat** | — | — | 2026-11-18 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `stepfun-ai/step-5-preview` (nvidia) — 1,048,576 tokens
3. `inclusionai/ling-3.2-flash:free` (openrouter) — 1,048,576 tokens
4. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1,024,000 tokens
5. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 1,000,000 tokens
6. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
7. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
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
19. `glm-4.7-flash` (zai) — 200,000 tokens
20. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
21. `openai/gpt-oss-20b` (groq) — 131,072 tokens
22. `openai/gpt-oss-120b` (groq) — 131,072 tokens
23. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
24. `ministral-3b-2512` (mistral) — 131,072 tokens
25. `ministral-3b-latest` (mistral) — 131,072 tokens
26. `glm-4.5-flash` (zai) — 131,072 tokens
27. `voxtral-small-2507` (mistral) — 32,768 tokens
28. `voxtral-small-latest` (mistral) — 32,768 tokens
29. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `openai/gpt-oss-120b` (groq) — 197ms probe
2. `openai/gpt-oss-20b` (groq) — 211ms probe
3. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 239ms probe
4. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262ms probe
5. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 307ms probe
6. `recursive/flint-v1.0:free` (openrouter) — 307ms probe
7. `voxtral-small-2507` (mistral) — 314ms probe
8. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 321ms probe
9. `ministral-3b-latest` (mistral) — 326ms probe
10. `codestral-latest` (mistral) — 331ms probe
11. `cohere/north-mini-code:free` (openrouter) — 338ms probe
12. `ministral-14b-2512` (mistral) — 347ms probe
13. `codestral-2508` (mistral) — 354ms probe
14. `voxtral-small-latest` (mistral) — 366ms probe
15. `ministral-8b-latest` (mistral) — 380ms probe
16. `allam-2-7b` (groq) — 389ms probe
17. `ministral-8b-2512` (mistral) — 390ms probe
18. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 392ms probe
19. `ministral-3b-2512` (mistral) — 414ms probe
20. `stepfun-ai/step-5-preview` (nvidia) — 440ms probe
21. `ministral-14b-latest` (mistral) — 528ms probe
22. `poolside/laguna-xs-2.1` (nvidia) — 538ms probe
23. `google/gemma-4-31b-it` (nvidia) — 547ms probe
24. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 577ms probe
25. `glm-4.5-flash` (zai) — 657ms probe
26. `qwen/qwen3.8-27b` (groq) — 663ms probe
27. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 801ms probe
28. `dots-studio/dots-3-note-preview:free` (openrouter) — 883ms probe
29. `nvidia/ising-calibration-1.5-31b` (nvidia) — 968ms probe
30. `inclusionai/ling-3.2-flash:free` (openrouter) — 1061ms probe
31. `meta/muse-glimmer-30b` (nvidia) — 1229ms probe
32. `glm-4.7-flash` (zai) — 1312ms probe
33. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 1815ms probe
34. `gpt-oss:20b` (llm7) — 2027ms probe
35. `codestral-latest` (llm7) — 2359ms probe
36. `mistral-Nemo-Instruct-2407` (llm7) — 3485ms probe
37. `gemma4:31b` (llm7) — 4173ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `inclusionai/ling-3.2-flash:free` (openrouter) — 1048k ctx
4. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
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
18. `glm-4.7-flash` (zai) — 200k ctx
19. `qwen/qwen3.8-27b` (groq) — 131k ctx
20. `openai/gpt-oss-20b` (groq) — 131k ctx
21. `openai/gpt-oss-120b` (groq) — 131k ctx
22. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
23. `ministral-3b-2512` (mistral) — 131k ctx
24. `ministral-3b-latest` (mistral) — 131k ctx
25. `glm-4.5-flash` (zai) — 131k ctx
26. `voxtral-small-2507` (mistral) — 32k ctx
27. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `inclusionai/ling-3.2-flash:free` (openrouter) — 1048k ctx
4. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
8. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
9. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
10. `google/gemma-4-31b-it` (nvidia) — 256k ctx
11. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
12. `cohere/north-mini-code:free` (openrouter) — 256k ctx
13. `glm-4.7-flash` (zai) — 200k ctx
14. `qwen/qwen3.8-27b` (groq) — 131k ctx
15. `openai/gpt-oss-20b` (groq) — 131k ctx
16. `openai/gpt-oss-120b` (groq) — 131k ctx
17. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
18. `glm-4.5-flash` (zai) — 131k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `stepfun-ai/step-5-preview` (nvidia) — 1048k ctx
3. `inclusionai/ling-3.2-flash:free` (openrouter) — 1048k ctx
4. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
5. `ministral-14b-2512` (mistral) — 262k ctx
6. `ministral-8b-2512` (mistral) — 262k ctx
7. `ministral-8b-latest` (mistral) — 262k ctx
8. `google/gemma-4-31b-it` (nvidia) — 256k ctx
9. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
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
