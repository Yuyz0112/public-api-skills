# DELETE /accounts/{account_id}/magic/sites/{site_id}/lans/{lan_id}

**Resource:** [Magic Site LANs](../resources/Magic-Site-LANs.md)
**Delete Site LAN**
**Operation ID:** `magic-site-lans-delete-lan`

Remove a specific Site LAN.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `lan_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Site LAN response |
| 4XX | Delete Site LAN response failure |

**Success Response Schema:**

[magic_lan_deleted_response](../schemas/magic/magic-lan-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
