# GET /zones/{zone_id}/client_certificates/{client_certificate_id}

**Resource:** [API Shield Client Certificates for a Zone](../resources/API-Shield-Client-Certificates-for-a-Zone.md)
**Client Certificate Details**
**Operation ID:** `client-certificate-for-a-zone-client-certificate-details`

Get Details for a single mTLS API Shield Client Certificate

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `client_certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Client Certificate Details Response |
| 4XX | Client Certificate Details Response Failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_client_certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-client-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
