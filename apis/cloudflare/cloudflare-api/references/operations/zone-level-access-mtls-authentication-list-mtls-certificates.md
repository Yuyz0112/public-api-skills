# GET /zones/{zone_id}/access/certificates

**Resource:** [Zone-Level Access mTLS authentication](../resources/Zone-Level-Access-mTLS-authentication.md)
**List mTLS certificates**
**Operation ID:** `zone-level-access-mtls-authentication-list-mtls-certificates`

Lists all mTLS certificates.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List mTLS certificates response |
| 4XX | List mTLS certificates response failure |

**Success Response Schema:**

[access_certificates_components-schemas-response_collection-2](../schemas/access/access-certificates-components-schemas-response-collection-2.md)

## Security

- **api_email**
- **api_key**
