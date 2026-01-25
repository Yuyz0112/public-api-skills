# GET /2/webhooks

**Resource:** [Webhooks](../resources/Webhooks.md)
**Get webhook**
**Operation ID:** `getWebhooks`

Get a list of webhook configs associated with a client app.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2WebhooksResponse](../schemas/Get/Get2WebhooksResponse.md)

## Security

- **BearerToken**
