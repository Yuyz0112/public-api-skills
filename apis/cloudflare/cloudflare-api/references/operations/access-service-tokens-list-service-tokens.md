# GET /accounts/{account_id}/access/service_tokens

**Resource:** [Access service tokens](../resources/Access-service-tokens.md)
**List service tokens**
**Operation ID:** `access-service-tokens-list-service-tokens`

Lists all service tokens.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `name` | query | string | No |  |
| `search` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List service tokens response |
| 4XX | List service tokens response failure |

**Success Response Schema:**

[access_components-schemas-response_collection](../schemas/access/access-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
