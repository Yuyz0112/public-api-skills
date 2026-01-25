# PUT /2/webhooks/{webhook_id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Validate webhook**
**Operation ID:** `validateWebhooks`

Triggers a CRC check for a given webhook.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | WebhookConfigId | Yes | The ID of the webhook to check. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[WebhookConfigPutResponse](../schemas/Webhook/WebhookConfigPutResponse.md)

## Security

- **BearerToken**
- **UserToken**
