# PATCH /zones/{zone_id}/ssl/universal/settings

**Resource:** [Universal SSL Settings for a Zone](../resources/Universal-SSL-Settings-for-a-Zone.md)
**Edit Universal SSL Settings**
**Operation ID:** `universal-ssl-settings-for-a-zone-edit-universal-ssl-settings`

Patch Universal SSL Settings for a Zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [tls-certificates-and-hostnames_universal](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-universal.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit Universal SSL Settings response |
| 4XX | Edit Universal SSL Settings response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_ssl_universal_settings_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-ssl-universal-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
