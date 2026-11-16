# Free LLM Models — daily-verified registry

Which free API models actually work *right now*, verified daily with real free-tier keys — not copied from pricing pages.

_Last verified: 2026-11-16T23:15:40Z_

## Models by lane

Full per-lane tables are collapsible below. Statuses: **active** = answered the probe · **deprecated** = works but retirement announced · **retired** = gone per aimodelwatch · **dead/unhealthy** = probe failed (unhealthy = 3+ days) · **not-chat** = not a chat model · **rate-limited** = 429 on probe day.

<details><summary><b>groq</b> — 4/11 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `openai/gpt-oss-20b` | **active** | 147ms | ctx 131k, tools, reasoning | 2026-11-16 |
| `whisper-large-v3` | **not-chat** | — | ctx 0k | 2026-11-16 |
| `openai/gpt-oss-120b` | **active** | 265ms | ctx 131k, tools, reasoning | 2026-11-16 |
| `meta-llama/llama-prompt-guard-2-22m` | **not-chat** | — | ctx 0k | 2026-11-16 |
| `canopylabs/orpheus-v1-english` | **not-chat** | — | ctx 4k | 2026-11-16 |
| `canopylabs/orpheus-arabic-saudi` | **not-chat** | — | ctx 4k | 2026-11-16 |
| `meta-llama/llama-prompt-guard-2-86m` | **not-chat** | — | ctx 0k | 2026-11-16 |
| `allam-2-7b` | **active** | 275ms | ctx 4k | 2026-11-16 |
| `qwen/qwen3.8-27b` | **active** | 202ms | ctx 131k, tools, reasoning, vision | 2026-11-16 |
| `openai/gpt-oss-safeguard-20b` | **not-chat** | — | ctx 131k, tools, reasoning | 2026-11-16 |
| `whisper-large-v3-turbo` | **not-chat** | — | ctx 0k | 2026-11-16 |

</details>

