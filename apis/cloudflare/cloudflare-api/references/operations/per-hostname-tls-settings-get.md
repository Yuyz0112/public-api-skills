# GET /zones/{zone_id}/hostnames/settings/{setting_id}/{hostname}

**Resource:** [Per-Hostname TLS Settings](../resources/Per-Hostname-TLS-Settings.md)
**Get TLS setting for hostname**
**Operation ID:** `per-hostname-tls-settings-get`

Get the requested TLS setting for the hostname.

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
| 200 | Get TLS setting for hostname response |
| 4XX | Get TLS setting for hostname response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_per_hostname_settings_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-per-hostname-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
