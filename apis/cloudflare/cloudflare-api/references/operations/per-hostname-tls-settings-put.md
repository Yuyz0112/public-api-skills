# PUT /zones/{zone_id}/hostnames/settings/{setting_id}/{hostname}

**Resource:** [Per-Hostname TLS Settings](../resources/Per-Hostname-TLS-Settings.md)
**Edit TLS setting for hostname**
**Operation ID:** `per-hostname-tls-settings-put`

Update the tls setting value for the hostname.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `setting_id` | path | tls-certificates-and-hostnames_setting_id | Yes |  |
| `hostname` | path | tls-certificates-and-hostnames_components-schemas-hostname | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit TLS setting for hostname response |
| 4XX | Edit TLS setting for hostname response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_per_hostname_settings_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-per-hostname-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
