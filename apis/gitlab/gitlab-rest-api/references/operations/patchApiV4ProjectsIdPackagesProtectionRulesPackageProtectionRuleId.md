# PATCH /api/v4/projects/{id}/packages/protection/rules/{package_protection_rule_id}

**Resource:** [Projects](../resources/Projects.md)
**Update a package protection rule for a project**
**Operation ID:** `patchApiV4ProjectsIdPackagesProtectionRulesPackageProtectionRuleId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_protection_rule_id` | path | integer | Yes | The ID of the package protection rule |

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

[APIEntitiesProjectsPackagesProtectionRule](../schemas/APIEntitiesProjectsPackagesProtectionRule/APIEntitiesProjectsPackagesProtectionRule.md)

