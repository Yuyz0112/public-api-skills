# POST /accounts/{account_id}/access/identity_providers

**Resource:** [Access identity providers](../resources/Access-identity-providers.md)
**Add an Access identity provider**
**Operation ID:** `access-identity-providers-add-an-access-identity-provider`

Adds a new identity provider to Access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_identity-providers](../schemas/access/access-identity-providers.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Add an Access identity provider response |
| 4XX | Add an Access identity provider response failure |

**Success Response Schema:**

[access_components-schemas-single_response](../schemas/access/access-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
