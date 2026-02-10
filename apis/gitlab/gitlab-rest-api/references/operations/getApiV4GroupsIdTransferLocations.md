# GET /api/v4/groups/{id}/transfer_locations

**Resource:** [Groups](../resources/Groups.md)
**Get the groups to where the current group can be transferred to**
**Operation ID:** `getApiV4GroupsIdTransferLocations`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `search` | query | string | No | Return list of namespaces matching the search criteria |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroup](../schemas/APIEntitiesGroup/APIEntitiesGroup.md)