<details><summary><b>nvidia</b> — 10/33 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `bigcode/starcoder2-15b` | **dead** | — | — | 2026-11-16 |
| `deepseek-ai/deepseek-v4.1-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-16 |
| `google/gemma-3-12b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-16 |
| `google/gemma-3-4b-it` | **dead** | — | ctx 131k, tools, vision | 2026-11-16 |
| `google/gemma-4-31b-it` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-16 |
| `meta/muse-glimmer-30b` | **active** | 6338ms | ctx 131k, tools, reasoning, vision | 2026-11-16 |
| `minimaxai/minimax-m3.1-flash` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-16 |
| `mistralai/mistral-large-4-1t-a52b` | **active** | 235ms | ctx 1000k | 2026-11-16 |
| `nvidia/ai-synthetic-video-detector` | **dead** | — | — | 2026-11-16 |
| `nvidia/cosmos-reason2-8b` | **dead** | — | ctx 131k, tools, reasoning, vision | 2026-11-16 |
| `nvidia/embed-qa-4` | **not-chat** | — | — | 2026-11-16 |
| `nvidia/ising-calibration-1.5-31b` | **active** | 13955ms | — | 2026-11-16 |
| `nvidia/llama-3.1-nemoguard-8b-topic-control` | **not-chat** | — | — | 2026-11-16 |
| `nvidia/llama-3.1-nemotron-safety-guard-8b-v3` | **not-chat** | — | ctx 128k | 2026-11-16 |
| `nvidia/llama-3.2-nemoretriever-1b-vlm-embed-v1` | **not-chat** | — | — | 2026-11-16 |
| `nvidia/llama-3.2-nv-embedqa-1b-v1` | **not-chat** | — | — | 2026-11-16 |
| `nvidia/nemotron-3-embed-1b` | **not-chat** | — | — | 2026-11-16 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` | **active** | 192ms | ctx 256k, tools, reasoning, vision | 2026-11-16 |
| `nvidia/nemotron-3-ultra-550b-a55b` | **active** | 1129ms | ctx 1000k, tools, reasoning | 2026-11-16 |
| `nvidia/nemotron-3.5-bolt-e4b` | **active** | 249ms | — | 2026-11-16 |
| `nvidia/nemotron-3.5-content-safety` | **not-chat** | — | ctx 128k, reasoning, vision | 2026-11-16 |
| `nvidia/nemotron-3.5-embed-1b` | **not-chat** | — | — | 2026-11-16 |
| `nvidia/nemotron-3.5-embed-8b` | **not-chat** | — | — | 2026-11-16 |
| `nvidia/nemotron-3.5-lightning-30b-a3b` | **active** | 135ms | ctx 262k, tools, reasoning | 2026-11-16 |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | **active** | 454ms | ctx 1048k, tools, reasoning, vision | 2026-11-16 |
| `nvidia/nv-embedqa-mistral-7b-v2` | **not-chat** | — | — | 2026-11-16 |
| `nvidia/nvclip` | **dead** | — | — | 2026-11-16 |
| `nvidia/riva-translate-4b-instruct-v2` | **active** | 254ms | — | 2026-11-16 |
| `openai/gpt-oss-20b` | **dead** | — | ctx 131k, tools, reasoning | 2026-11-16 |
| `poolside/laguna-xs-2.1` | **active** | 140ms | ctx 262k, tools, reasoning | 2026-11-16 |
| `snowflake/arctic-embed-l` | **not-chat** | — | — | 2026-11-16 |
| `stepfun-ai/step-5-preview` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-16 |
| `z-ai/glm-5.3-flash` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-16 |

</details>

<details><summary><b>mistral</b> — 10/53 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `codestral-2508` | **active** | 1090ms | ctx 256k, tools | 2026-11-16 |
| `codestral-latest` | **active** | 300ms | ctx 256k, tools | 2026-11-16 |
| `mistral-code-latest` | **rate-limited** | — | — | 2026-11-16 |
| `mistral-code-fim-latest` | **rate-limited** | — | — | 2026-11-16 |
| `labs-leanstral-1-5-1` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-16 |
| `labs-leanstral-1-5` | **dead** | — | ctx 262k, tools, reasoning, vision | 2026-11-16 |
| `ministral-14b-2512` | **active** | 345ms | ctx 262k, tools, vision | 2026-11-16 |
| `ministral-14b-latest` | **active** | 313ms | — | 2026-11-16 |
| `ministral-3b-2512` | **active** | 301ms | ctx 131k, tools, vision | 2026-11-16 |
| `ministral-3b-latest` | **active** | 1417ms | ctx 131k, tools, vision | 2026-11-16 |
| `ministral-8b-2512` | **active** | 457ms | ctx 262k, tools, vision | 2026-11-16 |
| `ministral-8b-latest` | **active** | 330ms | ctx 262k, tools, vision | 2026-11-16 |
| `mistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-16 |
| `mistral-medium` | **rate-limited** | — | ctx 131k, tools, vision | 2026-11-16 |
| `mistral-medium-3-5` | **rate-limited** | — | — | 2026-11-16 |
| `mistral-medium-3.5` | **rate-limited** | — | — | 2026-11-16 |
| `mistral-medium-3` | **rate-limited** | — | — | 2026-11-16 |
| `mistral-medium-2604` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-16 |
| `mistral-vibe-cli-latest` | **rate-limited** | — | — | 2026-11-16 |
| `mistral-vibe-cli-with-tools` | **rate-limited** | — | — | 2026-11-16 |
| `magistral-medium-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-16 |
| `mistral-small-2603` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-16 |
| `mistral-small-latest` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-16 |
| `mistral-vibe-cli-fast` | **rate-limited** | — | — | 2026-11-16 |
| `magistral-small-latest` | **rate-limited** | — | — | 2026-11-16 |
| `voxtral-small-2507` | **active** | 350ms | ctx 32k, tools | 2026-11-16 |
| `voxtral-small-latest` | **active** | 368ms | ctx 32k, tools | 2026-11-16 |
| `codestral-embed` | **not-chat** | — | ctx 8k | 2026-11-16 |
| `codestral-embed-2505` | **not-chat** | — | ctx 8k | 2026-11-16 |
| `mistral-embed-2312` | **not-chat** | — | ctx 8k | 2026-11-16 |
| `mistral-embed` | **not-chat** | — | ctx 8k | 2026-11-16 |
| `mistral-moderation-2603` | **not-chat** | — | — | 2026-11-16 |
| `mistral-ocr-2512` | **not-chat** | — | — | 2026-11-16 |
| `mistral-ocr-3-0` | **not-chat** | — | — | 2026-11-16 |
| `mistral-ocr-3` | **not-chat** | — | — | 2026-11-16 |
| `mistral-ocr-latest` | **not-chat** | — | — | 2026-11-16 |
| `mistral-ocr-4` | **not-chat** | — | — | 2026-11-16 |
| `mistral-ocr-4-1` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-2602` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-latest` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-transcribe-3` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-transcribe-3-0` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-transcribe-realtime-2602` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-realtime-2602` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-realtime-latest` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-transcribe-realtime-3` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-transcribe-realtime-3-0` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-small-transcribe-3` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-small-transcribe-3-0` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-tts-2603` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-tts-latest` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-tts-3-0` | **not-chat** | — | — | 2026-11-16 |
| `voxtral-mini-tts-3` | **not-chat** | — | — | 2026-11-16 |

</details>

<details><summary><b>zai</b> — 2/3 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-4.7-flash` | **rate-limited** | — | ctx 200k, tools, reasoning | 2026-11-16 |
| `glm-4.5-flash` | **active** | 1274ms | ctx 131k, tools, reasoning | 2026-11-16 |
| `glm-4.6v-flash` | **active** | 1244ms | ctx 128k, tools, reasoning, vision | 2026-11-16 |

