# DELETE /accounts/{account_id}/alerting/v3/destinations/webhooks/{webhook_id}

**Resource:** [Notification webhooks](../resources/Notification-webhooks.md)
**Delete a webhook**
**Operation ID:** `notification-webhooks-delete-a-webhook`

Delete a configured webhook destination.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | aaa_webhook-id | Yes |  |
| `account_id` | path | aaa_account-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a webhook response |
| 4XX | Delete a webhook response failure |

**Success Response Schema:**

[aaa_schemas-api-response-common](../schemas/aaa/aaa-schemas-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
