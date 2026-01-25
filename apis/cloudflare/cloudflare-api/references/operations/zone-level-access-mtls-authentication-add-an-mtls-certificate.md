# POST /zones/{zone_id}/access/certificates

**Resource:** [Zone-Level Access mTLS authentication](../resources/Zone-Level-Access-mTLS-authentication.md)
**Add an mTLS certificate**
**Operation ID:** `zone-level-access-mtls-authentication-add-an-mtls-certificate`

Adds a new mTLS root certificate to Access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Add an mTLS certificate response |
| 4XX | Add an mTLS certificate response failure |

**Success Response Schema:**

[access_certificates_components-schemas-single_response-2](../schemas/access/access-certificates-components-schemas-single-response-2.md)

## Security

- **api_email**
- **api_key**
