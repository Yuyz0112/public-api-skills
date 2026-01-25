# Webhook

Information about the configured webhook.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `endpoint_url` | string (url) | No | The url endpoint the webhook payload is sent to. |
| `name` | string | No | The name of the webhook. |
| `webhook_object` | [WebhookObject](WebhookObject.md) | No |  |
| `config` | object | No | The object that contains webhook configuration values depending on the webhook type specification. |
| `outbound_integration` | [OutboundIntegrationReference](OutboundIntegrationReference.md) | No |  |

