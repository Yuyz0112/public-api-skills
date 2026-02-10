# DELETE /api/v4/projects/{id}/packages/protection/rules/{package_protection_rule_id}

**Resource:** [Projects](../resources/Projects.md)
**Delete package protection rule**
**Operation ID:** `deleteApiV4ProjectsIdPackagesProtectionRulesPackageProtectionRuleId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_protection_rule_id` | path | integer | Yes | The ID of the package protection rule |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

