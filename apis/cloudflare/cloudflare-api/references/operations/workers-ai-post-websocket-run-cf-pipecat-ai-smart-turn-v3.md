# GET /accounts/{account_id}/ai/run/@cf/pipecat-ai/smart-turn-v3

**Resource:** [Workers AI Dumb Pipe](../resources/Workers-AI-Dumb-Pipe.md)
**Open Websocket connection with @cf/pipecat-ai/smart-turn-v3 model.**
**Operation ID:** `workers-ai-post-websocket-run-cf-pipecat-ai-smart-turn-v3`

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
