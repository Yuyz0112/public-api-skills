# GET /api/v4/projects/{id}/repository/commits/{sha}/statuses

**Resource:** [Commit statuses](../resources/Commit-statuses.md)
**Get a commit's statuses**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommitsShaStatuses`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the project. |
| `sha` | path | string | Yes | Hash of the commit. |
| `ref` | query | string | No | Name of the branch or tag. Default is the default branch. |
| `stage` | query | string | No | Filter statuses by build stage. |
| `name` | query | string | No | Filter statuses by job name. |
| `pipeline_id` | query | integer | No | Filter statuses by pipeline ID. |
| `all` | query | boolean | No | Include all statuses instead of latest only. Default is `false`. |
| `order_by` | query | enum: id, pipeline_id | No | Values for sorting statuses. Valid values are `id` and `pipeline_id`. Default is `id`. |
| `sort` | query | enum: asc, desc | No | Sort statuses in ascending or descending order. Valid values are `asc` and `desc`. Default is `asc`. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCommitStatus](../schemas/APIEntitiesCommitStatus/APIEntitiesCommitStatus.md)

