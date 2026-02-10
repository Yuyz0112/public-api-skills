# GET /api/v4/templates/gitlab_ci_ymls

**Resource:** [Templates](../resources/Templates.md)
**Get all GitLab CI/CD YAML templates**
**Operation ID:** `getApiV4TemplatesGitlabCiYmls`

This feature was introduced in GitLab 8.9.

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

