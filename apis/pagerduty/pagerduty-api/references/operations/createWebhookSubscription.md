# POST /webhook_subscriptions

**Resource:** [Webhooks](../resources/Webhooks.md)
**Create a webhook subscription**
**Operation ID:** `createWebhookSubscription`

Creates a new webhook subscription.

For more information on webhook subscriptions and how they are used to configure v3 webhooks
see the [Webhooks v3 Developer Documentation](https://developer.pagerduty.com/docs/webhooks/v3-overview/).

Scoped OAuth requires: `webhook_subscriptions.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The webhook subscription that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

