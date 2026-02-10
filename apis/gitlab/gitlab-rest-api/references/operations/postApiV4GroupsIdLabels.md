# POST /api/v4/groups/{id}/labels

**Resource:** [Labels](../resources/Labels.md)
**Create a new label**
**Operation ID:** `postApiV4GroupsIdLabels`

This feature was added in GitLab 11.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesGroupLabel](../schemas/APIEntitiesGroupLabel/APIEntitiesGroupLabel.md)

