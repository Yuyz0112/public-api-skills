# GET /accounts/{account_id}/mtls_certificates

**Resource:** [mTLS Certificate Management](../resources/mTLS-Certificate-Management.md)
**List mTLS certificates**
**Operation ID:** `m-tls-certificate-management-list-m-tls-certificates`

Lists all mTLS certificates.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List mTLS certificates response |
| 4XX | List mTLS certificates response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_mtls-management_components-schemas-certificate_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-mtls-management-components-schemas-certificate-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
