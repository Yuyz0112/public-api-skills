# GET /accounts/{account_id}/access/apps/{app_id}/user_policy_checks

**Resource:** [Access applications](../resources/Access-applications.md)
**Test Access policies**
**Operation ID:** `access-applications-test-access-policies`

Tests if a specific user has permission to access an application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_app_id | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Test Access policies response |
| 4XX | Test Access policies response failure |

**Success Response Schema:**

[access_policy_check_response](../schemas/access/access-policy-check-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
