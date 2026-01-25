# DELETE /accounts/{account_id}/alerting/v3/silences/{silence_id}

**Resource:** [Notification Silences](../resources/Notification-Silences.md)
**Delete Silence**
**Operation ID:** `notification-silences-delete-silences`

Deletes an existing silence for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |
| `silence_id` | path | aaa_silence-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Silence response |
| 4XX | Delete Silence response failure |

**Success Response Schema:**

[aaa_schemas-api-response-common](../schemas/aaa/aaa-schemas-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
