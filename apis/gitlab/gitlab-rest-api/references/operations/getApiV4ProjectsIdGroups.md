# GET /api/v4/projects/{id}/groups

**Resource:** [Projects](../resources/Projects.md)
**Get ancestor and shared groups for a project**
**Operation ID:** `getApiV4ProjectsIdGroups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `search` | query | string | No | Return list of groups matching the search criteria |
| `skip_groups` | query | any | No | Array of group ids to exclude from list |
| `with_shared` | query | boolean | No | Include shared groups |
| `shared_visible_only` | query | boolean | No | Limit to shared groups user has access to |
| `shared_min_access_level` | query | enum: 10, 15, 20... | No | Limit returned shared groups by minimum access level to the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesPublicGroupDetails](../schemas/APIEntitiesPublicGroupDetails/APIEntitiesPublicGroupDetails.md)

