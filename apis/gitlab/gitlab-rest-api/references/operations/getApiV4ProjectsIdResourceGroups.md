# GET /api/v4/projects/{id}/resource_groups

**Resource:** [CI resource groups](../resources/CI-resource-groups.md)
**Get all resource groups for a project**
**Operation ID:** `getApiV4ProjectsIdResourceGroups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiResourceGroup](../schemas/APIEntitiesCiResourceGroup/APIEntitiesCiResourceGroup.md)

