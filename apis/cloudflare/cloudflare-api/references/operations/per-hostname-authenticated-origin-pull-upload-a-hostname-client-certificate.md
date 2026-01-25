# POST /zones/{zone_id}/origin_tls_client_auth/hostnames/certificates

**Resource:** [Per-hostname Authenticated Origin Pull](../resources/Per-hostname-Authenticated-Origin-Pull.md)
**Upload a Hostname Client Certificate**
**Operation ID:** `per-hostname-authenticated-origin-pull-upload-a-hostname-client-certificate`

Upload a certificate to be used for client authentication on a hostname. 10 hostname certificates per zone are allowed.

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
| 200 | Upload a Hostname Client Certificate response |
| 4XX | Upload a Hostname Client Certificate response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_hostname-authenticated-origin-pull_components-schemas-certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-hostname-authenticated-origin-pull-components-schemas-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
