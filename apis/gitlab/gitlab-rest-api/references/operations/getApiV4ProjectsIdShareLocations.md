# GET /api/v4/projects/{id}/share_locations

**Resource:** [Groups](../resources/Groups.md)
**Returns group that can be shared with the given project**
**Operation ID:** `getApiV4ProjectsIdShareLocations`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The id of the project |
| `search` | query | string | No | Return list of groups matching the search criteria |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroup](../schemas/APIEntitiesGroup/APIEntitiesGroup.md)

