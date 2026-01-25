# GET /accounts/{account_id}/alerting/v3/silences/{silence_id}

**Resource:** [Notification Silences](../resources/Notification-Silences.md)
**Get Silence**
**Operation ID:** `notification-silences-get-silence`

Gets a specific silence for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |
| `silence_id` | path | aaa_silence-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Silence response |
| 4XX | Get Silence response failure |

**Success Response Schema:**

[aaa_silence_components-schemas-response_collection](../schemas/aaa/aaa-silence-components-schemas-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
