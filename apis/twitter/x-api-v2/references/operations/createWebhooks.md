# POST /2/webhooks

**Resource:** [Webhooks](../resources/Webhooks.md)
**Create webhook**
**Operation ID:** `createWebhooks`

Creates a new webhook configuration.

## Request Body

**Content Types:** `application/json`

**Schema:** [WebhookConfigCreateRequest](../schemas/Webhook/WebhookConfigCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[WebhookConfigCreateResponse](../schemas/Webhook/WebhookConfigCreateResponse.md)

## Security

- **BearerToken**
- **UserToken**
