# PUT /api/v4/projects/{id}/labels/promote

**Resource:** [Labels](../resources/Labels.md)
**Promote a label to a group label**
**Operation ID:** `putApiV4ProjectsIdLabelsPromote`

This feature was added in GitLab 12.3 and deprecated in GitLab 12.4.

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
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupLabel](../schemas/APIEntitiesGroupLabel/APIEntitiesGroupLabel.md)

