# GET /zones/{zone_id}/origin_tls_client_auth

**Resource:** [Zone-Level Authenticated Origin Pulls](../resources/Zone-Level-Authenticated-Origin-Pulls.md)
**List Certificates**
**Operation ID:** `zone-level-authenticated-origin-pulls-list-certificates`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Certificates response |
| 4XX | List Certificates response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_components-schemas-certificate_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-components-schemas-certificate-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
