# PUT /api/v4/groups/{id}/labels/{name}

**Resource:** [Labels](../resources/Labels.md)
**Update an existing label. At least one optional parameter is required.**
**Operation ID:** `putApiV4GroupsIdLabelsName`

This feature was added in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `name` | path | string | Yes | The name or id of the label to be updated |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupLabel](../schemas/APIEntitiesGroupLabel/APIEntitiesGroupLabel.md)

