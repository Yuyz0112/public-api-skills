# GET /accounts/{account_id}/magic/sites/{site_id}/lans/{lan_id}

**Resource:** [Magic Site LANs](../resources/Magic-Site-LANs.md)
**Site LAN Details**
**Operation ID:** `magic-site-lans-lan-details`

Get a specific Site LAN.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `lan_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Site LAN Details response |
| 4XX | Site LAN Details response failure |

**Success Response Schema:**

[magic_lan_single_response](../schemas/magic/magic-lan-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
