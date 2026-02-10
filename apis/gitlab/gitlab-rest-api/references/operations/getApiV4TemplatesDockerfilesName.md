# GET /api/v4/templates/dockerfiles/{name}

**Resource:** [Templates](../resources/Templates.md)
**Get a single Dockerfile template**
**Operation ID:** `getApiV4TemplatesDockerfilesName`

This feature was introduced in GitLab 8.15.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | path | string | Yes | The name of the Dockerfile template |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesTemplate](../schemas/APIEntitiesTemplate/APIEntitiesTemplate.md)

