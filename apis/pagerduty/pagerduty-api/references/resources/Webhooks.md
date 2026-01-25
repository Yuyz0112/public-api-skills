# Webhooks

A webhook is a way to receive events that occur on the PagerDuty platform via an HTTP POST request.
V3 webhooks are set up by creating a webhook subscription.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/webhook_subscriptions` | List webhook subscriptions | [View](../operations/listWebhookSubscriptions.md) |
| POST | `/webhook_subscriptions` | Create a webhook subscription | [View](../operations/createWebhookSubscription.md) |
| GET | `/webhook_subscriptions/{id}` | Get a webhook subscription | [View](../operations/getWebhookSubscription.md) |
| PUT | `/webhook_subscriptions/{id}` | Update a webhook subscription | [View](../operations/updateWebhookSubscription.md) |
| DELETE | `/webhook_subscriptions/{id}` | Delete a webhook subscription | [View](../operations/deleteWebhookSubscription.md) |
| POST | `/webhook_subscriptions/{id}/enable` | Enable a webhook subscription | [View](../operations/enableWebhookSubscription.md) |
| POST | `/webhook_subscriptions/{id}/ping` | Test a webhook subscription | [View](../operations/testWebhookSubscription.md) |
| GET | `/webhook_subscriptions/oauth_clients` | List OAuth clients | [View](../operations/listOauthClients.md) |
| POST | `/webhook_subscriptions/oauth_clients` | Create an OAuth client | [View](../operations/createOauthClient.md) |
| GET | `/webhook_subscriptions/oauth_clients/{id}` | Get an OAuth client | [View](../operations/getOauthClient.md) |
| PUT | `/webhook_subscriptions/oauth_clients/{id}` | Update an OAuth client | [View](../operations/updateOauthClient.md) |
| DELETE | `/webhook_subscriptions/oauth_clients/{id}` | Delete an OAuth client | [View](../operations/deleteOauthClient.md) |
