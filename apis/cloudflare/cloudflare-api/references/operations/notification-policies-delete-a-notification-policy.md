# DELETE /accounts/{account_id}/alerting/v3/policies/{policy_id}

**Resource:** [Notification policies](../resources/Notification-policies.md)
**Delete a Notification policy**
**Operation ID:** `notification-policies-delete-a-notification-policy`

Delete a Notification policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |
| `policy_id` | path | aaa_policy-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a Notification policy response |
| 4XX | Delete a Notification policy response failure |

**Success Response Schema:**

[aaa_api-response-collection](../schemas/aaa/aaa-api-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
