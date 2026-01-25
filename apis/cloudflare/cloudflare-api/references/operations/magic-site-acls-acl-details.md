# GET /accounts/{account_id}/magic/sites/{site_id}/acls/{acl_id}

**Resource:** [Magic Site ACLs](../resources/Magic-Site-ACLs.md)
**Site ACL Details**
**Operation ID:** `magic-site-acls-acl-details`

Get a specific Site ACL.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `acl_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Site ACL Details response |
| 4XX | Site ACL Details response failure |

**Success Response Schema:**

[magic_acl_single_response](../schemas/magic/magic-acl-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
