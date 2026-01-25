# DELETE /accounts/{account_id}/access/groups/{group_id}

**Resource:** [Access groups](../resources/Access-groups.md)
**Delete an Access group**
**Operation ID:** `access-groups-delete-an-access-group`

Deletes an Access group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `group_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete an Access group response |
| 4XX | Delete an Access group response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
