# GET /accounts/{account_id}/access/policy-tests/{policy_test_id}/users

**Resource:** [Access policy tester](../resources/Access-policy-tester.md)
**Get an Access policy test users page**
**Operation ID:** `access-policy-tests-get-a-user-page`

Fetches a single page of user results from an Access policy test.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `policy_test_id` | path | access_policy_test_id | Yes |  |
| `per_page` | query | integer | No |  |
| `status` | query | enum: success, fail, error | No | Filter users by their policy evaluation status. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an Access policy tester users page response. |
| 400 | Get an Access policy tester users page response failure. |

**Success Response Schema:**

[access_policy_users_resp](../schemas/access/access-policy-users-resp.md)

## Security

- **api_email**
- **api_key**
- **api_token**
