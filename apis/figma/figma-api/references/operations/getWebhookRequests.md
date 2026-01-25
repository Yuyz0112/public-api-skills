# GET /v2/webhooks/{webhook_id}/requests

**Resource:** [Webhooks](../resources/Webhooks.md)
**Get webhook requests**
**Operation ID:** `getWebhookRequests`

Returns all webhook requests sent within the last week. Useful for debugging.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | string | Yes | The id of the webhook subscription you want to see events from |

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
- **OAuth2**: webhooks:read, files:read
