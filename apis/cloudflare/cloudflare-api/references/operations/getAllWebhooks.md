# GET /accounts/{account_id}/realtime/kit/{app_id}/webhooks

**Resource:** [Webhooks](../resources/Webhooks.md)
**Fetch all webhooks details**
**Operation ID:** `getAllWebhooks`

Returns details of all webhooks for an App.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Operation successful |
| 401 | Invalid credentials |

**Success Response Schema:**

[realtimekit_WebhooksListSuccessResponse](../schemas/realtimekit/realtimekit-WebhooksListSuccessResponse.md)

## Security

- **api_token**
