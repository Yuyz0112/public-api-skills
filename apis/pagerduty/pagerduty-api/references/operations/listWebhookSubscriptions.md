# GET /webhook_subscriptions

**Resource:** [Webhooks](../resources/Webhooks.md)
**List webhook subscriptions**
**Operation ID:** `listWebhookSubscriptions`

List existing webhook subscriptions.

The `filter_type` and `filter_id` query parameters may be used to only show subscriptions
for a particular _service_ or _team_.

For more information on webhook subscriptions and how they are used to configure v3 webhooks
see the [Webhooks v3 Developer Documentation](https://developer.pagerduty.com/docs/webhooks/v3-overview/).

Scoped OAuth requires: `webhook_subscriptions.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A set of webhook subscriptions matching the request. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

