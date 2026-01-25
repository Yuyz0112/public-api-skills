# GET /zones/{zone_id}/ssl/verification

**Resource:** [SSL Verification](../resources/SSL-Verification.md)
**SSL Verification Details**
**Operation ID:** `ssl-verification-ssl-verification-details`

Get SSL Verification Info for a Zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `retry` | query | enum: true | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | SSL Verification Details response |
| 4XX | SSL Verification Details response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_ssl_verification_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-ssl-verification-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
