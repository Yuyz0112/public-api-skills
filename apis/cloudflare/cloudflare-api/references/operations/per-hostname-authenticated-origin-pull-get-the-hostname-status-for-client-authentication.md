# GET /zones/{zone_id}/origin_tls_client_auth/hostnames/{hostname}

**Resource:** [Per-hostname Authenticated Origin Pull](../resources/Per-hostname-Authenticated-Origin-Pull.md)
**Get the Hostname Status for Client Authentication**
**Operation ID:** `per-hostname-authenticated-origin-pull-get-the-hostname-status-for-client-authentication`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hostname` | path | tls-certificates-and-hostnames_schemas-hostname | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the Hostname Status for Client Authentication response |
| 4XX | Get the Hostname Status for Client Authentication response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_hostname_aop_single_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-hostname-aop-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
