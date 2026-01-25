# GET /accounts/{account_id}/alerting/v3/policies/{policy_id}

**Resource:** [Notification policies](../resources/Notification-policies.md)
**Get a Notification policy**
**Operation ID:** `notification-policies-get-a-notification-policy`

Get details for a single policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |
| `policy_id` | path | aaa_policy-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Notification policy response |
| 4XX | Get a Notification policy response failure |

**Success Response Schema:**

[aaa_single_response](../schemas/aaa/aaa-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
