# GET /accounts/{account_id}/access/policy-tests/{policy_test_id}

**Resource:** [Access policy tester](../resources/Access-policy-tester.md)
**Get the current status of a given Access policy test**
**Operation ID:** `access-policy-tests-get-an-update`

Fetches the current status of a given Access policy test.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `policy_test_id` | path | access_policy_test_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an Access policy test update response. |
| 400 | Get an Access policy test update response failure. |

**Success Response Schema:**

[access_policy_update_resp](../schemas/access/access-policy-update-resp.md)

## Security

- **api_email**
- **api_key**
- **api_token**
