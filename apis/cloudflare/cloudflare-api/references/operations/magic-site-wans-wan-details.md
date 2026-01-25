# GET /accounts/{account_id}/magic/sites/{site_id}/wans/{wan_id}

**Resource:** [Magic Site WANs](../resources/Magic-Site-WANs.md)
**Site WAN Details**
**Operation ID:** `magic-site-wans-wan-details`

Get a specific Site WAN.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `wan_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Site WAN Details response |
| 4XX | Site WAN Details response failure |

**Success Response Schema:**

[magic_wan_single_response](../schemas/magic/magic-wan-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
