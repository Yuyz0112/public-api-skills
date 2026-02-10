# GET /api/v4/templates/dockerfiles

**Resource:** [Templates](../resources/Templates.md)
**Get all Dockerfile templates**
**Operation ID:** `getApiV4TemplatesDockerfiles`

This feature was introduced in GitLab 8.15.

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

