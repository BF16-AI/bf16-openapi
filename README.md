# bf16.ai OpenAPI Specification

Machine-readable [OpenAPI 3.0.3](openapi.yaml) specification and [APIs.json](apis.json) discovery manifest for the [bf16.ai](https://bf16.ai) LLM Inference API (`https://api.bf16.ai/v1`).

## Covered Endpoints

- `GET /v1/models` — Public live model & per-token pricing catalog (also usable with a Bearer token for zero-cost key verification)
- `POST /v1/chat/completions` — OpenAI Chat Completions compatible endpoint (streaming, tool calling, vision, structured outputs, reasoning effort)
- `POST /v1/responses` — OpenAI Responses API compatible endpoint (Codex CLI & agentic loops)
- `POST /v1/messages` — Native Anthropic Messages API compatible endpoint (Claude Code & Anthropic SDKs)

## Import into Tools

- **OpenAPI YAML URL**: `https://raw.githubusercontent.com/BF16-AI/bf16-openapi/main/openapi.yaml`
- **Postman / Insomnia / Bruno / Apidog**: Import the raw YAML URL above directly to generate a ready-to-run collection.
- **API Docs**: https://bf16.ai/docs
- **Pricing**: https://bf16.ai/pricing
- **Live Status**: https://bf16.ai/status
