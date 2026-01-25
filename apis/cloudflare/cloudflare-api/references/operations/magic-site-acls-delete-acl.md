# DELETE /accounts/{account_id}/magic/sites/{site_id}/acls/{acl_id}

**Resource:** [Magic Site ACLs](../resources/Magic-Site-ACLs.md)
**Delete Site ACL**
**Operation ID:** `magic-site-acls-delete-acl`

Remove a specific Site ACL.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `acl_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Site ACL response |
| 4XX | Delete Site ACL response failure |

**Success Response Schema:**

[magic_acl_deleted_response](../schemas/magic/magic-acl-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
