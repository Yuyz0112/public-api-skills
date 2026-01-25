# GET /accounts/{account_id}/access/identity_providers

**Resource:** [Access identity providers](../resources/Access-identity-providers.md)
**List Access identity providers**
**Operation ID:** `access-identity-providers-list-access-identity-providers`

Lists all configured identity providers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `scim_enabled` | query | string | No |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Access identity providers response |
| 4XX | List Access identity providers response failure |

**Success Response Schema:**

[access_response_collection](../schemas/access/access-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
