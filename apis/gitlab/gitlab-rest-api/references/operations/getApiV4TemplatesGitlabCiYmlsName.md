# GET /api/v4/templates/gitlab_ci_ymls/{name}

**Resource:** [Templates](../resources/Templates.md)
**Get a single GitLab CI/CD YAML template**
**Operation ID:** `getApiV4TemplatesGitlabCiYmlsName`

This feature was introduced in GitLab 8.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | path | string | Yes | The name of the GitLab CI/CD YAML template |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesTemplate](../schemas/APIEntitiesTemplate/APIEntitiesTemplate.md)

