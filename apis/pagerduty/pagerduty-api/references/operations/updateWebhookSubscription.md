# PUT /webhook_subscriptions/{id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Update a webhook subscription**
**Operation ID:** `updateWebhookSubscription`

Updates an existing webhook subscription.

Only the fields being updated need to be included on the request.  This operation does not
support updating the `delivery_method` of the webhook subscription.

Scoped OAuth requires: `webhook_subscriptions.write`


## Request Body

**Content Types:** `application/json`

**Schema:** [WebhookSubscriptionUpdate](../schemas/Webhook/WebhookSubscriptionUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The updated webhook subscription. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

