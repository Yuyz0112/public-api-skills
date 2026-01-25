# DELETE /zones/{zone_id}/access/apps/{app_id}/policies/{policy_id}

**Resource:** [Zone-Level Access policies](../resources/Zone-Level-Access-policies.md)
**Delete an Access policy**
**Operation ID:** `zone-level-access-policies-delete-an-access-policy`

Delete an Access policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `policy_id` | path | access_uuid | Yes |  |
| `app_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete an Access policy response |
| 4XX | Delete an Access policy response failure |

## Security

- **api_email**
- **api_key**
