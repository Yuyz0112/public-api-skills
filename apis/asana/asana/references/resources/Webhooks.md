# Webhooks

Webhooks allow you to subscribe to notifications about events that occur on Asana resources (e.g., tasks, projects, stories, etc.).

For a more detailed explanation of webhooks see the [overview of webhooks](/docs/webhooks-guide).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/webhooks` | Get multiple webhooks | [View](../operations/getWebhooks.md) |
| POST | `/webhooks` | Establish a webhook | [View](../operations/createWebhook.md) |
| GET | `/webhooks/{webhook_gid}` | Get a webhook | [View](../operations/getWebhook.md) |
| PUT | `/webhooks/{webhook_gid}` | Update a webhook | [View](../operations/updateWebhook.md) |
| DELETE | `/webhooks/{webhook_gid}` | Delete a webhook | [View](../operations/deleteWebhook.md) |
