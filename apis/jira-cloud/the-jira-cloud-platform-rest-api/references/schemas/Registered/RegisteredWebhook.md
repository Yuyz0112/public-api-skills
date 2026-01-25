# RegisteredWebhook

ID of a registered webhook or error messages explaining why a webhook wasn't registered.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `createdWebhookId` | integer (int64) | No | The ID of the webhook. Returned if the webhook is created. |
| `errors` | string[] | No | Error messages specifying why the webhook creation failed. |

