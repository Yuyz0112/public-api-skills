# PUT /accounts/{account_id}/alerting/v3/policies/{policy_id}

**Resource:** [Notification policies](../resources/Notification-policies.md)
**Update a Notification policy**
**Operation ID:** `notification-policies-update-a-notification-policy`

Update a Notification policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |
| `policy_id` | path | aaa_policy-id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a Notification policy response |
| 4XX | Update a Notification policy response failure |

**Success Response Schema:**

[aaa_id_response](../schemas/aaa/aaa-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
