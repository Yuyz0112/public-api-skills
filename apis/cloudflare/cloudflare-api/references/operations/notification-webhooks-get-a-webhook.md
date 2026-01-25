# GET /accounts/{account_id}/alerting/v3/destinations/webhooks/{webhook_id}

**Resource:** [Notification webhooks](../resources/Notification-webhooks.md)
**Get a webhook**
**Operation ID:** `notification-webhooks-get-a-webhook`

Get details for a single webhooks destination.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |
| `webhook_id` | path | aaa_webhook-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a webhook response |
| 4XX | Get a webhook response failure |

**Success Response Schema:**

[aaa_schemas-single_response](../schemas/aaa/aaa-schemas-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
