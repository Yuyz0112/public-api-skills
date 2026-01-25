# GET /accounts/{account_id}/access/policies

**Resource:** [Access reusable policies](../resources/Access-reusable-policies.md)
**List Access reusable policies**
**Operation ID:** `access-policies-list-access-reusable-policies`

Lists Access reusable policies.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Access reusable policies response. |
| 4XX | List Access reusable policies response failure. |

**Success Response Schema:**

[access_reusable-policies_components-schemas-response_collection](../schemas/access/access-reusable-policies-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
