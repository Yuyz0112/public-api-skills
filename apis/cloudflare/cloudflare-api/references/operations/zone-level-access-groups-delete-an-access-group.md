# DELETE /zones/{zone_id}/access/groups/{group_id}

**Resource:** [Zone-Level Access groups](../resources/Zone-Level-Access-groups.md)
**Delete an Access group**
**Operation ID:** `zone-level-access-groups-delete-an-access-group`

Deletes an Access group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `group_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete an Access group response |
| 4XX | Delete an Access group response failure |

## Security

- **api_email**
- **api_key**
