# GET /accounts/{account_id}/ai/run/@cf/deepgram/nova-3-internal

**Resource:** [Workers AI Automatic Speech Recognition](../resources/Workers-AI-Automatic-Speech-Recognition.md)
**Open Websocket connection with @cf/deepgram/nova-3-internal model.**
**Operation ID:** `workers-ai-post-websocket-run-cf-deepgram-nova-3-internal`

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
