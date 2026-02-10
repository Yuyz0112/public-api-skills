# GET /api/v4/projects/{id}/releases/permalink/latest(/)(*suffix_path)

**Resource:** [Releases](../resources/Releases.md)
**Get the latest project release**
**Operation ID:** `getApiV4ProjectsIdReleasesPermalinkLatest()(*suffixPath)`

This feature was introduced in GitLab 15.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `suffix_path` | query | string | Yes | The path to be suffixed to the latest release |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 404 | Not found |

