# PUT /zones/{zone_id}/custom_certificates/prioritize

**Resource:** [Custom SSL for a Zone](../resources/Custom-SSL-for-a-Zone.md)
**Re-prioritize SSL Certificates**
**Operation ID:** `custom-ssl-for-a-zone-re-prioritize-ssl-certificates`

If a zone has multiple SSL certificates, you can set the order in which they should be used during a request. The higher priority will break ties across overlapping 'legacy_custom' certificates.

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
| 200 | Re-prioritize SSL Certificates response |
| 4XX | Re-prioritize SSL Certificates response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
