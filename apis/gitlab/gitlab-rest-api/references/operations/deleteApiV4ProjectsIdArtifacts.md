# DELETE /api/v4/projects/{id}/artifacts

**Resource:** [Job artifacts](../resources/Job-artifacts.md)
**Expire the artifacts files from a project**
**Operation ID:** `deleteApiV4ProjectsIdArtifacts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | Unauthorized |
| 403 | Forbidden |
| 409 | Conflict |

