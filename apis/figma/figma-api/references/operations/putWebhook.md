# PUT /v2/webhooks/{webhook_id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Update a webhook**
**Operation ID:** `putWebhook`

Update a webhook by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | string | Yes | ID of webhook to update |

## Request Body

The webhook to update.

**Required:** Yes

**Content Types:** `application/json`

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
