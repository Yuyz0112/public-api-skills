# webhooks

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/webhooks/{webhook_id}` |  | [View](../operations/get-webhook.md) |
| DELETE | `/webhooks/{webhook_id}` |  | [View](../operations/delete-webhook.md) |
| PATCH | `/webhooks/{webhook_id}` |  | [View](../operations/update-webhook.md) |
| GET | `/webhooks/{webhook_id}/{webhook_token}` |  | [View](../operations/get-webhook-by-token.md) |
| POST | `/webhooks/{webhook_id}/{webhook_token}` |  | [View](../operations/execute-webhook.md) |
| DELETE | `/webhooks/{webhook_id}/{webhook_token}` |  | [View](../operations/delete-webhook-by-token.md) |
| PATCH | `/webhooks/{webhook_id}/{webhook_token}` |  | [View](../operations/update-webhook-by-token.md) |
| POST | `/webhooks/{webhook_id}/{webhook_token}/github` |  | [View](../operations/execute-github-compatible-webhook.md) |
| GET | `/webhooks/{webhook_id}/{webhook_token}/messages/@original` |  | [View](../operations/get-original-webhook-message.md) |
| DELETE | `/webhooks/{webhook_id}/{webhook_token}/messages/@original` |  | [View](../operations/delete-original-webhook-message.md) |
| PATCH | `/webhooks/{webhook_id}/{webhook_token}/messages/@original` |  | [View](../operations/update-original-webhook-message.md) |
| GET | `/webhooks/{webhook_id}/{webhook_token}/messages/{message_id}` |  | [View](../operations/get-webhook-message.md) |
| DELETE | `/webhooks/{webhook_id}/{webhook_token}/messages/{message_id}` |  | [View](../operations/delete-webhook-message.md) |
| PATCH | `/webhooks/{webhook_id}/{webhook_token}/messages/{message_id}` |  | [View](../operations/update-webhook-message.md) |
| POST | `/webhooks/{webhook_id}/{webhook_token}/slack` |  | [View](../operations/execute-slack-compatible-webhook.md) |
