# GET /api/v4/templates/gitignores/{name}

**Resource:** [Templates](../resources/Templates.md)
**Get a single .gitignore template**
**Operation ID:** `getApiV4TemplatesGitignoresName`

This feature was introduced in GitLab 8.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | path | string | Yes | The name of the .gitignore template |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesTemplate](../schemas/APIEntitiesTemplate/APIEntitiesTemplate.md)

