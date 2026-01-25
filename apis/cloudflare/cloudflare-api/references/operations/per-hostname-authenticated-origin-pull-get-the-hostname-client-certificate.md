# GET /zones/{zone_id}/origin_tls_client_auth/hostnames/certificates/{certificate_id}

**Resource:** [Per-hostname Authenticated Origin Pull](../resources/Per-hostname-Authenticated-Origin-Pull.md)
**Get the Hostname Client Certificate**
**Operation ID:** `per-hostname-authenticated-origin-pull-get-the-hostname-client-certificate`

Get the certificate by ID to be used for client authentication on a hostname.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the Hostname Client Certificate response |
| 4XX | Get the Hostname Client Certificate response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_hostname-authenticated-origin-pull_components-schemas-certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-hostname-authenticated-origin-pull-components-schemas-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
