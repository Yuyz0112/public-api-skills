# POST /zones/{zone_id}/access/apps/{app_id}/revoke_tokens

**Resource:** [Zone-Level Access applications](../resources/Zone-Level-Access-applications.md)
**Revoke application tokens**
**Operation ID:** `zone-level-access-applications-revoke-service-tokens`

Revokes all tokens issued for an application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_app_id | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Revoke application tokens response |
| 4XX | Revoke application tokens response failure |

## Security

- **api_email**
- **api_key**
