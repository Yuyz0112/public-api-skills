# PUT /zones/{zone_id}/access/certificates/settings

**Resource:** [Zone-Level Access mTLS authentication](../resources/Zone-Level-Access-mTLS-authentication.md)
**Update an mTLS certificate's hostname settings**
**Operation ID:** `zone-level-access-mtls-authentication-update-an-mtls-certificate-settings`

Updates an mTLS certificate's hostname settings.

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
| 202 | Update an mTLS certificates hostname settings response |
| 4XX | Update an mTLS certificates hostname settings failure |

## Security

- **api_email**
- **api_key**
