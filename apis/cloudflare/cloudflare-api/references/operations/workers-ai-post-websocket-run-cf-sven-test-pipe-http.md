# GET /accounts/{account_id}/ai/run/@cf/sven/test-pipe-http

**Resource:** [Workers AI Text To Image](../resources/Workers-AI-Text-To-Image.md)
**Open Websocket connection with @cf/sven/test-pipe-http model.**
**Operation ID:** `workers-ai-post-websocket-run-cf-sven-test-pipe-http`

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
