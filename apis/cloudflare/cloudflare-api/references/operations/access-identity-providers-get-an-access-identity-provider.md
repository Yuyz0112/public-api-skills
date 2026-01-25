# GET /accounts/{account_id}/access/identity_providers/{identity_provider_id}

**Resource:** [Access identity providers](../resources/Access-identity-providers.md)
**Get an Access identity provider**
**Operation ID:** `access-identity-providers-get-an-access-identity-provider`

Fetches a configured identity provider.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identity_provider_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an Access identity provider response |
| 4XX | Get an Access identity provider response failure |

**Success Response Schema:**

[access_components-schemas-single_response](../schemas/access/access-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
