# POST /accounts/{account_id}/alerting/v3/silences

**Resource:** [Notification Silences](../resources/Notification-Silences.md)
**Create Silences**
**Operation ID:** `notification-silences-create-silences`

Creates a new silence for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [aaa_silence_create_request](../schemas/aaa/aaa-silence-create-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Silences response |
| 4XX | Create Silences response failure |

**Success Response Schema:**

[aaa_schemas-api-response-common](../schemas/aaa/aaa-schemas-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
