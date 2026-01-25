# GET /accounts/{account_id}/ai/run/@cf/deepgram/aura-1-internal

**Resource:** [Workers AI Text To Speech](../resources/Workers-AI-Text-To-Speech.md)
**Open Websocket connection with @cf/deepgram/aura-1-internal model.**
**Operation ID:** `workers-ai-post-websocket-run-cf-deepgram-aura-1-internal`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 101 | Returns a websocket connection |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
