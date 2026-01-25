# GET /accounts/{account_id}/access/identity_providers/{identity_provider_id}/scim/groups

**Resource:** [Access identity providers](../resources/Access-identity-providers.md)
**List SCIM Group resources**
**Operation ID:** `access-identity-providers-list-scim-group-resources`

Lists SCIM Group resources synced to Cloudflare via the System for Cross-domain Identity Management (SCIM).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identity_provider_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |
| `cf_resource_id` | query | access_cf_resource_id | No |  |
| `idp_resource_id` | query | access_idp_resource_id | No |  |
| `name` | query | access_groups-name | No |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List SCIM Group resources response |
| 4XX | List SCIM Group resources response failure |

**Success Response Schema:**

[access_scim_groups_response](../schemas/access/access-scim-groups-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
