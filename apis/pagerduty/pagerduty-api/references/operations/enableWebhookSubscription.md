# POST /webhook_subscriptions/{id}/enable

**Resource:** [Webhooks](../resources/Webhooks.md)
**Enable a webhook subscription**
**Operation ID:** `enableWebhookSubscription`

Enable a webhook subscription that is temporarily disabled. (This API does not require a request body.)

Webhook subscriptions can become temporarily disabled when the subscription's delivery method is repeatedly rejected by the server.

Scoped OAuth requires: `webhook_subscriptions.write`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The webhook subscription that was successfully enabled. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

