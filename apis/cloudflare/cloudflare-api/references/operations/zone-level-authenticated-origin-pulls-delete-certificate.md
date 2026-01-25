# DELETE /zones/{zone_id}/origin_tls_client_auth/{certificate_id}

**Resource:** [Zone-Level Authenticated Origin Pulls](../resources/Zone-Level-Authenticated-Origin-Pulls.md)
**Delete Certificate**
**Operation ID:** `zone-level-authenticated-origin-pulls-delete-certificate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Certificate response |
| 4XX | Delete Certificate response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_components-schemas-certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-components-schemas-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
