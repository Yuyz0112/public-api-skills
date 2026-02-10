# GET /api/v4/projects/{id}/repository/blobs/{sha}

**Resource:** [Repositories](../resources/Repositories.md)
**Get a blob from the repository**
**Operation ID:** `getApiV4ProjectsIdRepositoryBlobsSha`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | path | string | Yes | The commit hash |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

