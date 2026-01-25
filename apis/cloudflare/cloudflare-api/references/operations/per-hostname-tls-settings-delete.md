# DELETE /zones/{zone_id}/hostnames/settings/{setting_id}/{hostname}

**Resource:** [Per-Hostname TLS Settings](../resources/Per-Hostname-TLS-Settings.md)
**Delete TLS setting for hostname**
**Operation ID:** `per-hostname-tls-settings-delete`

Delete the tls setting value for the hostname.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `setting_id` | path | tls-certificates-and-hostnames_setting_id | Yes |  |
| `hostname` | path | tls-certificates-and-hostnames_components-schemas-hostname | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete TLS setting for hostname response |
| 4XX | Delete TLS setting for hostname response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_per_hostname_settings_response_delete](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-per-hostname-settings-response-delete.md)

## Security

- **api_email**
- **api_key**
- **api_token**
