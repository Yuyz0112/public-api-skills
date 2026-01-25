# POST /zones/{zone_id}/client_certificates

**Resource:** [API Shield Client Certificates for a Zone](../resources/API-Shield-Client-Certificates-for-a-Zone.md)
**Create Client Certificate**
**Operation ID:** `client-certificate-for-a-zone-create-client-certificate`

Create a new API Shield mTLS Client Certificate

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
| 200 | Create Client Certificate Response |
| 4XX | Create Client Certificate Response Failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_client_certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-client-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
