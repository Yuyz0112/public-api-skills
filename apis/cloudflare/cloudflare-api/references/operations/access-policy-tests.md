# POST /accounts/{account_id}/access/policy-tests

**Resource:** [Access policy tester](../resources/Access-policy-tester.md)
**Start Access policy test**
**Operation ID:** `access-policy-tests`

Starts an Access policy test.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_policy_init_req](../schemas/access/access-policy-init-req.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Start Access policy test response. |
| 400 | Start Access policy test response failure. |

**Success Response Schema:**

[access_policy_init_resp](../schemas/access/access-policy-init-resp.md)

## Security

- **api_email**
- **api_key**
- **api_token**
