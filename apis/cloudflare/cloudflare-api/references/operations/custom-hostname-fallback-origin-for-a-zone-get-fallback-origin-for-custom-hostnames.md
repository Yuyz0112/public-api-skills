# GET /zones/{zone_id}/custom_hostnames/fallback_origin

**Resource:** [Custom Hostname Fallback Origin for a Zone](../resources/Custom-Hostname-Fallback-Origin-for-a-Zone.md)
**Get Fallback Origin for Custom Hostnames**
**Operation ID:** `custom-hostname-fallback-origin-for-a-zone-get-fallback-origin-for-custom-hostnames`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Fallback Origin for Custom Hostnames response |
| 4XX | Get Fallback Origin for Custom Hostnames response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_fallback_origin_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-fallback-origin-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
