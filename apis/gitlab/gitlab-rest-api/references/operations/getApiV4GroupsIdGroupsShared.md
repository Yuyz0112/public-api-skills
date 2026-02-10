# GET /api/v4/groups/{id}/groups/shared

**Resource:** [Groups](../resources/Groups.md)
**Get a list of shared groups this group was invited to**
**Operation ID:** `getApiV4GroupsIdGroupsShared`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `skip_groups` | query | any | No | Array of group ids to exclude from list |
| `visibility` | query | enum: private, internal, public | No | Limit by visibility |
| `search` | query | string | No | Search for a specific group |
| `min_access_level` | query | enum: 10, 15, 20... | No | Minimum access level of authenticated user |
| `order_by` | query | enum: name, path, id... | No | Order by name, path, id or similarity if searching |
| `sort` | query | enum: asc, desc | No | Sort by asc (ascending) or desc (descending) |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `with_custom_attributes` | query | boolean | No | Include custom attributes in the response |
| `custom_attributes` | query | object | No | Filter with custom attributes |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroup](../schemas/APIEntitiesGroup/APIEntitiesGroup.md)

