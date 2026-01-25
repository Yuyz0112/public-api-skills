# PUT /zones/{zone_id}/access/certificates/{certificate_id}

**Resource:** [Zone-Level Access mTLS authentication](../resources/Zone-Level-Access-mTLS-authentication.md)
**Update an mTLS certificate**
**Operation ID:** `zone-level-access-mtls-authentication-update-an-mtls-certificate`

Updates a configured mTLS certificate.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an mTLS certificate response |
| 4XX | Update an mTLS certificate response failure |

**Success Response Schema:**

[access_certificates_components-schemas-single_response-2](../schemas/access/access-certificates-components-schemas-single-response-2.md)

## Security

- **api_email**
- **api_key**
