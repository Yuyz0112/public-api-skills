# GET /accounts/{account_id}/stream/webhook

**Resource:** [Stream Webhook](../resources/Stream-Webhook.md)
**View webhooks**
**Operation ID:** `stream-webhook-view-webhooks`

Retrieves a list of webhooks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | View webhooks response. |
| 4XX | View webhooks response failure. |

**Success Response Schema:**

[stream_webhook_response_single](../schemas/stream/stream-webhook-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
