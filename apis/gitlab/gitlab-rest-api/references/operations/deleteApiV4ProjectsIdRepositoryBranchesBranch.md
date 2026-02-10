# DELETE /api/v4/projects/{id}/repository/branches/{branch}

**Resource:** [Branches](../resources/Branches.md)
**Delete a branch**
**Operation ID:** `deleteApiV4ProjectsIdRepositoryBranchesBranch`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `branch` | path | string | Yes | The name of the branch |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 404 | Branch Not Found |

