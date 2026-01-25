# GET /zones/{zone_id}/origin_tls_client_auth/{certificate_id}

**Resource:** [Zone-Level Authenticated Origin Pulls](../resources/Zone-Level-Authenticated-Origin-Pulls.md)
**Get Certificate Details**
**Operation ID:** `zone-level-authenticated-origin-pulls-get-certificate-details`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Certificate Details response |
| 4XX | Get Certificate Details response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_components-schemas-certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-components-schemas-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
