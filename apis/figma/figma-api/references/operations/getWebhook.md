# GET /v2/webhooks/{webhook_id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Get a webhook**
**Operation ID:** `getWebhook`

Get a webhook by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | string | Yes | ID of webhook to get |

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
