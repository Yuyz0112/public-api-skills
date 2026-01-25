# PUT /accounts/{account_id}/access/policies/{policy_id}

**Resource:** [Access reusable policies](../resources/Access-reusable-policies.md)
**Update an Access reusable policy**
**Operation ID:** `access-policies-update-an-access-reusable-policy`

Updates a Access reusable policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `policy_id` | path | access_schemas-uuid | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_policy_req](../schemas/access/access-policy-req.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an Access reusable policy response. |
| 4XX | Update an Access reusable policy response failure. |

**Success Response Schema:**

[access_reusable-policies_components-schemas-single_response](../schemas/access/access-reusable-policies-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
