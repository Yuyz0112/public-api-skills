# POST /accounts/{account_id}/access/policies

**Resource:** [Access reusable policies](../resources/Access-reusable-policies.md)
**Create an Access reusable policy**
**Operation ID:** `access-policies-create-an-access-reusable-policy`

Creates a new Access reusable policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_policy_req](../schemas/access/access-policy-req.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create an Access reusable policy response. |
| 4XX | Create an Access reusable policy response failure. |

**Success Response Schema:**

[access_reusable-policies_components-schemas-single_response](../schemas/access/access-reusable-policies-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
