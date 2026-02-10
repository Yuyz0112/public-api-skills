# GET /api/v4/projects/{id}/labels/{name}

**Resource:** [Labels](../resources/Labels.md)
**Get a single label**
**Operation ID:** `getApiV4ProjectsIdLabelsName`

This feature was added in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `include_ancestor_groups` | query | boolean | No | Include ancestor groups |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectLabel](../schemas/APIEntitiesProjectLabel/APIEntitiesProjectLabel.md)

