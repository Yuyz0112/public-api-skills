# PUT /zones/{zone_id}/origin_tls_client_auth/hostnames

**Resource:** [Per-hostname Authenticated Origin Pull](../resources/Per-hostname-Authenticated-Origin-Pull.md)
**Enable or Disable a Hostname for Client Authentication**
**Operation ID:** `per-hostname-authenticated-origin-pull-enable-or-disable-a-hostname-for-client-authentication`

Associate a hostname to a certificate and enable, disable or invalidate the association. If disabled, client certificate will not be sent to the hostname even if activated at the zone level. 100 maximum associations on a single certificate are allowed. Note: Use a null value for parameter *enabled* to invalidate the association.

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
| 200 | Enable or Disable a Hostname for Client Authentication response |
| 4XX | Enable or Disable a Hostname for Client Authentication response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_hostname_aop_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-hostname-aop-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
