# Maxat Shaimardinov

AI Engineer. I build LLM agents for finance and tax products, with routing, RAG and structured outputs, and I test them like a QA engineer: deterministic checks, tests that run without a live LLM, CI.

Based in Astana, Kazakhstan. Open to remote and international roles. Stack: TypeScript/Node.js, Python, Go, React, PostgreSQL, Docker.

## Experience

- **Sber-Invest.kz** (Apr 2026 – now): AI agents for AI-Office, a virtual office for tax and investment services: LLM routing between agents, a knowledge base with hybrid search and RAG, prompt test sessions, Telegram and amoCRM integrations, and a QC bot that checks declarations before filing.
- **iKapitalist** (Nov 2025 – Apr 2026): an agent that turns Kazakh bank-statement PDFs into revenue analysis for investment screening: Python parser, rule-based heuristics plus an OpenAI Agents SDK classifier, React/Express app on Render. (Private repos.)
- **Underdot** (Sep 2026 – now): independent developer: [underdot.net](https://underdot.net) web apps and AI bot packages for business.

## Selected projects

### AI and LLM

- **[meta-targeting-copilot](https://github.com/mshaim001-hue/meta-targeting-copilot)**: Go + React app where a chain of LLM agents turns an ad brief into a Meta Ads targeting strategy. A deterministic resolver checks every interest against the Meta Graph API, and Go tests make sure hallucinated IDs never reach the result.
- **[voice-manager](https://github.com/mshaim001-hue/voice-manager)**: fully offline meeting assistant: Faster-Whisper transcription, speaker diarization, a local LLM (Ollama) that writes a structured JSON protocol, and a BM25 RAG chat over the meeting. 25 pytest tests run without a live LLM.
- **[lexsiai-hackaton](https://github.com/mshaim001-hue/lexsiai-hackaton)**: hackathon project on reliable tool calling: LoRA fine-tuning of Tiny Aya Global for a refund agent, with a paired evaluation on held-out requests (27/40 → 28/40 full success, 0 invalid calls).
- **[Halyk_AI_Challenge_2026_I-mAxe](https://github.com/mshaim001-hue/Halyk_AI_Challenge_2026_I-mAxe)**: team hackathon (3 people): an agent that checks financial covenants from PDFs and a ledger. The LLM reads contracts, code computes the numbers. I built the pipeline and integration. 31 pytest tests.

### Testing

- **[qa-playwright-api-suite](https://github.com/mshaim001-hue/qa-playwright-api-suite)**: 31 Playwright tests in TypeScript (UI on Swag Labs, API on Restful-Booker) with page objects, Zod contract checks, GitHub Actions and a [live Allure report](https://mshaim001-hue.github.io/qa-playwright-api-suite/).

### Full-stack

- **[html-to-txt](https://github.com/mshaim001-hue/html-to-txt)**: Go (Gin) API + Next.js app that converts Telegram HTML chat exports into plain text.
- **[game_for_digital_bridge](https://github.com/mshaim001-hue/game_for_digital_bridge)**: TypeScript/Phaser PWA. [Live demo](https://game-for-digital-bridge.vercel.app).

## Education

- Tomorrow School (Astana Hub): completed the Go, JavaScript and Rust branches.
- Superteam Kazakhstan: Solana for Developers, Level 1 and Level 2. Certificates pending.

## Contact

- LinkedIn: [linkedin.com/in/max-underdot](https://www.linkedin.com/in/max-underdot)
- Telegram: [@underdot_dev](https://t.me/underdot_dev)
