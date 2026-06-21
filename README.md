# Pipecat (pipecat-ai)

Pipecat is an open-source Python framework (created by Daily) for building realtime voice and multimodal AI agents. It orchestrates pipelines of frames through pluggable services (STT, LLM, TTS, vision) and transports (Daily WebRTC, WebSocket, SmallWebRTC, telephony). Pipecat Cloud adds a hosted platform with a REST control API for deploying agents and starting/stopping agent sessions at scale.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pipecat-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pipecat-ai/refs/heads/main/apis.yml)

## Tags

- AI
- Voice
- Multimodal
- Agents
- Realtime
- Framework

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Pipecat Framework (Python SDK)

Open-source (BSD 2-Clause) Python framework whose interface is the pipecat-ai library, not a REST API. Applications wire FrameProcessors into a Pipeline, where Frames carry audio, text, images, and control signals between pluggable AI Services (STT, LLM, TTS, vision) and client Transports.

- **Human URL:** [https://docs.pipecat.ai/overview/introduction](https://docs.pipecat.ai/overview/introduction)

#### Tags

- Framework
- Python
- SDK
- Pipelines
- Frames

#### Properties

- [Documentation](https://docs.pipecat.ai/overview/introduction)
- [API Reference](https://docs.pipecat.ai/server/introduction)
- [GitHub](https://github.com/pipecat-ai/pipecat)

### Pipecat Cloud (Agents/Sessions API)

Hosted REST control API (Bearer-token authenticated) for deploying and operating Pipecat agents on Pipecat Cloud - create/list/update/delete agents, start and stop agent sessions, manage builds, secrets, and organization properties.

- **Human URL:** [https://docs.pipecat.ai/api-reference/pipecat-cloud/rest-reference](https://docs.pipecat.ai/api-reference/pipecat-cloud/rest-reference)
- **Base URL:** `https://api.pipecat.daily.co/v1`

#### Tags

- Cloud
- Agents
- Sessions
- REST
- Deployment

#### Properties

- [Documentation](https://docs.pipecat.ai/overview/cloud)
- [API Reference](https://docs.pipecat.ai/api-reference/pipecat-cloud/rest-reference)
- [OpenAPI](openapi/pipecat-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pipecat-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pipecat-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Transports (WebRTC/WebSocket)

Realtime media transport layer of the framework. Bidirectional audio, video, and data flow over Daily WebRTC, SmallWebRTC, LiveKit, FastAPI WebSocket server, and telephony serializers (Twilio, Telnyx, Plivo, Exotel). These are SDK transport classes, not a hosted public REST/WebSocket control API.

- **Human URL:** [https://docs.pipecat.ai/server/services/supported-services](https://docs.pipecat.ai/server/services/supported-services)

#### Tags

- Transports
- WebRTC
- WebSocket
- Telephony
- Realtime

#### Properties

- [Documentation](https://docs.pipecat.ai/server/services/supported-services)
- [GitHub](https://github.com/pipecat-ai/pipecat)

## Common Properties

- [GitHub Organization](https://github.com/pipecat-ai)
- [LinkedIn](https://www.linkedin.com/company/daily-co)
- [Website](https://www.pipecat.ai)
- [Documentation](https://docs.pipecat.ai)
- [Plans](plans/pipecat-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/pipecat-ai-rate-limits.yml)
- [Fin Ops](finops/pipecat-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
