# GET /zones/{zone_id}/access/certificates/settings

**Resource:** [Zone-Level Access mTLS authentication](../resources/Zone-Level-Access-mTLS-authentication.md)
**List all mTLS hostname settings**
**Operation ID:** `zone-level-access-mtls-authentication-list-mtls-certificates-hostname-settings`

List all mTLS hostname settings for this zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List mTLS hostname settings response |
| 4XX | List mTLS hostname settings response failure |

**Success Response Schema:**

[access_schemas-response_collection_hostnames](../schemas/access/access-schemas-response-collection-hostnames.md)

## Security

- **api_email**
- **api_key**
