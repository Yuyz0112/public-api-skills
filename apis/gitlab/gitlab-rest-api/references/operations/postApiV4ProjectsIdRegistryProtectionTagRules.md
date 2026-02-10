# POST /api/v4/projects/{id}/registry/protection/tag/rules

**Resource:** [Projects](../resources/Projects.md)
**Create a container protection tag rule for a project. 5 rule limit per project.**
**Operation ID:** `postApiV4ProjectsIdRegistryProtectionTagRules`

This feature was introduced in GitLab 18.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 422 | Unprocessable Entity |

**Success Response Schema:**

[APIEntitiesProjectsContainerRegistryProtectionTagRule](../schemas/APIEntitiesProjectsContainerRegistryProtectionTagRule/APIEntitiesProjectsContainerRegistryProtectionTagRule.md)

