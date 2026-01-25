# DELETE /zones/{zone_id}/firewall/lockdowns/{lock_downs_id}

**Resource:** [Zone Lockdown](../resources/Zone-Lockdown.md)
**Delete a Zone Lockdown rule**
**Operation ID:** `zone-lockdown-delete-a-zone-lockdown-rule`

Deletes an existing Zone Lockdown rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `lock_downs_id` | path | firewall_lockdowns_components-schemas-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a Zone Lockdown rule response |
| 4XX | Delete a Zone Lockdown rule response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
