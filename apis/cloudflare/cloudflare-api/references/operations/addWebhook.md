# POST /accounts/{account_id}/realtime/kit/{app_id}/webhooks

**Resource:** [Webhooks](../resources/Webhooks.md)
**Add a webhook**
**Operation ID:** `addWebhook`

Adds a new webhook to an App.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [realtimekit_WebhookRequest](../schemas/realtimekit/realtimekit-WebhookRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Webhook registered successfully |
| 400 | Error - malformed request |
| 401 | Invalid credentials |

**Success Response Schema:**

[realtimekit_WebhookSuccessResponse](../schemas/realtimekit/realtimekit-WebhookSuccessResponse.md)

## Security

- **api_token**
