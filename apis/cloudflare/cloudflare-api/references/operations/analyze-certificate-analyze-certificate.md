# POST /zones/{zone_id}/ssl/analyze

**Resource:** [Analyze Certificate](../resources/Analyze-Certificate.md)
**Analyze Certificate**
**Operation ID:** `analyze-certificate-analyze-certificate`

Returns the set of hostnames, the signature algorithm, and the expiration date of the certificate.

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
| 200 | Analyze Certificate response |
| 4XX | Analyze Certificate response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_analyze_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-analyze-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
