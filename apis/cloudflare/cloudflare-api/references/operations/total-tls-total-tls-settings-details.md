# GET /zones/{zone_id}/acm/total_tls

**Resource:** [Total TLS](../resources/Total-TLS.md)
**Total TLS Settings Details**
**Operation ID:** `total-tls-total-tls-settings-details`

Get Total TLS Settings for a Zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Total TLS Settings Details response |
| 4XX | Total TLS Settings Details response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_total_tls_settings_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-total-tls-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
