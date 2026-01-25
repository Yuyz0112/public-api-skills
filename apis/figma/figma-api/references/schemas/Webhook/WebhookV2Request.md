# WebhookV2Request

Information regarding the most recent interactions sent to a webhook endpoint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `webhook_id` | string | Yes | The ID of the webhook the requests were sent to |
| `request_info` | [WebhookV2RequestInfo](WebhookV2RequestInfo.md) | Yes |  |
| `response_info` | [WebhookV2ResponseInfo](WebhookV2ResponseInfo.md) | Yes |  |
| `error_msg` | string,null | Yes | Error message for this request. NULL if no error occurred |

