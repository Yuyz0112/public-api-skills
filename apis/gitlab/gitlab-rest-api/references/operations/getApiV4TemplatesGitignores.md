# GET /api/v4/templates/gitignores

**Resource:** [Templates](../resources/Templates.md)
**Get all .gitignore templates**
**Operation ID:** `getApiV4TemplatesGitignores`

This feature was introduced in GitLab 8.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesTemplatesList](../schemas/APIEntitiesTemplatesList/APIEntitiesTemplatesList.md)

