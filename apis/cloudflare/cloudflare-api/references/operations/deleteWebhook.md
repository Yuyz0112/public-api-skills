# DELETE /accounts/{account_id}/realtime/kit/{app_id}/webhooks/{webhook_id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Delete a webhook**
**Operation ID:** `deleteWebhook`

Removes a webhook for the given webhook ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `webhook_id` | path | string | Yes | ID of the webhook |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Operation successful |
| 400 | Error - malformed request |
| 401 | Invalid credentials |

**Success Response Schema:**

[realtimekit_WebhookSuccessResponse](../schemas/realtimekit/realtimekit-WebhookSuccessResponse.md)

## Security

- **api_token**
