# DELETE /v2/webhooks/{webhook_id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Delete a webhook**
**Operation ID:** `deleteWebhook`

Deletes the specified webhook. This operation cannot be reversed.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | string | Yes | ID of webhook to delete |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: webhooks:write
