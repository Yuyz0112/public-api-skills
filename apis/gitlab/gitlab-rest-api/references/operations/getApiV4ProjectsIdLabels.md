# GET /api/v4/projects/{id}/labels

**Resource:** [Labels](../resources/Labels.md)
**Get all labels of the project**
**Operation ID:** `getApiV4ProjectsIdLabels`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `with_counts` | query | boolean | No | Include issue and merge request counts |
| `include_ancestor_groups` | query | boolean | No | Include ancestor groups |
| `search` | query | string | No | Keyword to filter labels by. This feature was added in GitLab 13.6 |
| `archived` | query | boolean | No | Filter by archived status. This feature is gated by the :labels_archive feature flag |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectLabel](../schemas/APIEntitiesProjectLabel/APIEntitiesProjectLabel.md)

