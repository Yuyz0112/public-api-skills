# PATCH /accounts/{account_id}/magic/sites/{site_id}/acls/{acl_id}

**Resource:** [Magic Site ACLs](../resources/Magic-Site-ACLs.md)
**Patch Site ACL**
**Operation ID:** `magic-site-acls-patch-acl`

Patch a specific Site ACL.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `acl_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_acl_update_request](../schemas/magic/magic-acl-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch Site ACL response |
| 4XX | Patch Site ACL response failure |

**Success Response Schema:**

[magic_acl_modified_response](../schemas/magic/magic-acl-modified-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
