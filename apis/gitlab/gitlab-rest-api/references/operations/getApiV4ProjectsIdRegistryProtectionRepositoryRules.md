# GET /api/v4/projects/{id}/registry/protection/repository/rules

**Resource:** [Projects](../resources/Projects.md)
**Get list of container registry protection rules for a project**
**Operation ID:** `getApiV4ProjectsIdRegistryProtectionRepositoryRules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesProjectsContainerRegistryProtectionRule](../schemas/APIEntitiesProjectsContainerRegistryProtectionRule/APIEntitiesProjectsContainerRegistryProtectionRule.md)

