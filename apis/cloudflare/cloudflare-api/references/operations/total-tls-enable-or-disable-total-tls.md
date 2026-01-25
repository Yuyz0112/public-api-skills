# POST /zones/{zone_id}/acm/total_tls

**Resource:** [Total TLS](../resources/Total-TLS.md)
**Enable or Disable Total TLS**
**Operation ID:** `total-tls-enable-or-disable-total-tls`

Set Total TLS Settings or disable the feature for a Zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Enable or Disable Total TLS response |
| 4XX | Enable or Disable Total TLS response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_total_tls_settings_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-total-tls-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
