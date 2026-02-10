# GET /api/v4/projects/{id}/resource_groups/{key}

**Resource:** [CI resource groups](../resources/CI-resource-groups.md)
**Get a specific resource group**
**Operation ID:** `getApiV4ProjectsIdResourceGroupsKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `key` | path | string | Yes | The key of the resource group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiResourceGroup](../schemas/APIEntitiesCiResourceGroup/APIEntitiesCiResourceGroup.md)

