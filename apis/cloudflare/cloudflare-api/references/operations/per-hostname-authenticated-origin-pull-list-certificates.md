# GET /zones/{zone_id}/origin_tls_client_auth/hostnames/certificates

**Resource:** [Per-hostname Authenticated Origin Pull](../resources/Per-hostname-Authenticated-Origin-Pull.md)
**List Certificates**
**Operation ID:** `per-hostname-authenticated-origin-pull-list-certificates`

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

[tls-certificates-and-hostnames_hostname-authenticated-origin-pull_components-schemas-certificate_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-hostname-authenticated-origin-pull-components-schemas-certificate-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
