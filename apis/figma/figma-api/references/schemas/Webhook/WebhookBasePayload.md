# WebhookBasePayload

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `passcode` | string | Yes | The passcode specified when the webhook was created, should match what was initially provided |
| `timestamp` | string (date-time) | Yes | UTC ISO 8601 timestamp of when the event was triggered. |
| `webhook_id` | string | Yes | The id of the webhook that caused the callback |

