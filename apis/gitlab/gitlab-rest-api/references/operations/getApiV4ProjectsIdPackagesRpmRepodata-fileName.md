# GET /api/v4/projects/{id}/packages/rpm/repodata/*file_name

**Resource:** [Packages](../resources/Packages.md)
**Download repository metadata files**
**Operation ID:** `getApiV4ProjectsIdPackagesRpmRepodata*fileName`

This feature was introduced in GitLab 15.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `file_name` | query | string | Yes | Repository metadata file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

