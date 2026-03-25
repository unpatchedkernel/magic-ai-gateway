# 🤖 MAGIC AI Gateway

> Self-hosted multi-model LLM gateway — powering AI across  30+ companies.

Built on [OpenClaw](https://github.com/openclaw), MAGIC AI routes queries intelligently across Claude, Gemini & GPT-4o with enterprise-grade access control, audit logging, and WhatsApp + Telegram integration.

## Architecture
```text
User (WhatsApp / Telegram / Web)
        ↓
  MAGIC AI Gateway  ←→  Auth + Rate Limiting
        ↓
  Model Router
  ├── Anthropic Claude 3.5/4
  ├── Google Gemini 2.0
  └── OpenAI GPT-4o
        ↓
  Audit Logger → Enterprise SIEM
```

## Features
- Multi-model routing with fallback
- WhatsApp & Telegram bot integration
- OAuth 2.0 enterprise authentication
- Full audit trail for compliance
- Role-based access per department

## Topics
`ai-gateway` `llm` `openai` `anthropic` `gemini` `self-hosted` `enterprise-ai` `whatsapp` `telegram`
