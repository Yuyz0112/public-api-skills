# Action

A message containing information about a single PagerDuty action.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string (uuid) | No | Uniquely identifies this outgoing webhook message; can be used for idempotency when processing the messages. |
| `triggered_at` | string (date-time) | No | The date/time when this message was was sent. |
| `webhook` | [Webhook](Webhook.md) | No |  |

