# PATCH /accounts/{account_id}/magic/sites/{site_id}/lans/{lan_id}

**Resource:** [Magic Site LANs](../resources/Magic-Site-LANs.md)
**Patch Site LAN**
**Operation ID:** `magic-site-lans-patch-lan`

Patch a specific Site LAN.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `lan_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_lan_update_request](../schemas/magic/magic-lan-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch Site LAN response |
| 4XX | Patch Site LAN response failure |

**Success Response Schema:**

[magic_lan_modified_response](../schemas/magic/magic-lan-modified-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
