# PUT /api/v4/projects/{id}/labels/{name}/promote

**Resource:** [Labels](../resources/Labels.md)
**Promote a label to a group label**
**Operation ID:** `putApiV4ProjectsIdLabelsNamePromote`

This feature was added in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name or id of the label to be promoted |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupLabel](../schemas/APIEntitiesGroupLabel/APIEntitiesGroupLabel.md)

