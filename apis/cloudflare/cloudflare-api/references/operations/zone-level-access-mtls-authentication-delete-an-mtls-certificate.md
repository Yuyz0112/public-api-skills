# DELETE /zones/{zone_id}/access/certificates/{certificate_id}

**Resource:** [Zone-Level Access mTLS authentication](../resources/Zone-Level-Access-mTLS-authentication.md)
**Delete an mTLS certificate**
**Operation ID:** `zone-level-access-mtls-authentication-delete-an-mtls-certificate`

Deletes an mTLS certificate.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete an mTLS certificate response |
| 4XX | Delete an mTLS certificate response failure |

**Success Response Schema:**

[access_components-schemas-id_response](../schemas/access/access-components-schemas-id-response.md)

## Security

- **api_email**
- **api_key**
