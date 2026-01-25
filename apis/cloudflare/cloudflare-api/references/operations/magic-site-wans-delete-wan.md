# DELETE /accounts/{account_id}/magic/sites/{site_id}/wans/{wan_id}

**Resource:** [Magic Site WANs](../resources/Magic-Site-WANs.md)
**Delete Site WAN**
**Operation ID:** `magic-site-wans-delete-wan`

Remove a specific Site WAN.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `wan_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Site WAN response |
| 4XX | Delete Site WAN response failure |

**Success Response Schema:**

[magic_wan_deleted_response](../schemas/magic/magic-wan-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
