# Ripple App – Vercel Ready

Glass AI chat PWA. Paste your own API key (OpenRouter recommended).

## Quick Deploy on Vercel
1. Unzip and push the folder to a GitHub repo (or use Vercel CLI).
2. Import the project in Vercel (static site).
3. Deploy. No env vars needed (keys stay on device).

Or locally:
python3 -m http.server 8080

## Recommended Models (paste these in the app)
- Muse Spark Open: model = meta/muse-spark-open
- Free uncensored coding: model = cognitivecomputations/dolphin-mistral-24b-venice-edition:free
- Free coding agent: model = cohere/north-mini-code:free or poolside/laguna-s-2.1:free

Base URL for all: https://openrouter.ai/api/v1
Get a free OpenRouter key at openrouter.ai

See models.json for full list.