</details>

<details><summary><b>ollama</b> — 0/24 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `glm-5.2` | **dead** | — | — | 2026-11-16 |
| `deepseek-v4-pro:0813` | **dead** | — | ctx 1000k | 2026-11-16 |
| `gemma4:31b` | **dead** | — | — | 2026-11-16 |
| `kimi-k2.7-code` | **dead** | — | ctx 262k | 2026-11-16 |
| `gpt-oss:20b` | **dead** | — | — | 2026-11-16 |
| `deepseek-v4.1-flash:1017` | **dead** | — | — | 2026-11-16 |
| `beam` | **dead** | — | — | 2026-11-16 |
| `glm-5.3` | **dead** | — | — | 2026-11-16 |
| `deepseek-v4.1-flash` | **dead** | — | — | 2026-11-16 |
| `kimi-k3.1-pro` | **dead** | — | ctx 1048k | 2026-11-16 |
| `minimax-m3.1-flash` | **dead** | — | — | 2026-11-16 |
| `minimax-m3` | **dead** | — | — | 2026-11-16 |
| `clef:27b` | **not-chat** | — | — | 2026-11-16 |
| `muse-spark-open` | **dead** | — | — | 2026-11-16 |
| `nemotron-3-ultra` | **dead** | — | — | 2026-11-16 |
| `glm-5.3-flash` | **dead** | — | — | 2026-11-16 |
| `mimo-v2.6-pro` | **dead** | — | — | 2026-11-16 |
| `kimi-k2.6` | **dead** | — | ctx 262k | 2026-11-16 |
| `kimi-k3` | **dead** | — | ctx 1048k | 2026-11-16 |
| `mistral-large-4` | **dead** | — | ctx 1000k | 2026-11-16 |
| `inkling-2-small` | **dead** | — | — | 2026-11-16 |
| `mimo-v2.6-flash` | **dead** | — | — | 2026-11-16 |
| `gpt-oss:120b` | **dead** | — | — | 2026-11-16 |
| `nemotron-3-super` | **dead** | — | — | 2026-11-16 |

</details>

<details><summary><b>cohere</b> — 0/1 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `command-r7b-12-2024` | **deprecated** | 211ms | ctx 128k, tools | 2026-11-16 |

</details>

