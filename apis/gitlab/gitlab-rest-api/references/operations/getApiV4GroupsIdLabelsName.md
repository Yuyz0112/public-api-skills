# GET /api/v4/groups/{id}/labels/{name}

**Resource:** [Labels](../resources/Labels.md)
**Get a single label**
**Operation ID:** `getApiV4GroupsIdLabelsName`

This feature was added in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `include_ancestor_groups` | query | boolean | No | Include ancestor groups |
| `include_descendant_groups` | query | boolean | No | Include descendant groups. This feature was added in GitLab 13.6 |
| `only_group_labels` | query | boolean | No | Toggle to include only group labels or also project labels. This feature was added in GitLab 13.6 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupLabel](../schemas/APIEntitiesGroupLabel/APIEntitiesGroupLabel.md)

