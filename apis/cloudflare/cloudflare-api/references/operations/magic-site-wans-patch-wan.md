# PATCH /accounts/{account_id}/magic/sites/{site_id}/wans/{wan_id}

**Resource:** [Magic Site WANs](../resources/Magic-Site-WANs.md)
**Patch Site WAN**
**Operation ID:** `magic-site-wans-patch-wan`

Patch a specific Site WAN.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `wan_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_wan_update_request](../schemas/magic/magic-wan-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch Site WAN response |
| 4XX | Patch Site WAN response failure |

**Success Response Schema:**

[magic_wan_modified_response](../schemas/magic/magic-wan-modified-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
