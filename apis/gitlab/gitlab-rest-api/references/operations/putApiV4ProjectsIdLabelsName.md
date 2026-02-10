# PUT /api/v4/projects/{id}/labels/{name}

**Resource:** [Labels](../resources/Labels.md)
**Update an existing label. At least one optional parameter is required.**
**Operation ID:** `putApiV4ProjectsIdLabelsName`

This feature was added in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name or id of the label to be updated |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectLabel](../schemas/APIEntitiesProjectLabel/APIEntitiesProjectLabel.md)

