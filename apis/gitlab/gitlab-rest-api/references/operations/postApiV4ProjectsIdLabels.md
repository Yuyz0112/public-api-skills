# POST /api/v4/projects/{id}/labels

**Resource:** [Labels](../resources/Labels.md)
**Create a new label**
**Operation ID:** `postApiV4ProjectsIdLabels`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesProjectLabel](../schemas/APIEntitiesProjectLabel/APIEntitiesProjectLabel.md)

