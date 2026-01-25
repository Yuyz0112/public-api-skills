# DELETE /2/webhooks/{webhook_id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Delete webhook**
**Operation ID:** `deleteWebhooks`

Deletes an existing webhook configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | WebhookConfigId | Yes | The ID of the webhook to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[WebhookConfigDeleteResponse](../schemas/Webhook/WebhookConfigDeleteResponse.md)

## Security

- **BearerToken**
- **UserToken**
