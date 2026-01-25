# POST /accounts/{account_id}/mtls_certificates

**Resource:** [mTLS Certificate Management](../resources/mTLS-Certificate-Management.md)
**Upload mTLS certificate**
**Operation ID:** `m-tls-certificate-management-upload-m-tls-certificate`

Upload a certificate that you want to use with mTLS-enabled Cloudflare services.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Upload mTLS certificate response |
| 4XX | Upload mTLS certificate response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_response_single_post](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-response-single-post.md)

## Security

- **api_email**
- **api_key**
- **api_token**
