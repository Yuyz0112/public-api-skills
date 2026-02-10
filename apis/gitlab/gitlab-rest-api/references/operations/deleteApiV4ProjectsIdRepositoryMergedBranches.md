# DELETE /api/v4/projects/{id}/repository/merged_branches

**Resource:** [Branches](../resources/Branches.md)
**Delete all merged branches**
**Operation ID:** `deleteApiV4ProjectsIdRepositoryMergedBranches`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 404 | 404 Project Not Found |

