# GET /accounts/{account_id}/access/identity_providers/{identity_provider_id}/scim/users

**Resource:** [Access identity providers](../resources/Access-identity-providers.md)
**List SCIM User resources**
**Operation ID:** `access-identity-providers-list-scim-user-resources`

Lists SCIM User resources synced to Cloudflare via the System for Cross-domain Identity Management (SCIM).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identity_provider_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |
| `cf_resource_id` | query | access_users-cf_resource_id | No |  |
| `idp_resource_id` | query | access_users-idp_resource_id | No |  |
| `username` | query | access_username | No |  |
| `email` | query | access_email | No |  |
| `name` | query | access_users-name | No |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List SCIM User resources response |
| 4XX | List SCIM User resources response failure |

**Success Response Schema:**

[access_scim_users_response](../schemas/access/access-scim-users-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
