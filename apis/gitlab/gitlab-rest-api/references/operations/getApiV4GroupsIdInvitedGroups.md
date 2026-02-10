# GET /api/v4/groups/{id}/invited_groups

**Resource:** [Groups](../resources/Groups.md)
**Get a list of invited groups in this group**
**Operation ID:** `getApiV4GroupsIdInvitedGroups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `relation` | query | any | No | Include group relations |
| `search` | query | string | No | Search for a specific group |
| `min_access_level` | query | enum: 10, 15, 20... | No | Minimum access level of authenticated user |
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

