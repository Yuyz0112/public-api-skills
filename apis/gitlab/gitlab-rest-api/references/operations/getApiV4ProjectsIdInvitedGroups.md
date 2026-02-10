# GET /api/v4/projects/{id}/invited_groups

**Resource:** [Projects](../resources/Projects.md)
**Get a list of invited groups in this project**
**Operation ID:** `getApiV4ProjectsIdInvitedGroups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `relation` | query | any | No | Filter by group relation |
| `search` | query | string | No | Search for a specific group |
| `min_access_level` | query | enum: 10, 15, 20... | No | Limit by minimum access level of authenticated user |
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

