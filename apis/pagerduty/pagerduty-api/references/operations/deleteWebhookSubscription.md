# DELETE /webhook_subscriptions/{id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Delete a webhook subscription**
**Operation ID:** `deleteWebhookSubscription`

Deletes a webhook subscription.

Scoped OAuth requires: `webhook_subscriptions.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The webhook subscription was deleted successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

