# GET /zones/{zone_id}/ssl/universal/settings

**Resource:** [Universal SSL Settings for a Zone](../resources/Universal-SSL-Settings-for-a-Zone.md)
**Universal SSL Settings Details**
**Operation ID:** `universal-ssl-settings-for-a-zone-universal-ssl-settings-details`

Get Universal SSL Settings for a Zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Universal SSL Settings Details response |
| 4XX | Universal SSL Settings Details response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_ssl_universal_settings_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-ssl-universal-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
