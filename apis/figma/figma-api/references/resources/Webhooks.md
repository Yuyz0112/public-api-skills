# Webhooks

Interact with team webhooks as a team admin.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v2/webhooks` | Get webhooks by context or plan | [View](../operations/getWebhooks.md) |
| POST | `/v2/webhooks` | Create a webhook | [View](../operations/postWebhook.md) |
| GET | `/v2/webhooks/{webhook_id}` | Get a webhook | [View](../operations/getWebhook.md) |
| PUT | `/v2/webhooks/{webhook_id}` | Update a webhook | [View](../operations/putWebhook.md) |
| DELETE | `/v2/webhooks/{webhook_id}` | Delete a webhook | [View](../operations/deleteWebhook.md) |
| GET | `/v2/teams/{team_id}/webhooks` | [Deprecated] Get team webhooks | [View](../operations/getTeamWebhooks.md) |
| GET | `/v2/webhooks/{webhook_id}/requests` | Get webhook requests | [View](../operations/getWebhookRequests.md) |
