# GET /2/tweets/search/webhooks

**Resource:** [Webhooks](../resources/Webhooks.md)
**Get stream links**
**Operation ID:** `getWebhooksStreamLinks`

Get a list of webhook links associated with a filtered stream ruleset.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[WebhookLinksGetResponse](../schemas/Webhook/WebhookLinksGetResponse.md)

## Security

- **BearerToken**
