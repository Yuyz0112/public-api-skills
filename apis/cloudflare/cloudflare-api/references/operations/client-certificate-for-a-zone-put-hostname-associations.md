# PUT /zones/{zone_id}/certificate_authorities/hostname_associations

**Resource:** [API Shield Client Certificates for a Zone](../resources/API-Shield-Client-Certificates-for-a-Zone.md)
**Replace Hostname Associations**
**Operation ID:** `client-certificate-for-a-zone-put-hostname-associations`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [tls-certificates-and-hostnames_hostname_association](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-hostname-association.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Replace Hostname Associations Response |
| 4XX | Replace Hostname Associations Response Failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_hostname_associations_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-hostname-associations-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
