# GET /api/v4/projects/{id}/packages/protection/rules

**Resource:** [Projects](../resources/Projects.md)
**Get list of package protection rules for a project**
**Operation ID:** `getApiV4ProjectsIdPackagesProtectionRules`

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

[APIEntitiesProjectsPackagesProtectionRule](../schemas/APIEntitiesProjectsPackagesProtectionRule/APIEntitiesProjectsPackagesProtectionRule.md)

