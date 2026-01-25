# GET /zones/{zone_id}/origin_tls_client_auth/settings

**Resource:** [Zone-Level Authenticated Origin Pulls](../resources/Zone-Level-Authenticated-Origin-Pulls.md)
**Get Enablement Setting for Zone**
**Operation ID:** `zone-level-authenticated-origin-pulls-get-enablement-setting-for-zone`

Get whether zone-level authenticated origin pulls is enabled or not. It is false by default.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Enablement Setting for Zone response |
| 4XX | Get Enablement Setting for Zone response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_enabled_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-enabled-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