<details><summary><b>openrouter</b> — 5/14 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `inclusionai/ling-3.2-flash:free` | **active** | 1201ms | ctx 1048k, tools, reasoning, vision | 2026-11-16 |
| `baidu/ernie-5.5-flash-preview:free` | **active** | 1081ms | ctx 1024k, tools, reasoning | 2026-11-16 |
| `thinkingmachines/inkling-2-small:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-16 |
| `liquid/lfm-3-1.7b:free` | **dead** | — | ctx 262k, tools, reasoning | 2026-11-16 |
| `particle-ai/particle-1:free` | **dead** | — | ctx 1048k, tools, reasoning, vision | 2026-11-16 |
| `recursive/flint-v1.0:free` | **active** | 268ms | ctx 262k, tools, reasoning | 2026-11-16 |
| `nvidia/nemotron-3.5-super-vl:free` | **dead** | — | ctx 1000k, tools, reasoning, vision | 2026-11-16 |
| `dots-studio/dots-3-note-preview:free` | **active** | 726ms | ctx 512k, tools, reasoning, vision | 2026-11-16 |
| `nvidia/nemotron-3.5-lightning:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-16 |
| `cohere/north-mini-code:free` | **active** | 185ms | ctx 256k, tools, reasoning | 2026-11-16 |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | **dead** | — | ctx 1000k, tools, reasoning | 2026-11-16 |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | **dead** | — | ctx 256k, tools, reasoning, vision | 2026-11-16 |
| `google/gemma-4-26b-a4b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-16 |
| `google/gemma-4-31b-it:free` | **rate-limited** | — | ctx 262k, tools, reasoning, vision | 2026-11-16 |

</details>

<details><summary><b>llm7</b> — 4/10 active</summary>

| Model | Status | Latency | Capabilities | Last check |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | **retired** | — | ctx 1000k | 2026-11-16 |
| `GLM-5.3-Flash` | **not-chat** | — | — | 2026-11-16 |
| `codestral-latest` | **active** | 929ms | — | 2026-11-16 |
| `gemma4:31b` | **dead** | — | — | 2026-11-16 |
| `glm-5.2` | **dead** | — | — | 2026-11-16 |
| `gpt-oss:20b` | **active** | 727ms | — | 2026-11-16 |
| `minimax-m2.7` | **active** | 1840ms | — | 2026-11-16 |
| `minimax-m3` | **dead** | — | — | 2026-11-16 |
| `mistral-Nemo-Instruct-2407` | **active** | 212ms | — | 2026-11-16 |
| `nemotron-3-nano:30b` | **not-chat** | — | — | 2026-11-16 |

</details>


## Right model for the right job (verified-active only)

**Long context** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1,048,576 tokens
2. `inclusionai/ling-3.2-flash:free` (openrouter) — 1,048,576 tokens
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1,024,000 tokens
4. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 1,000,000 tokens
5. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1,000,000 tokens
6. `dots-studio/dots-3-note-preview:free` (openrouter) — 512,000 tokens
7. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262,144 tokens
8. `poolside/laguna-xs-2.1` (nvidia) — 262,144 tokens
9. `ministral-14b-2512` (mistral) — 262,144 tokens
10. `ministral-8b-2512` (mistral) — 262,144 tokens
11. `ministral-8b-latest` (mistral) — 262,144 tokens
12. `recursive/flint-v1.0:free` (openrouter) — 262,144 tokens
13. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256,000 tokens
14. `codestral-2508` (mistral) — 256,000 tokens
15. `codestral-latest` (mistral) — 256,000 tokens
16. `cohere/north-mini-code:free` (openrouter) — 256,000 tokens
17. `openai/gpt-oss-20b` (groq) — 131,072 tokens
18. `openai/gpt-oss-120b` (groq) — 131,072 tokens
19. `qwen/qwen3.8-27b` (groq) — 131,072 tokens
20. `meta/muse-glimmer-30b` (nvidia) — 131,072 tokens
21. `ministral-3b-2512` (mistral) — 131,072 tokens
22. `ministral-3b-latest` (mistral) — 131,072 tokens
23. `glm-4.5-flash` (zai) — 131,072 tokens
24. `glm-4.6v-flash` (zai) — 128,000 tokens
25. `voxtral-small-2507` (mistral) — 32,768 tokens
26. `voxtral-small-latest` (mistral) — 32,768 tokens
27. `allam-2-7b` (groq) — 4,096 tokens

**Speed** (ranked):
1. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 135ms probe
2. `poolside/laguna-xs-2.1` (nvidia) — 140ms probe
3. `openai/gpt-oss-20b` (groq) — 147ms probe
4. `cohere/north-mini-code:free` (openrouter) — 185ms probe
5. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 192ms probe
6. `qwen/qwen3.8-27b` (groq) — 202ms probe
7. `mistral-Nemo-Instruct-2407` (llm7) — 212ms probe
8. `mistralai/mistral-large-4-1t-a52b` (nvidia) — 235ms probe
9. `nvidia/nemotron-3.5-bolt-e4b` (nvidia) — 249ms probe
10. `nvidia/riva-translate-4b-instruct-v2` (nvidia) — 254ms probe
11. `openai/gpt-oss-120b` (groq) — 265ms probe
12. `recursive/flint-v1.0:free` (openrouter) — 268ms probe
13. `allam-2-7b` (groq) — 275ms probe
14. `codestral-latest` (mistral) — 300ms probe
15. `ministral-3b-2512` (mistral) — 301ms probe
16. `ministral-14b-latest` (mistral) — 313ms probe
17. `ministral-8b-latest` (mistral) — 330ms probe
18. `ministral-14b-2512` (mistral) — 345ms probe
19. `voxtral-small-2507` (mistral) — 350ms probe
20. `voxtral-small-latest` (mistral) — 368ms probe
21. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 454ms probe
22. `ministral-8b-2512` (mistral) — 457ms probe
23. `dots-studio/dots-3-note-preview:free` (openrouter) — 726ms probe
24. `gpt-oss:20b` (llm7) — 727ms probe
25. `codestral-latest` (llm7) — 929ms probe
26. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1081ms probe
27. `codestral-2508` (mistral) — 1090ms probe
28. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1129ms probe
29. `inclusionai/ling-3.2-flash:free` (openrouter) — 1201ms probe
30. `glm-4.6v-flash` (zai) — 1244ms probe
31. `glm-4.5-flash` (zai) — 1274ms probe
32. `ministral-3b-latest` (mistral) — 1417ms probe
33. `minimax-m2.7` (llm7) — 1840ms probe
34. `meta/muse-glimmer-30b` (nvidia) — 6338ms probe
35. `nvidia/ising-calibration-1.5-31b` (nvidia) — 13955ms probe

**Tool calling** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `inclusionai/ling-3.2-flash:free` (openrouter) — 1048k ctx
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
8. `ministral-14b-2512` (mistral) — 262k ctx
9. `ministral-8b-2512` (mistral) — 262k ctx
10. `ministral-8b-latest` (mistral) — 262k ctx
11. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
12. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
13. `codestral-2508` (mistral) — 256k ctx
14. `codestral-latest` (mistral) — 256k ctx
15. `cohere/north-mini-code:free` (openrouter) — 256k ctx
16. `openai/gpt-oss-20b` (groq) — 131k ctx
17. `openai/gpt-oss-120b` (groq) — 131k ctx
18. `qwen/qwen3.8-27b` (groq) — 131k ctx
19. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
20. `ministral-3b-2512` (mistral) — 131k ctx
21. `ministral-3b-latest` (mistral) — 131k ctx
22. `glm-4.5-flash` (zai) — 131k ctx
23. `glm-4.6v-flash` (zai) — 128k ctx
24. `voxtral-small-2507` (mistral) — 32k ctx
25. `voxtral-small-latest` (mistral) — 32k ctx

**Reasoning** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `inclusionai/ling-3.2-flash:free` (openrouter) — 1048k ctx
3. `baidu/ernie-5.5-flash-preview:free` (openrouter) — 1024k ctx
4. `nvidia/nemotron-3-ultra-550b-a55b` (nvidia) — 1000k ctx
5. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
6. `nvidia/nemotron-3.5-lightning-30b-a3b` (nvidia) — 262k ctx
7. `poolside/laguna-xs-2.1` (nvidia) — 262k ctx
8. `recursive/flint-v1.0:free` (openrouter) — 262k ctx
9. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
10. `cohere/north-mini-code:free` (openrouter) — 256k ctx
11. `openai/gpt-oss-20b` (groq) — 131k ctx
12. `openai/gpt-oss-120b` (groq) — 131k ctx
13. `qwen/qwen3.8-27b` (groq) — 131k ctx
14. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
15. `glm-4.5-flash` (zai) — 131k ctx
16. `glm-4.6v-flash` (zai) — 128k ctx

**Vision (image input)** (ranked):
1. `nvidia/nemotron-3.5-super-vl-120b-a12b` (nvidia) — 1048k ctx
2. `inclusionai/ling-3.2-flash:free` (openrouter) — 1048k ctx
3. `dots-studio/dots-3-note-preview:free` (openrouter) — 512k ctx
4. `ministral-14b-2512` (mistral) — 262k ctx
5. `ministral-8b-2512` (mistral) — 262k ctx
6. `ministral-8b-latest` (mistral) — 262k ctx
7. `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning` (nvidia) — 256k ctx
8. `qwen/qwen3.8-27b` (groq) — 131k ctx
9. `meta/muse-glimmer-30b` (nvidia) — 131k ctx
10. `ministral-3b-2512` (mistral) — 131k ctx
11. `ministral-3b-latest` (mistral) — 131k ctx
12. `glm-4.6v-flash` (zai) — 128k ctx

_Not covered by any current lane: embeddings — all lanes are text chat models. These leaderboards apply when such lanes are added._


## Deprecation feed audit (shadow probes)

The vendor deprecation feed tracks first-party APIs, but aggregator lanes may still serve pinned snapshots. Retired-flagged models keep their `retired` status while a daily shadow probe records what the model actually does. Disagreements are listed here for review before the skip rule changes.

| Model | Lane | Feed says | Probe says | Disagreeing for |
|---|---|---|---|---|
| `DeepSeek-V4-Flash-0731` | llm7 | retired | active (2023ms) | 1 day(s) |


## Lane quotas (daily snapshot)

Where each lane stands on its free allowance. Quota comes from rate-limit headers captured off the probe responses (zero extra requests), except OpenRouter which needs one daily call to its key endpoint. Keys never leave the private verifier repo; only aggregate remaining counts are published here.

| Lane | Source | Requests remaining | Request limit | Reset / note |
|---|---|---|---|---|
| groq | response-headers | 999 | 1000 | resets in 1m26.4s |
| nvidia | none | — | — | no quota API; dashboard only |
| mistral | response-headers | 59 | 60 |  |
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
