# DELETE /zones/{zone_id}/access/identity_providers/{identity_provider_id}

**Resource:** [Zone-Level Access identity providers](../resources/Zone-Level-Access-identity-providers.md)
**Delete an Access identity provider**
**Operation ID:** `zone-level-access-identity-providers-delete-an-access-identity-provider`

Deletes an identity provider from Access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identity_provider_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete an Access identity provider response |
| 4XX | Delete an Access identity provider response failure |

## Security

- **api_email**
- **api_key**
