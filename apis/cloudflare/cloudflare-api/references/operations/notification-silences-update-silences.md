# PUT /accounts/{account_id}/alerting/v3/silences

**Resource:** [Notification Silences](../resources/Notification-Silences.md)
**Update Silences**
**Operation ID:** `notification-silences-update-silences`

Updates existing silences for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [aaa_silence_update_request](../schemas/aaa/aaa-silence-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Silences response |
| 4XX | Update Silences response failure |

**Success Response Schema:**

[aaa_silences_components-schemas-response_collection](../schemas/aaa/aaa-silences-components-schemas-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
