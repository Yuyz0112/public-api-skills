# WebhookRegistrationDetails

Details of webhooks to register.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | Yes | The URL that specifies where to send the webhooks. This URL must use the same base URL as the Connect app. Only a single URL per app is allowed to be registered. |
| `webhooks` | WebhookDetails[] | Yes | A list of webhooks. |

