# PATCH /api/v4/projects/{id}/registry/protection/tag/rules/{protection_rule_id}

**Resource:** [Projects](../resources/Projects.md)
**Update a container protection tag rule for a project.**
**Operation ID:** `patchApiV4ProjectsIdRegistryProtectionTagRulesProtectionRuleId`

This feature was introduced in GitLab 18.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `protection_rule_id` | path | integer | Yes | The ID of the container protection tag rule. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 422 | Unprocessable Entity |

**Success Response Schema:**

[APIEntitiesProjectsContainerRegistryProtectionTagRule](../schemas/APIEntitiesProjectsContainerRegistryProtectionTagRule/APIEntitiesProjectsContainerRegistryProtectionTagRule.md)

