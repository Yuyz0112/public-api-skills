# PUT /zones/{zone_id}/origin_tls_client_auth/settings

**Resource:** [Zone-Level Authenticated Origin Pulls](../resources/Zone-Level-Authenticated-Origin-Pulls.md)
**Set Enablement for Zone**
**Operation ID:** `zone-level-authenticated-origin-pulls-set-enablement-for-zone`

Enable or disable zone-level authenticated origin pulls. 'enabled' should be set true either before/after the certificate is uploaded to see the certificate in use.

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
| 200 | Set Enablement for Zone response |
| 4XX | Set Enablement for Zone response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_enabled_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-enabled-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
