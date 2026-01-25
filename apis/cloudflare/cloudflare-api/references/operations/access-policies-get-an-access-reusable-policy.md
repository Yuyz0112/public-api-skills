# GET /accounts/{account_id}/access/policies/{policy_id}

**Resource:** [Access reusable policies](../resources/Access-reusable-policies.md)
**Get an Access reusable policy**
**Operation ID:** `access-policies-get-an-access-reusable-policy`

Fetches a single Access reusable policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `policy_id` | path | access_schemas-uuid | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an Access reusable policy response. |
| 4XX | Get an Access reusable policy response failure. |

**Success Response Schema:**

[access_reusable-policies_components-schemas-single_response](../schemas/access/access-reusable-policies-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
