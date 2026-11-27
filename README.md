# LLM API Pricing & Context Tracker 💰📊

![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--11--27T18%3A41%3A06Z-brightgreen?style=flat-square)
![Tracked Models](https://img.shields.io/badge/Tracked%20Models-4795-blue?style=flat-square)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

**Daily auto-updated comparison of LLM API token prices (Input / Output USD per 1M tokens) and context windows.**

🌐 **Interactive Pricing Dashboard:** [https://oneforallhub.github.io/llm-pricing-tracker/](https://oneforallhub.github.io/llm-pricing-tracker/)
📦 **JSON:** [`data/llm_pricing.json`](https://raw.githubusercontent.com/OneForAllHub/llm-pricing-tracker/main/data/llm_pricing.json) · **CSV:** [`data/llm_pricing.csv`](https://raw.githubusercontent.com/OneForAllHub/llm-pricing-tracker/main/data/llm_pricing.csv)

## Major Provider Models (USD per 1M Tokens)

| Model ID | Provider | Input / 1M | Output / 1M | Context Window | Source |
| --- | --- | ---: | ---: | ---: | --- |
| `mistralai/mistral-nemo` | mistralai | $0.03 | $0.03 | 131,072 | OpenRouter |
| `meta-llama/llama-3.1-8b-instruct` | meta-llama | $0.05 | $0.08 | 131,072 | OpenRouter |
| `mistralai/mistral-small-24b-instruct-2501` | mistralai | $0.05 | $0.08 | 32,768 | OpenRouter |
| `openai/gpt-oss-20b:batch` | openai | $0.02 | $0.11 | 131,072 | OpenRouter |
| `mistralai/ministral-8b-2512:batch` | mistralai | $0.07 | $0.07 | 262,144 | OpenRouter |
| `google/gemma-3-4b-it` | google | $0.05 | $0.10 | 131,072 | OpenRouter |
| `qwen/qwen3.7-flash` | qwen | $0.03 | $0.13 | 1,000,000 | OpenRouter |
| `openai/gpt-oss-20b` | openai | $0.03 | $0.13 | 131,072 | OpenRouter |
| `openai/gpt-oss-120b:batch` | openai | $0.03 | $0.14 | 131,072 | OpenRouter |
| `deepseek/deepseek-v4.1-flash-1017:batch` | deepseek | $0.04 | $0.15 | 1,048,576 | OpenRouter |
| `deepseek/deepseek-v4-flash-0731:batch` | deepseek | $0.05 | $0.14 | 1,048,576 | OpenRouter |
| `deepseek/deepseek-v4.1-flash:batch` | deepseek | $0.05 | $0.15 | 1,048,576 | OpenRouter |
| `google/gemma-3-12b-it` | google | $0.05 | $0.15 | 131,072 | OpenRouter |
| `mistralai/ministral-3b-2512` | mistralai | $0.10 | $0.10 | 131,072 | OpenRouter |
| `openai/gpt-5-nano:batch` | openai | $0.03 | $0.20 | 400,000 | OpenRouter |
| `google/gemma-3-27b-it` | google | $0.08 | $0.16 | 131,072 | OpenRouter |
| `openai/gpt-4.1-nano:batch` | openai | $0.05 | $0.20 | 1,047,576 | OpenRouter |
| `deepseek/deepseek-v4.1-flash` | deepseek | $0.05 | $0.20 | 1,048,576 | OpenRouter |
| `deepseek/deepseek-v4-flash` | deepseek | $0.09 | $0.18 | 1,048,576 | OpenRouter |
| `mistralai/mistral-small-3.2-24b-instruct` | mistralai | $0.07 | $0.20 | 256,000 | OpenRouter |
| `openai/gpt-6-luna-pro:batch` | openai | $0.05 | $0.25 | 1,050,000 | OpenRouter |
| `openai/gpt-6-luna:batch` | openai | $0.05 | $0.25 | 1,050,000 | OpenRouter |
| `anthropic/claude-haiku-5.5:batch` | anthropic | $0.05 | $0.25 | 1,000,000 | OpenRouter |
| `mistralai/ministral-8b-2512` | mistralai | $0.15 | $0.15 | 262,144 | OpenRouter |
| `openai/gpt-oss-120b` | openai | $0.05 | $0.25 | 131,072 | OpenRouter |
| `qwen/qwen3.5-flash-02-23` | qwen | $0.07 | $0.26 | 1,000,000 | OpenRouter |
| `deepseek/deepseek-v4-flash-0731` | deepseek | $0.05 | $0.30 | 1,048,576 | OpenRouter |
| `qwen/qwen3.5-9b` | qwen | $0.10 | $0.25 | 262,144 | OpenRouter |
| `qwen/qwen3-coder-30b-a3b-instruct` | qwen | $0.07 | $0.28 | 262,144 | OpenRouter |
| `meta-llama/llama-guard-4-12b` | meta-llama | $0.18 | $0.18 | 163,840 | OpenRouter |
| `qwen/qwen3-14b` | qwen | $0.12 | $0.24 | 40,960 | OpenRouter |
| `qwen/qwen3-32b` | qwen | $0.08 | $0.28 | 131,072 | OpenRouter |
| `mistralai/mistral-small-2603:batch` | mistralai | $0.07 | $0.30 | 262,144 | OpenRouter |
| `openai/gpt-oss-safeguard-20b` | openai | $0.07 | $0.30 | 131,072 | OpenRouter |
| `openai/gpt-4o-mini:batch` | openai | $0.07 | $0.30 | 128,000 | OpenRouter |
| `meta-llama/llama-3.2-3b-instruct` | meta-llama | $0.05 | $0.33 | 131,072 | OpenRouter |
| `google/gemma-4-26b-a4b-it` | google | $0.09 | $0.30 | 262,144 | OpenRouter |
| `meta-llama/llama-4-scout` | meta-llama | $0.10 | $0.30 | 1,310,720 | OpenRouter |
| `mistralai/ministral-14b-2512` | mistralai | $0.20 | $0.20 | 262,144 | OpenRouter |
| `qwen/qwen3-30b-a3b-instruct-2507` | qwen | $0.10 | $0.30 | 262,144 | OpenRouter |

## Cheapest Paid Models (USD per 1M Tokens)

| Model ID | Provider | Input / 1M | Output / 1M | Context Window | Source |
| --- | --- | ---: | ---: | ---: | --- |
| `fireworks_ai/accounts/fireworks/models/flux-1-dev…` | fireworks_ai | $0.0010 | $0.0010 | 4,096 | LiteLLM |
| `fireworks-ai-embedding-up-to-150m` | fireworks_ai-embe… | $0.0080 | $0.00 | 0 | LiteLLM |
| `fireworks-ai-embedding-150m-to-350m` | fireworks_ai-embe… | $0.02 | $0.00 | 0 | LiteLLM |
| `empiriolabs/aplomb-1` | empiriolabs | $0.02 | $0.00 | 1,000,000 | LiteLLM |
| `vercel_ai_gateway/amazon/titan-embed-text-v2` | vercel_ai_gateway | $0.02 | $0.00 | 0 | LiteLLM |
| `scaledown/extract` | scaledown | $0.04 | $0.00 | 1,000,000 | OpenRouter |
| `scaledown/summarize` | scaledown | $0.04 | $0.00 | 1,000,000 | OpenRouter |
| `deepinfra/meta-llama/Llama-3.2-3B-Instruct` | deepinfra | $0.02 | $0.02 | 131,072 | LiteLLM |
| `lambda_ai/llama3.2-11b-vision-instruct` | lambda_ai | $0.01 | $0.03 | 131,072 | LiteLLM |
| `lambda_ai/llama3.2-3b-instruct` | lambda_ai | $0.01 | $0.03 | 131,072 | LiteLLM |
| `novita/meta-llama/llama-3.2-1b-instruct` | novita | $0.02 | $0.02 | 131,000 | LiteLLM |
| `nebius/Qwen/Qwen2.5-Coder-7B` | nebius | $0.01 | $0.03 | 32,768 | LiteLLM |
| `together_ai/Qwen/Qwen2-1.5B-Instruct` | together_ai | $0.02 | $0.02 | 32,768 | LiteLLM |
| `novita/paddlepaddle/paddleocr-vl` | novita | $0.02 | $0.02 | 16,384 | LiteLLM |
| `nscale/Qwen/Qwen2.5-Coder-3B-Instruct` | nscale | $0.01 | $0.03 | 0 | LiteLLM |
| `nscale/Qwen/Qwen2.5-Coder-7B-Instruct` | nscale | $0.01 | $0.03 | 0 | LiteLLM |
| `together_ai/together/Tev1-4B-experimental` | together_ai | $0.04 | $0.00 | 32,768 | LiteLLM |
| `upstage/solar-mini-4-5` | upstage | $0.01 | $0.04 | 524,288 | OpenRouter |
| `nscale/deepseek-ai/DeepSeek-R1-Distill-Llama-8B` | nscale | $0.03 | $0.03 | 0 | LiteLLM |
| `scaledown/classify` | scaledown | $0.05 | $0.00 | 0 | LiteLLM |
| `scaledown/compress` | scaledown | $0.05 | $0.00 | 0 | LiteLLM |
| `scaledown/decisions` | scaledown | $0.05 | $0.00 | 0 | LiteLLM |
| `mistralai/mistral-nemo` | mistralai | $0.03 | $0.03 | 131,072 | OpenRouter |
| `deepinfra/mistralai/Mistral-Nemo-Instruct-2407` | deepinfra | $0.03 | $0.03 | 131,072 | LiteLLM |
| `inclusionai/ling-3.0-tiny` | inclusionai | $0.01 | $0.04 | 262,144 | OpenRouter |
| `deepinfra/meta-llama/Meta-Llama-3.1-8B-Instruct-T…` | deepinfra | $0.02 | $0.04 | 131,072 | LiteLLM |
| `novita/qwen/qwen3-4b-fp8` | novita | $0.03 | $0.03 | 128,000 | LiteLLM |
| `novita/deepseek/deepseek-ocr` | novita | $0.03 | $0.03 | 8,192 | LiteLLM |
| `novita/deepseek/deepseek-ocr-2` | novita | $0.03 | $0.03 | 8,192 | LiteLLM |
| `groq/meta-llama/llama-prompt-guard-2-22m` | groq | $0.03 | $0.03 | 512 | LiteLLM |

## Dedicated Topic & SEO Pages

- [OpenAI Pricing](https://oneforallhub.github.io/llm-pricing-tracker/pages/openai-pricing.html)
- [Claude Pricing](https://oneforallhub.github.io/llm-pricing-tracker/pages/anthropic-pricing.html)
- [Gemini Pricing](https://oneforallhub.github.io/llm-pricing-tracker/pages/google-pricing.html)
- [DeepSeek Pricing](https://oneforallhub.github.io/llm-pricing-tracker/pages/deepseek-pricing.html)
- [Llama Pricing](https://oneforallhub.github.io/llm-pricing-tracker/pages/meta-llama-pricing.html)
- [Qwen Pricing](https://oneforallhub.github.io/llm-pricing-tracker/pages/qwen-pricing.html)
- [Cheapest Paid](https://oneforallhub.github.io/llm-pricing-tracker/pages/cheapest-llm-apis.html)

## More Live Trackers & Analytics by OneForAllHub

- 🌐 [**All Trackers Hub**](https://oneforallhub.github.io/OneForAllHub/) · 📊 [**Live Traffic Analytics Panel**](https://oneforallhub.github.io/OneForAllHub/panel.html) · 👤 [**GitHub Profile**](https://github.com/OneForAllHub)

- [Free LLM APIs Live](https://github.com/OneForAllHub/free-llm-apis-live) ([Live Dashboard](https://oneforallhub.github.io/free-llm-apis-live/)) — Live verified free AI & LLM API models
- [Trending AI & MCP Radar](https://github.com/OneForAllHub/trending-ai-mcp-radar) ([Live Dashboard](https://oneforallhub.github.io/trending-ai-mcp-radar/)) — Daily fastest-growing AI Agents & MCP servers
- [Daily Remote Tech Jobs](https://github.com/OneForAllHub/daily-remote-tech-jobs) ([Live Dashboard](https://oneforallhub.github.io/daily-remote-tech-jobs/)) — Auto-updated remote developer & AI jobs
- [Verified Public APIs](https://github.com/OneForAllHub/verified-public-apis) ([Live Dashboard](https://oneforallhub.github.io/verified-public-apis/)) — Uptime-checked directory of free public APIs
- [Daily CVE Security Feed](https://github.com/OneForAllHub/daily-cve-security-feed) ([Live Dashboard](https://oneforallhub.github.io/daily-cve-security-feed/)) — CISA KEV & critical GitHub security advisories
- [Free For Devs Live](https://github.com/OneForAllHub/free-for-devs-live) ([Live Dashboard](https://oneforallhub.github.io/free-for-devs-live/)) — Status-checked free cloud, DB & dev tiers
- [Free Games Radar](https://github.com/OneForAllHub/free-games-radar) ([Live Dashboard](https://oneforallhub.github.io/free-games-radar/)) — Temporarily free PC games tracker & Telegram bot

