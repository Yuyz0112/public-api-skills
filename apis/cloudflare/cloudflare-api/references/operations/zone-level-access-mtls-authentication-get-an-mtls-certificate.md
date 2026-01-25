# GET /zones/{zone_id}/access/certificates/{certificate_id}

**Resource:** [Zone-Level Access mTLS authentication](../resources/Zone-Level-Access-mTLS-authentication.md)
**Get an mTLS certificate**
**Operation ID:** `zone-level-access-mtls-authentication-get-an-mtls-certificate`

Fetches a single mTLS certificate.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an mTLS certificate response |
| 4XX | Get an mTLS certificate response failure |

**Success Response Schema:**

[access_certificates_components-schemas-single_response-2](../schemas/access/access-certificates-components-schemas-single-response-2.md)

## Security

- **api_email**
- **api_key**
