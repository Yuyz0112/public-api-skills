# GET /accounts/{account_id}/mtls_certificates/{mtls_certificate_id}

**Resource:** [mTLS Certificate Management](../resources/mTLS-Certificate-Management.md)
**Get mTLS certificate**
**Operation ID:** `m-tls-certificate-management-get-m-tls-certificate`

Fetches a single mTLS certificate.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `mtls_certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `account_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get mTLS certificate response |
| 4XX | Get mTLS certificate response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_mtls-management_components-schemas-certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-mtls-management-components-schemas-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
