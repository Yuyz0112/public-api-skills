# WebhookV2RequestInfo

Information regarding the request sent to a webhook endpoint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The ID of the webhook |
| `endpoint` | string | Yes | The actual endpoint the request was sent to |
| `payload` | object | Yes | The contents of the request that was sent to the endpoint |
| `sent_at` | string (date-time) | Yes | UTC ISO 8601 timestamp of when the request was sent |

