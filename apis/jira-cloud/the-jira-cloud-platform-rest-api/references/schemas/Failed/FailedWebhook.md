# FailedWebhook

Details about a failed webhook.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `body` | string | No | The webhook body. |
| `failureTime` | integer (int64) | Yes | The time the webhook was added to the list of failed webhooks (that is, the time of the last failed retry). |
| `id` | string | Yes | The webhook ID, as sent in the `X-Atlassian-Webhook-Identifier` header with the webhook. |
| `url` | string | Yes | The original webhook destination. |

