# POST /accounts/{account_id}/magic/sites/{site_id}/acls

**Resource:** [Magic Site ACLs](../resources/Magic-Site-ACLs.md)
**Create a new Site ACL**
**Operation ID:** `magic-site-acls-create-acl`

Creates a new Site ACL.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_acls_add_single_request](../schemas/magic/magic-acls-add-single-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Site ACL response |
| 4XX | Create Site ACL response failure |

**Success Response Schema:**

[magic_acl_single_response](../schemas/magic/magic-acl-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
