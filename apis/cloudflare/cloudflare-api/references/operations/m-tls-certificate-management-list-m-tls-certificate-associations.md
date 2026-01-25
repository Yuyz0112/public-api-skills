# GET /accounts/{account_id}/mtls_certificates/{mtls_certificate_id}/associations

**Resource:** [mTLS Certificate Management](../resources/mTLS-Certificate-Management.md)
**List mTLS certificate associations**
**Operation ID:** `m-tls-certificate-management-list-m-tls-certificate-associations`

Lists all active associations between the certificate and Cloudflare services.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `mtls_certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `account_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List mTLS certificate associations response |
| 4XX | List mTLS certificate associations response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_association_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-association-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
