# GET /accounts/{account_id}/magic/sites/{site_id}/acls

**Resource:** [Magic Site ACLs](../resources/Magic-Site-ACLs.md)
**List Site ACLs**
**Operation ID:** `magic-site-acls-list-acls`

Lists Site ACLs associated with an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Site ACLs response |
| 4XX | List Site ACLs response failure |

**Success Response Schema:**

[magic_acls_collection_response](../schemas/magic/magic-acls-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
