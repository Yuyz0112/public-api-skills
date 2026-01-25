# GET /accounts/{account_id}/alerting/v3/available_alerts

**Resource:** [Notification Alert Types](../resources/Notification-Alert-Types.md)
**Get Alert Types**
**Operation ID:** `notification-alert-types-get-alert-types`

Gets a list of all alert types for which an account is eligible.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Alert Types response |
| 4XX | Get Alert Types response failure |

**Success Response Schema:**

[aaa_alerts-response_collection](../schemas/aaa/aaa-alerts-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
