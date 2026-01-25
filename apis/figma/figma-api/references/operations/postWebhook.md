# POST /v2/webhooks

**Resource:** [Webhooks](../resources/Webhooks.md)
**Create a webhook**
**Operation ID:** `postWebhook`

Create a new webhook which will call the specified endpoint when the event triggers. By default, this webhook will automatically send a PING event to the endpoint when it is created. If this behavior is not desired, you can create the webhook and set the status to PAUSED and reactivate it later.

## Request Body

The webhook to create.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: webhooks:write
