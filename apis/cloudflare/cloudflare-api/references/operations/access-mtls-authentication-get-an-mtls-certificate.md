# GET /accounts/{account_id}/access/certificates/{certificate_id}

**Resource:** [Access mTLS authentication](../resources/Access-mTLS-authentication.md)
**Get an mTLS certificate**
**Operation ID:** `access-mtls-authentication-get-an-mtls-certificate`

Fetches a single mTLS certificate.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an mTLS certificate response |
| 4XX | Get an mTLS certificate response failure |

**Success Response Schema:**

[access_certificates_components-schemas-single_response](../schemas/access/access-certificates-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
