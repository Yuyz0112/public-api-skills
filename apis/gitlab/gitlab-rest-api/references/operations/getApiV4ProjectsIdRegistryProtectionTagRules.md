# GET /api/v4/projects/{id}/registry/protection/tag/rules

**Resource:** [Projects](../resources/Projects.md)
**Gets a list of container protection tag rules for a project.**
**Operation ID:** `getApiV4ProjectsIdRegistryProtectionTagRules`

This feature was introduced in GitLab 18.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesProjectsContainerRegistryProtectionTagRule](../schemas/APIEntitiesProjectsContainerRegistryProtectionTagRule/APIEntitiesProjectsContainerRegistryProtectionTagRule.md)

