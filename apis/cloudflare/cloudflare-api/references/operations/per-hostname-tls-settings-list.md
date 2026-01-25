# GET /zones/{zone_id}/hostnames/settings/{setting_id}

**Resource:** [Per-Hostname TLS Settings](../resources/Per-Hostname-TLS-Settings.md)
**List TLS setting for hostnames**
**Operation ID:** `per-hostname-tls-settings-list`

List the requested TLS setting for the hostnames under this zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `setting_id` | path | tls-certificates-and-hostnames_setting_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List per-hostname TLS settings response |
| 4XX | List per-hostname TLS settings response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_per_hostname_settings_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-per-hostname-settings-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
