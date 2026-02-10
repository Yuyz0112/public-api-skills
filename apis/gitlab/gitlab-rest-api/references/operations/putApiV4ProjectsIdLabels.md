# PUT /api/v4/projects/{id}/labels

**Resource:** [Labels](../resources/Labels.md)
**Update an existing label. At least one optional parameter is required.**
**Operation ID:** `putApiV4ProjectsIdLabels`

This feature was deprecated in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectLabel](../schemas/APIEntitiesProjectLabel/APIEntitiesProjectLabel.md)

