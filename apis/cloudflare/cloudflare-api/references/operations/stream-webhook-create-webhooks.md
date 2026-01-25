# PUT /accounts/{account_id}/stream/webhook

**Resource:** [Stream Webhook](../resources/Stream-Webhook.md)
**Create webhooks**
**Operation ID:** `stream-webhook-create-webhooks`

Creates a webhook notification.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_webhook_request](../schemas/stream/stream-webhook-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create webhooks response. |
| 4XX | Create webhooks response failure. |

**Success Response Schema:**

[stream_webhook_response_single](../schemas/stream/stream-webhook-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
