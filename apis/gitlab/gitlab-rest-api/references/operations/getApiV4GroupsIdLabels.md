# GET /api/v4/groups/{id}/labels

**Resource:** [Labels](../resources/Labels.md)
**Get all labels of the group**
**Operation ID:** `getApiV4GroupsIdLabels`

This feature was added in GitLab 11.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `with_counts` | query | boolean | No | Include issue and merge request counts |
| `include_ancestor_groups` | query | boolean | No | Include ancestor groups |
| `include_descendant_groups` | query | boolean | No | Include descendant groups. This feature was added in GitLab 13.6 |
| `only_group_labels` | query | boolean | No | Toggle to include only group labels or also project labels. This feature was added in GitLab 13.6 |
| `search` | query | string | No | Keyword to filter labels by. This feature was added in GitLab 13.6 |
| `archived` | query | boolean | No | Filter by archived status. This feature is gated by the :labels_archive feature flag |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupLabel](../schemas/APIEntitiesGroupLabel/APIEntitiesGroupLabel.md)

