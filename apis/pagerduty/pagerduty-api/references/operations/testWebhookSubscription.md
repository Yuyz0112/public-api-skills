# POST /webhook_subscriptions/{id}/ping

**Resource:** [Webhooks](../resources/Webhooks.md)
**Test a webhook subscription**
**Operation ID:** `testWebhookSubscription`

Test a webhook subscription.

Fires a test event against the webhook subscription.  If properly configured,
this will deliver the `pagey.ping` webhook event to the destination.

Scoped OAuth requires: `webhook_subscriptions.write`


## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

