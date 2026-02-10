# PUT /api/v4/projects/{id}/resource_groups/{key}

**Resource:** [CI resource groups](../resources/CI-resource-groups.md)
**Edit an existing resource group**
**Operation ID:** `putApiV4ProjectsIdResourceGroupsKey`

Updates an existing resource group's properties.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `key` | path | string | Yes | The key of the resource group |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiResourceGroup](../schemas/APIEntitiesCiResourceGroup/APIEntitiesCiResourceGroup.md)

