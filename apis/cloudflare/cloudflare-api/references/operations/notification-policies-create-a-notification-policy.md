# POST /accounts/{account_id}/alerting/v3/policies

**Resource:** [Notification policies](../resources/Notification-policies.md)
**Create a Notification policy**
**Operation ID:** `notification-policies-create-a-notification-policy`

Creates a new Notification policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a Notification policy response |
| 4XX | Create a Notification policy response failure |

**Success Response Schema:**

[aaa_id_response](../schemas/aaa/aaa-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
